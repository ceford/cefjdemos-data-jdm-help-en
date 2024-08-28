<!-- Filename: Help4.x:Menu_Item:_Site_Configuration_Options / Display title: Site Configuration Options -->

## Description

The *Site Configuration Options* menu item type allows a Joomla!
super-user to easily change the site configuration. The page it links to
is a simplified version of the Administrator's Site Global Configuration
page. It provides access to some of the important site configuration
parameters. After a change, the super-user will see the results
immediately. This menu item is intended to help new super-users with
site development.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new **Display Site Configuration** menu item type:

- Select **Menus → \[name of the menu\]** from the from the
  Administrator menu (for example, **Menus → Main Menu**). Then...
  - Click the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the Configuration item to open a
    list and then select the **Site Configuration Options** item..

To edit an existing Site Configuration Options menu item: Select its
Title in the Menus: Items list.

## Screenshot

![Menu item type Site Configuration options](../../../en/images/menu-items/configuration-site-configuration-options-details.png)

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Details Tab

#### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.
- **Parent Item.** The parent menu item for this menu item. Used to
  determine whether a Menu Item is a top-level item or a submenu item.
  Select 'Menu Item Root' (the default value) if this is a top-level
  Menu Item. Otherwise, select the Menu Item that is this item's parent.
- **Ordering.** You can change the order of an item within a list as
  follows:
  - If the list Filter Options include a Position filter select the
    desired Position. This will limit the list to items that are
    assigned to that Position.
  - Select the Ordering icon <i class="fa-solid fa-sort"></i> in the Table
    heading to make it the active ordering item. The ordering icons in
    each row will change from light grey to dark grey and the pointer
    will change to a drag arrow on hover.
  - Select one of the Ordering icons <span class="icon-ellipsis-v"></i> and
    drag it up or down to change the position of that row in the list.
    The items will display in the new order within the Position.
- **Status**. The published status of the item.
- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).
- **Default Page**. If Yes, this menu item is the default or home page
  for the site. There must be exactly one menu item set as the default
  page. You can change the default page in two ways:
  1.  Click on the Home column of the desired menu item in the Menus: Items
      screen.
  2.  Open the menu item for the new default page and change the Default
      Page setting to Yes.
- **Access**. The viewing Access  Level   for this item.
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

## Front End Screenshot

<img
src="https://docs.joomla.org/images/1/16/Help-4x-Menus-Menu-Display_Configuration-front-end-screenshot-en.png"
decoding="async" data-file-width="588" data-file-height="843"
width="588" height="843"
alt="Menu Site Configuration options frontend screenshot" />
