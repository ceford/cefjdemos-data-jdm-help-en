<!-- Filename: Help4.x:Menu_Item:_Compact_List_of_Tagged_Items / Display title: Compact List of Tagged Items -->

## Description

The **Compact List of Tagged Items** menu item type is used to create a
page ...

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

To create a new Compact List of Tagged Items menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar.
  - Select the Menu Item Type Select button.
  - In the modal dialog select the Tags item to open a list and then
    select the **Compact List of Tagged Items** item.

To edit an existing Compact List of Tags Items menu item:

- Select its Title in the Menus: Items list.

## Screenshot

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-compact-list-of-tagged-items-details-tab.png)

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
- **Tag**. Select the tag to use.
- **Content Type.** Only tags of the selected types will be displayed
  (optional).
- **Language Filter**. (Use Global (All)/All/Current/English
  (en-GB)/...). Optionally filter the list of tags based on language.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

### Tag Options Tab

![Compact List of Tagged Items tag options tab](../../../en/images/menu-items/tags-compact-list-of-tagged-items-tag-options-tab.png)

- **Show Tag Name.** (Use Global(Hide)/Hide/Show). For a layout with one
  tag, show the tag name.
- **Tag Image.** (Use Global(Hide)/Hide/Show). For a layout with one
  tag, show the image for the tag.
- **Tag Description.** (Use Global(Hide)/Hide/Show). Show or hide the
  description for the tag (only used when a single tag is selected).
- **Image.** Select or upload the image.
- **Description**. The description for the item. Category, Subcategory
  and Web Link descriptions may be shown on web pages, depending on the
  parameter settings. These descriptions are entered using the same
  editor that is used for Articles.
- **Ordering:** (default). The column in which to sort displayed items
  in the table. The values are the same as the column heading names.
- **Direction.** Sort order. Descending is highest to lowest. Ascending
  is lowest to highest.

### List Layouts Tab

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-compact-list-of-tagged-items-list-layouts-tab.png)

- **Item Image** Show or hide the image for each item.
- **Item Description** Show or hide the description for each item in the list. 
  The length may be limited using the Maximum Character option.
- **Maximum Characters** The maximum number of characters to display
  from the description in each tag.
- **Filter Field** Show or hide the Filter Field, a text field  where a user 
  can enter a field to be used to filter the articles shown in  the list.
- **Table Headings** Show or hide the Table Headings.
- **Display Select** Show or hide the control that allows the user to select 
  the number of items to show in the list. 
- **\# Items to List** The number of tagged items to list on a page.
- **Pagination** Show or hide the Pagination support at the bottom of the page 
  that allow the User to navigate to additional pages. 
- **Pagination Summary** Show or hide the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. 
- **Date** Show or hide a date in the list. 
- **Date Format** Optional format string to control the format of the
  date (if shown). If left blank, the date will use the DATE_FORMAT_LC1
  format from the language file (for example, "D M Y" for "31 December
  2012" or "m-d-y" for "12-31-12").

### Item Selection Options Tab

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-compact-list-of-tagged-items-item-selection-options-tab.png)

- **Match Type.** (Use Global (Any), All, Any) All will return items
  that have all of the tags. Any will return items that have at least
  one of the tags.
- **Child Tags.** (Use Global (Exclude), Exclude, Include) Include or
  exclude child tags from the result list for a tag.
