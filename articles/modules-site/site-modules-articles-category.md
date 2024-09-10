<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category / Display title: Modules: Articles - Category -->

## Description

The *Articles - Category* module type displays a list of published
articles from one or more categories.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Modules: Modules Tab](jdocmanual?article=help/modules/modules-module-tab).
* [The Modules: Menu Assignment Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [The Modules: Advanced Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

<!-- ToDo: A tutorial to show how to use this module -->

## How to Access

- Select **System → Manage Panel → Site Modules** from the
  Administrator menu. Then...
  - To create a new module: select the **New** button from the Toolbar. Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

![articles category module tab](../../../en/images/modules-site/modules-articles-category-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Mode** Select the mode to use. If Normal Mode is chosen, then simply 
  configure the module and it will display a static list of Articles on 
  the menu items you assign the module to. If Dynamic Mode is chosen, then 
  you can still configure the module normally, however now the Category option 
  will no longer be used. Instead, the module will dynamically detect whether 
  or not you are on a Category view and will display the list of articles within
  that Category accordingly. When Dynamic Mode is chosen, it is best to
  leave the module set to display on all pages, as it will decide
  whether or not to display anything dynamically.
- **Show on Article Page** This item appears if *Dynamic* Mode is selected. 
  Select to Show or Hide an Article List from Article Pages. This means that 
  the module will only display itself dynamically on Category Pages.

### Filtering Options Tab

![articles category filtering options tab](../../../en/images/modules-site/modules-articles-category-filtering-options-tab.png)

- **Featured Articles** Show or hide or select Only Featured Articles.
- **Count** The number of items to display. The default value of 0 will
  display all articles.
- **Category Filtering Type** Include or exclude the selected categories.
- **Category** Select one or more categories.
- **Child Category Articles** Include or exclude child category articles.
- **Category Depth** The number of child category levels to return.
- **Author Filtering Type** Include or exclude articles by the selected authors.
- **Authors** Select one or more authors from the list.
- **Author Alias Filtering Type** Include or exclude the selected author aliases.
- **Author Aliases** Select one or more author aliases from the list.
- **Article IDs to Exclude** Enter each Article ID to exclude on a new line.
- **Date Filtering** Select date filtering type.
- **Date Range Field** Select which date field range use.
- **Start Date Range** If Date Range is selected above, enter a starting date.
- **To Date** If Date Range is selected above, enter an end date.
- **Relative Date** If Relative Date is selected above, enter a numeric day 
  value. Results will be retrieved relative to the current date and the value 
  entered.

### Ordering Options Tab

![articles category ordering options tab](../../../en/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Article Field to Order By** Select a field from the list. Featured
  Ordering should only be used when the Filtering Option for Featured
  Articles is set to *Only*.
- **Ordering Direction** Select the article ordering direction.

### Grouping Options Tab

![articles category grouping options tab](../../../en/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Article Grouping** Select an article grouping method from the list.
- **Grouping Direction** Select the ordering direction.
- **Month and Year Display Format** Enter in a valid date format.

### Display Options Tab

![articles category display options tab](../../../en/images/modules-site/modules-articles-category-display-options-tab.png)

- **Linked Titles** Show titles as links to articles.
- **Date** Show* or hide the article date.
- **Date Field** Select the date field to display.
- **Date Format** Enter in a valid date format.
- **Category** Show or hide the article category name.
- **Hits** Show or hide the article hits.
- **Author** Show or hide the author or author alias name.
- **Introtext** Show or hide the article intro text.
- **Introtext Limit** The maximum number of characters to display.
- **Show "Read More"** Show or hide the *Read more...* link if the article 
  main text has been provided.
- **Show Title with Read More** Show or hide the article title in the 
  *Read More...* link.
- **Read More Limit** Limit the number of article title characters to show in 
  the *Read More...* link.
