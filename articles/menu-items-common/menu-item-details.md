<!-- Filename: Help6.x:Menu_Item_Details / Display title: Menu Item Details-->

## Description

All menu items have a similar layout but some of the form fields and
some of the tabs change from type to type. This page describes the initial 
layout of the **Details** tab before a menu item type is selected. 

## How to Access

* Select any **Site Menu** from the Administrator menu.
* Select the **New** button from the Toolbar.

## Screenshot

![menu item details tab](../../../en/images/menu-items-common/menu-item-details.png)

The screenshots in each of the item type Help pages differ in details from
this screenshot.

## Form Fields

- **Menu Title** The title that will display for this menu item.
- **Alias** The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Menu Item**. Select a Menu Item name to point Alias Menu Item name
  at. The drop down list is sectioned by Menu Names, with a list of Menu
  Item names under each Menu Name.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Use Redirection.** The Template Style field is not used if this
  options is set to Yes.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

### Right Panel

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
  - Select one of the Ordering drag icons <span class="icon-ellipsis-v"></i> and
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
