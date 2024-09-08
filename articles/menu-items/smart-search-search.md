<!-- Filename: Help4.x:Menu_Item:_Search / Display title: Search -->

## Description

The **Search** menu item type is used to create a page for Smart Search
Results. It can be used in conjunction with a Smart Search module to
control a Search Results Page layout.

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

![Menu Item Smart Search details tab](../../../en/images/menu-items/smart-search-search-details-tab.png)

## Form Fields

If *Use Global* is selected for any option the default value from the 
*Smart Search: Options* is used.

### Options Tab

![Menu Item Smart Search options tab](../../../en/images/menu-items/smart-search-search-options-tab.png)

- **Date Filters** Show or hide the start and end date filters in Advanced Search.
- **Advanced Search** Shor ot hide the Advanced Search for element.
- **Expand Advanced Search** Show or hide Advanced Search in expanded state.
- **Result Taxonomy** ...?
- **Result Description** Show or hide a description under link in search results.
- **Description Length** The number of characters of the description to show 
  in the search results. The default is 255.
- **Result Date** ...?
- **Result URL** Show or hide the result item's URL in search results. The URL
  is located under the description.

### Advanced Tab

![Menu Item Smart Search advanced tab](../../../en/images/menu-items/smart-search-search-advanced-tab.png)

- **Display Select** Show or hide the Display \# control that allows the user 
  to select the number of items to show in the list.
- **Pagination** Show or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    The following options are available.
    - *Use Global* Use the default value from the component options screen.
    - *Auto* Pagination links shown if needed.
    - *Show* Pagination links shown if needed.
    - *Hide* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Results** Show or hide the current page number and total number
  of pages (for example *Page 1 of 2*) at the bottom of each page.
- **Allow Empty Search** If a filter is selected, allows an empty
  search string to initiate a search with the filter constraints.
- **Did You Mean** Whether to suggest alternative search terms when a
  search produces no result.
- **Query Explanation** Show or hide a detailed explanation of the
  search requested.
- **Show Sort Fields** Show or hide the additional sort fields.
- **Additional Sort Fields**: Choose one or more fields on which to sort the
  search results:
  - *Relevance* Order the results by relevance
  - *Title* Order the results by title
  - *Date* Order the results by date
  - *List price* Order the results by list price
  - *Sales price* Order the results by sales price
- **Sort Direction** Direction to sort search results.
