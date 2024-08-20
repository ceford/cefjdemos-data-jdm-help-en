<!-- Filename: Help4.x:Site_Modules:_Articles_-_Category / Display title: Modules: Articles - Category -->

## Description

The **Articles - Category** module type displays a list of published
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
  - To create a new module: select the **New** button from the Toolbar.
    Then...
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

- **Featured Articles:** (*Show*/*Hide*/*Only*). Select to Show, Hide,
  or Only display Featured Articles.
- **Count:** The number of items to display. The default value of 0 will
  display all articles.
- **Category Filtering Type:** (*Inclusive*/*Exclusive*). Select
  Inclusive to Include the Selected Categories, Exclusive to Exclude the
  Selected Categories.
- **Category:** Please select one or more categories.
- **Child Category Articles:** (*Include*/*Exclude*). Include or Exclude
  Articles from Child Categories.
- **Category Depth:** The number of child category levels to return.
- **Author Filtering Type:** (*Inclusive*/*Exclusive*). Select Inclusive
  to Include the Selected Authors, Exclusive to Exclude the Selected
  Authors.
- **Authors:** Select one or more authors from the list below.
- **Author Alias Filtering Type:** (*Inclusive*/*Exclusive*). Select
  Inclusive to Include the Selected Author Aliases, Exclusive to Exclude
  the Selected Author Aliases.
- **Author Aliases:** Select one or more author aliases from the list
  below.
- **Article IDs to Exclude:** Please enter each Article ID on a new
  line.
- **Date Filtering:** (*Off*/*Date Range*/*Relative Date*). Select Date
  Filtering Type.
- **Date Range Field:** (*Created Date*/*Modified Date*/*Start
  Publishing Date*). Select which date field you want the date range to
  be applied to.
- **Start Date Range:** If Date Range is selected above, please enter a
  Starting Date.
- **To Date:** If Date Range is selected above, please enter an End
  Date.
- **Relative Date:** If Relative Date is selected above, please enter in
  a numeric day value. Results will be retrieved relative to the current
  date and the value you enter.

### Ordering Options Tab

![articles category ordering options tab](../../../en/images/modules-site/modules-articles-category-ordering-options-tab.png)

- **Article Field to Order By:** (*Article Manager Order*/*Featured
  Articles Order*/*Hits*/*Title*/*ID*/*Alias*/*Created Date*/...).
  Select which field you would like Articles to be ordered by. Featured
  Ordering should only be used when Filtering Option for Featured
  Articles is set to 'Only'.
- **Ordering Direction:** (*Descending*/*Ascending*). Select the
  direction you would like Articles to be ordered by.

### Grouping Options Tab

![articles category grouping options tab](../../../en/images/modules-site/modules-articles-category-grouping-options-tab.png)

- **Article Grouping:** (*None*/*Year*/*Month and
  Year*/*Author*/*Category*). Select how you would like the articles to
  be grouped.
- **Grouping Direction:** (*Descending*/*Ascending*). Select the
  direction you would like the Article Groupings to be ordered by.
- **Month and Year Display Format:** Please enter in a valid date
  format.

### Display Options Tab

![articles category display options tab](../../../en/images/modules-site/modules-articles-category-display-options-tab.png)

- **Linked Titles:** (*Yes*/*No*).
- **Date:** (*Show*/*Hide*). Select Show if you would like the date
  displayed.
- **Date Field:** (*Created Date*/*Modified Date*/*Start Publishing
  Date*). Select which date field you want to display.
- **Date Format:** Please enter in a valid date format.
- **Category:** (*Show*/*Hide*). Select Show if you would like the
  category name displayed.
- **Hits:** (*Show*/*Hide*). Select Show if you would like the hits for
  each article to be displayed.
- **Author:** (*Show*/*Hide*). Select Show if you would like the author
  (or author alias instead, if available) to be displayed.
- **Introtext:** (*Show*/*Hide*). Select Show if you would like the
  introtext to be displayed.
- **Introtext Limit:** Please enter in a numeric character limit value.
  The introtext will be trimmed to the number of characters you enter.
- **Show "Read More":** (*Show*/*Hide*). If set to Show, the Read
  more... Link will show if Main text has been provided for the Article.
- **Show Title with Read More:** (*Show*/*Hide*). If set to show the
  Title of the Article will be shown on the Read More button.
- **Read More Limit:** Set a limit of number of characters in Article
  Title to show in Read More button.
