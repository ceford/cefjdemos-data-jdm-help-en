<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container / Display title: Menu Item: Components Menu Container -->

## Description

The Components Menu Container is used to show a component container in
the Administrator interface. A use case might be as follows:

Suppose you only wish to show certain users links to a subset of the
Components on your site. Super Users will see links to everything of
course. You can do this as follows:

- Create a new User Group named, say Branch, with Public as parent.
- Set the Global Permissions for this group to Allow Administrator Login.
- Create a new menu named, say, Branch Menu with no imported presets.
- Create a linked Module named, say, Branch Menu with menu to show as
  Branch Menu. Set Check Menu to No and Access to Public.
- Create a Components Menu Container menu item for the Branch Menu
  named, say, Branch Components.
  - Hide any components that you do not wish the Branch users to see.
  - Show those to which they should have access.
- Set the Component Permissions for the Branch Group to allowed for all
  except Configure ACL and Configure Options.

For a Super User the Administrator menu will have an obvious duplication
of links. However, a Branch user will only see the Branch Components
menu and the Home Dashboard. You will need to adjust the Access
permissions of the Quick Icon modules there too! And you really need to
create a Dashboard module for any components Branch users have access
to.

For users who need access to Articles you can add more menu items to the
Branch Menu. In this way you can build a complete custom menu for Branch
users.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).

## How To Access

To create a new Component Container Menu Item:

- Create a new Menu from **Menus → Manage** in the Administrator menu.
  - Select **Administrator** from the *Site/Administrator* dropdown selector.
  - Select the **New** button in the Toolbar. Fill in the form:
    - **Title** Branch Menu
    - **Unique Name** branch_menu
    - **Description** Custom menu for Branch.
    - **Import Preset** None
    - **Save**
    - **Permissions** Select *Branch* group and set all to *Allow*.
    - **Save & Close**
    - Select the **Create a Module** button and fill out the dialogue form:
    - **Title** Branch Components
    - **Check Menu** No (otherwise there will be a message inviting you to 
      *turn on the menu recovery mode*.)
    - **Access** Special
    - **Position** Menu
- Select **Menus → \[name of the menu\]** from the Administrator menu.
- Select the **New** Toolbar button to create a new menu item.
- Select the Menu Item Type **Select** button.
- Select the **List Component Container** link from **System Links** in
  the Menu Item Type modal dialog.

To edit an existing Component Container Menu Item, select its Title in
the Menu Items list.

## Screenshot

![Menu Item Components Menu Container](../../../en/images/menu-items/administrator-components-menu-container.png)

## Form Fields

- **Name** The name of the menu item, for example *Branch Menu*. It will appear
  at the bottom of the Administrator menu.
- **Alias** The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Details Tab

#### Left Panel

- **Menu Item Type** In this case *Components Menu Container*.
- **Show or Hide Menu Items** List of menu items with buttons to set
  visibility status. If a parent item is set to *Hide* all of the child
  items are hidden too, even if they are set to *Show*.

#### Right Panel

- **Menu** Shows which menu the link will appear in.
- **Parent** The item (category, menu item, and so on) that is the
  parent of the item being edited.
- **Ordering** Indicates the order of this Menu Item in the Menu. The
  default Order is to add the Menu Item to the end of the Menu. This
  Menu Item will moved to the order position just after the Menu Item
  selected from the drop-down list. Note that the Order of Menu Items
  can also be changed in the Menu Item Manager.
- **Status** The published status of the item.
- **Note** This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

## Tips

- The **Branch Components** item appears at the bottom of the Administrator
  menu. Access to the main Administrator menu and to this section can be
  customised for the Branch group.
