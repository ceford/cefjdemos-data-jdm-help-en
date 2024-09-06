<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: List All Categories -->

## Description

The *List All Categories in an Article Category Tree* menu item type is used 
to show Categories in a hierarchical list. Depending on the selected options 
for this layout, you can click on a category Title to show the articles in 
that category.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [The Category Tab](jdocmanual?article=help/menu-items-common/menu-item-category).
* [The Blog Layout Tab](jdocmanual?article=help/menu-items-common/menu-item-blog-layout).
* [The Options Tab](jdocmanual?article=help/menu-items-common/menu-item-article-options).
* [The Integration Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  Select the **New** button in the Toolbar.
2.  Select the Menu Item Type **Select** button.
3.  Select the **Articles** item.
4.  Select the **List All Categories in an Article Category Tree** item.

To edit a Menu Item:

- select a **Title** from the list

## Screenshot

![Menu Item Articles List All Categories details tab](../../../en/images/menu-items/articles-list-all-categories-details-tab.png)

## Form Fields

- **Title** The title that will display for this menu item.
- **Alias** The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Details tab

#### Left Panel

- **Menu Item Type** The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Select the Top Level Category**
  - *Root* Include all article categories.
  - Otherwise, select the desired top-level category. All child
    categories of the selected category will show in the menu item.
- **Link** The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window** Select from the dropdown list.
- **Template Style** Select from the dropdown list.

#### Right Panel

- **Menu** Shows which menu the link will appear in.

### Categories tab

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Top Level Category Description** Show the description for the
  top-level category.
- **Alternative Description** Enter an description to override the
  category description for the menu item.
- **Subcategory Levels** Control how many levels of subcategories to
  show.
- **Empty Categories** Show categories that don't contain any articles
  or subcategories.
- **Subcategories Descriptions** Show the description for
  subcategories.
- **\# Articles in Category** Show a count of the total number of
  articles in each category.

### Blog Layout tab

Blog Layout Options control the appearance of the category drill down if
that results in a blog layout.

The blog layout form has a different layout from that in the Common Elements
above but the fields are similar.

### List Layouts tab

The Options control the appearance of the category drill-down page when
that is presented as a Category List.

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-list-layouts-tab.png)

- **Display Select** Show the Display \# control that allows the user
  to select the number of articles to show.
- **Filter Field** Show a text field in the Frontend where a user can
  filter the articles.Options in the Backend menu item edit.
  - *Hide* Don't show a filter field.
  - *Title* Filter on article title.
  - *Author* Filter on the author's name.
  - *Hits* Filter on the number of article hits.
- **Table Headings** Show a heading in the article list in the
  Frontend.
- **Date** Show a date in the list.
  - *Hide* Don't show any date.
  - *Created* Show the created date.
  - *Modified* Show the date of the last modification.
  - *Published* Show the start publishing date.
- **Date Format** Optional format string to control the format of the
  date.
- **Hits** Show the number of hits for articles.
- **Author** Show the name of the author.
- **\# Articles to List** Number of articles shown in the list.

### Shared tab

The Shared Options apply for Shared Options in List, Blog and Featured
unless they are changed by the menu settings.

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Pagination** Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - *Hide: Pagination links not shown. Note* Users will not be able to
    navigate to additional pages.
  - *Show* Pagination links shown if needed.
  - *Auto* Pagination links shown if needed.
- **Pagination Summary** Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.

## Tips

- Categories can be "nested" into levels, similar to folders on a disk
  drive. In theory there is no absolute limit on the number of levels
  you can have. However, as a practical matter it is recommended to keep
  the levels to a minimum. The Show All Categories layout may not work
  correctly if the number of levels shown is greater than 5.
- If you set up category titles as linkable, the user can drill down on
  the category. When they do, they will normally see either a Category
  List or Category Blog menu item, depending on which option is
  selected. If there is a pre-existing menu item for this category (for
  example, a Category Blog menu item), then that menu item will show in
  the drill down and the options set for that menu item will control the
  page display. Otherwise, the options set for the current Show All
  Categories menu item will control the page display.
- You can set the option to drill down to a list or blog in 2 places.
  - In Articles: Options you can set the default value for all categories.
  - In Category: Edit you can set a value for a specific category. If this is 
    set, it overrides the default value.
- To customise a *Date Format: you can use D M Y for day month year or d-m-y
  for a short version for example 17-08-05. If left blank, the DATE_FORMAT_LC1 
  key translation is used from your language file.
