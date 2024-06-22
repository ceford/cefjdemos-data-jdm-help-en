<!-- Filename: Help4.x:Menu_Item:_Components_Menu_Container / Display title: Menu Item: Components Menu Container -->

## Description

The Components Menu Container is used to show a component container in
the Administrator interface. A use case might be as follows:

Suppose you only wish to show certain users links to a subset of the
Components on your site. Super Users will see links to everything of
course. You can do this as follows:

- Create a new User Group named, say Branch, with Public as parent.
- Set the Global Permissions for this group to Allow Administrator
  Login.
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

## How To Access

To create a new Component Container Menu Item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu.
- Select the **New** Toolbar button to create a new menu item.
- Select the Menu Item Type **Select** button.
- Select the **List Component Container** link from **System Links** in
  the Menu Item Type modal dialog.

To edit an existing Component Container Menu Item, select its Title in
the Menu Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/thumb/5/57/Help4x-Menus-Menu-Item-Components-Menu-Container-screen-en.png/800px-Help4x-Menus-Menu-Item-Components-Menu-Container-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/5/57/Help4x-Menus-Menu-Item-Components-Menu-Container-screen-en.png 1.5x"
data-file-width="1000" data-file-height="1309" width="800" height="1047"
alt="Menu Item Components Menu Container screen" />

## Form Fields

- **Name.** The full name of the menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Details Tab

#### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Show or Hide Menu Items.** List of menu items with buttons to set
  visibility status.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.
- **Parent**. The item (category, menu item, and so on) that is the
  parent of the item being edited.
- **Ordering:** Indicates the order of this Menu Item in the Menu. The
  default Order is to add the Menu Item to the end of the Menu. This
  Menu Item will moved to the order position just after the Menu Item
  selected from the drop-down list. Note that the Order of Menu Items
  can also be changed in the Menu Item Manager.
- **Status**. The published status of the item.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### Link Type Tab

The Options control attributes of the link for this menu item in a
Joomla menu.

- **Link Title Attribute.** An optional custom description for the title
  attribute of the menu hyperlink.
- **Link Icon Class.** If an icon class is entered, it takes precedence
  over the link image.
- **Link Image.** An optional image to be used with the menu hyperlink.
- **Image Class** An optional custom CSS style to apply to the menu
  image.
- **Display Menu Item Title.** (No/Yes) If an optional image is added,
  whether to add the menu title next to the image.
- **Display in Menu.** (No/Yes) Option to display the image in a menu.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.

Or

- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Help**. Opens this help screen.
