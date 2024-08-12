<!-- Filename: Help4.x:Menu_Item:_List_All_Tags / Display title: List All Tags -->

## Description

The **List All Tags** menu item type is Used to create a page containing
items with selected tags.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [The Integration Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new **List All Tags** menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the Tags item to open a list and then
    select the **List All Tags** item.

To edit an existing List All Tags menu item:

- Select its Title in the Menus: Items list.

## Screenshot

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-list-all-tags-details-tab.png)

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
- **Parent**. The item (category, menu item, and so on) that is the
  parent of the item being edited.
- **Language Filter**. (Use Global (All)/All/Current/English
  (en-GB)/...). Optionally filter the list of tags based on language.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

### Options Tab

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-list-all-tags-options-tab.png)

- **Number of Columns** The number of columns to arrange the tags in.
  Note that this may not be the number displayed if 12 does not divide
  evenly into it because display is based on a 12 column grid.
- **Heading Description** Description to display at the heading of tags
  list.
- **Show Heading Image** (Use Global/Hide/Show). Show an image at the
  heading of the tags list.
- **Heading Image File** Select or upload the image to display in the
  heading of the tags list.
- **Ordering** The column in which to sort displayed items
  in the table. The values are the same as the column heading names.
- **Direction** Sort order. Descending is highest to lowest. Ascending
  is lowest to highest.
- **Item Images**  Show or hide the first image for each item in the list.
- **Tag Description** Show or hide the description for the tag (only used 
  when a single tag is selected).
- **Maximum Characters** The maximum number of characters to display
  from the description in each tag.
- **Hits** Show or hide the number of times an item has been viewed.

### Selection Options Tab

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-list-all-tags-selection-options-tab.png)

- **Maximum Items** The maximum number of results to return.
- **Filter Field** Show or hide the Filter Field used to filter the articles 
  shown in the list.
- **Display Select.** Show or hide the \# control that allows the user to 
  select the number of items to show in the list.
- **Pagination** Show or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. 
- **Pagination Results** Show or hide the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.

