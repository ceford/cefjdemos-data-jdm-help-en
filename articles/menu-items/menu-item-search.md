<!-- Filename: Help4.x:Menu_Item:_Search / Display title: Menu Item: Search -->

## Description

The **Search** menu item type is used to create a page for Smart Search
Results. It can be used in conjunction with a Smart Search module to
control a Search Results Page layout.

## How To Access

To create a new Search menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the **New** button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the Smart Search item to open a list and
    then select the **Search** item.

To edit an existing Search menu item:

- Select its Title in the Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/2/28/Help-4x-Menus-Menu-Item-Finder-Search-screen-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menu Item Finder Search screen" />

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
- **Search Content Maps**. Optional, used to search in content map
  title.
- **Search Filters**. Select from list of \<Search filter\> in drop down
  to limit searches to the selected filter.

*Note: Filters must be created using Smart Search
Filters
before they are populated to this drop down list.*

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

### Options Tab

<img
src="https://docs.joomla.org/images/7/71/Help-4x-Menus-Menu-Item-Finder-Search-basic-options-screen-en.png"
decoding="async" data-file-width="600" data-file-height="373"
width="600" height="373"
alt="Menu Item Finder Search options tab" />

- **Date Filters**. Show the start and end date filters in Advanced
  Search.
- *Show:* Show filter in Advanced Search.
- *Hide:* Hide this filter in Advanced Search.
- *Use Global:* Use the default value from the Smart Search options.
- **Advanced Search**. Users should be able to see the Advanced Search.
- *Show:* Show Advanced Search.
- *Hide:* Hide Advanced Search.
- *Use Global:* Use the default value from the Smart Search options.
- **Expand Advanced Search**. Show Advanced Search in expanded state by
  default.
- *Show:* Show Expanded Advanced Search in results by default.
- *Hide:* Hide Expanded Advanced Search in results.
- *Use Global:* Use the default value from the Smart Search options.
- **Result Taxonomy.** ...?
- **Result Description:** Show a description under link in search
  results.
  - *Show:* Show description in search results.
  - *Hide:* Hide description in search results.
  - *Use Global:* Use the default value from the Smart Search options.
- **Description Length**. Number of characters of the description in
  search results. Enter \<number\> in field, default is 255.
- **Result Date.** ...?
- **Result URL:** Show the result item's URL in search results. The URL
  is located under the description.
  - *Show:* Show URL in search results.
  - *Hide:* Hide the URL in search results.
  - *Use Global:* Use the default value from the Smart Search options.

### Advanced Tab

<img
src="https://docs.joomla.org/images/4/4d/Help-4x-Menus-Menu-Item-Finder-Search-advanced-options-screen-en.png"
decoding="async" data-file-width="600" data-file-height="372"
width="600" height="372"
alt="Menu Item Finder Search advanced tab" />

- **Display Select.** (Use Global/Hide/Show) Whether to hide or show the
  Display \# control that allows the user to select the number of items
  to show in the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Pagination.** Hide or Show Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    The following options are available.
    - *Use Global:* Use the default value from the component options screen.
    - *Auto:* Pagination links shown if needed.
    - *Show:* Pagination links shown if needed.
    - *Hide:* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Results.** Hide or Show the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.
- **Allow Empty Search**. Only if a filter is selected. Allows an empty
  search string to initiate a search with the filter constraints.
- **Did You Mean**. Whether to suggest alternative search terms when a
  search produces no result.
- **Query Explanation**. Show or hide a detailed explanation of the
  search requested.
- **Show Sort Fields**: (*Show*/*Hide*) Show the additional sort fields.
- **Additional Sort Fields**: Choose one or more fields to sort the
  search results
  - Relevance: Order the results by relevance
  - Title: Order the results by title
  - Date: Order the results by date
  - List price: Order the results by list price
  - Sales price: Order the results by sales price
- **Sort Direction**. Direction to sort search results.
    - *Descending*.
    - *Ascending*.
    - *Use Global:* Use the default value from the Smart Search options.

### Integration Tab

<img
src="https://docs.joomla.org/images/7/79/Help-4x-Menus-Menu-Item-Finder-Search-integration-options-screen-en.png"
decoding="async" data-file-width="600" data-file-height="199"
width="600" height="199"
alt="Menu Item Finder Search integration tab" />

- **Show Feed Link.** (Use Global/Hide/Show) Whether to Hide or Show a
  link to a news feed (RSS Feed). If set to Show, a Feed Link will show
  up as a feed icon in the address bar of most modern browsers.

### Common Options

See Menus: New Item for help on fields common to all Menu Item types, including:

- Right Panel
- Link Type
- Page Display
- Metadata
- Associations
- Module Assignment

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.
- **Save as Copy**. Saves your changes to a copy of the current item.
  Does not affect the current item. This toolbar icon is not shown if
  you are creating a new item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.Or
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Help**. Opens this help screen.
