<!-- Filename: Help4.x:Menu_Item:_Compact_List_of_Tagged_Items / Display title: Menu Item: Compact List of Tagged Items -->

## Description

The **Compact List of Tagged Items** menu item type is used to create a
page ...

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

<img
src="https://docs.joomla.org/images/3/31/Help-4x-Menus-Menu-Item-Tags-Items-Compact-List-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menu Item Tags Items Compact List" />

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
  - Select the Ordering icon <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Ordering column header icon" /> in the Table
    heading to make it the active ordering item. The ordering icons in
    each row will change from light grey to dark grey and the pointer
    will change to a drag arrow on hover.
  - Select one of the Ordering icons <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Ordering drag icon" /> and
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

### Tag Options Tab

<img
src="https://docs.joomla.org/images/4/4f/Help-4x-Menus-Menu-Item-Tags-Items-Items-Compact-List-Tags-options-screenshot-en.png"
decoding="async" data-file-width="600" data-file-height="441"
width="600" height="441"
alt="Menu Item Tags Items Compact List tag options tab" />

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

<img
src="https://docs.joomla.org/images/c/c7/Help-4x-Menus-Menu-Item-Tags-Items-Items-Compact-List-ListLayout-options-screenshot-en.png"
decoding="async" data-file-width="600" data-file-height="255"
width="600" height="255"
alt="Menu Item Tags Items Compact List List Layouts tab" />

- **Item Image.** (Use Global/Hide/Show). Show the image for each item.
- **Item Description.** (Use Global/Hide/Show). Show or hide the
  description for each item in the list. The length may be limited using
  the Maximum Character option.
- **Maximum Characters.** The maximum number of characters to display
  from the description in each tag.
- **Filter Field.** The Filter Field creates a text field where a user
  can enter a field to be used to filter the articles shown in the list.
  An example of how this looks in the front-end layout is shown below.

The possible options for this (in the back-end menu item edit):

- *Use Global:* Use the value from Articles: Options.
  Only appears in Menu Item Type Options.
- *Hide:* Don't show a filter field.
- *Title:* Filter on article title.
- *Author:* Filter on the author's name.
- *Hits:* Filter on the number of article hits.
- **Display Select.** (Use Global/Hide/Show) Whether to hide or show the
  Display \# control that allows the user to select the number of items
  to show in the list. An example of how it is shown in the Front End
  (website) view below.

If there are more items than this number, you can use the page
navigation buttons (Start, Prev, Next, End, and page numbers) to
navigate between pages. Note that if you have a large number of items,
it may be helpful to use the Filter options, located above the column
headings, to limit which items display.

- **\# Items to List.** (Use Global, 5, 10, 15...) Default number of
  tagged items to list on a page.
- **Pagination.** Hide or Show Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    - *Use Global:* Use the default value from the component options screen.
    - *Auto:* Pagination links shown if needed.
    - *Show:* Pagination links shown if needed.
    - *Hide:* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Results.** Hide or Show the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.
- **Show Date.** This option allows you to show a date in the list. The
  options are as follows.
    - *Use Global:* Use the value set in Article Manager→Options.
    - *Hide:* Don't show any date.
    - *Created:* Show the created date.
    - *Modified:* Show the date of the last modification.
    - *Created:* Show the start publishing date.
- **Date Format.** Optional format string to control the format of the
  date (if shown). If left blank, the date will use the DATE_FORMAT_LC1
  format from the language file (for example, "D M Y" for "31 December
  2012" or "m-d-y" for "12-31-12").

### Item Selection Options Tab

<img
src="https://docs.joomla.org/images/f/f2/Help-4x-Menus-Menu-Item-Tags-Items-Items-Compact-List-Item-Selection-options-screenshot-en.png"
decoding="async" data-file-width="600" data-file-height="187"
width="600" height="187"
alt="Menu Item Tags Items Compact List Item Selection options tab" />

- **Match Type.** (Use Global (Any), All, Any) All will return items
  that have all of the tags. Any will return items that have at least
  one of the tags.
- **Child Tags.** (Use Global (Exclude), Exclude, Include) Include or
  exclude child tags from the result list for a tag.

### Integration Tab

- **RSS Feed Link**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.

### Common Options

See Menus: New Item for help on fields common to all Menu Item types, including:

- Right Panel
- Link Type
- Page Display
- Metadata
- Associations
- Module Assignment

## Toolbar

At the top of the page you will see the toolbar shown in the Screenshot
above. The functions are:

- **Save.** Saves the menu item and stays in the current screen.
- **Save & Close**. Saves the menu item and closes the current screen.
- **Save & New**. Saves the menu item and keeps the editing screen open
  and ready to create another menu item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Front End Screenshot

*Example Front End Site images are generic images using Joomla! core
installation supplied free Front End Templates. The actual view can
depend on the installed custom template used and the template's style
for those views on a Joomla! website.* Tags List Layout:

<img
src="https://docs.joomla.org/images/6/68/Help-4x-Menus-Menu-Tags-Compact-List-front-end-screenshot-en.png"
decoding="async" data-file-width="569" data-file-height="421"
width="569" height="421"
alt="Menu Tags Compact List front end screenshot" />
