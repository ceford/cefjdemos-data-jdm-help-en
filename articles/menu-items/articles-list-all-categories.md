<!-- Filename: Help4.x:Menu_Item:_List_All_Categories / Display title: List All Categories -->

## Description

The List All Categories menu item type is used to show Categories in a
hierarchical list. Depending on the selected options for this layout,
you can click on a category Title to show the articles in that category.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
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

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **List All Categories in an Article Category Tree** item.

To edit a Menu Item:

- select a **Title** from the list

## Screenshot

![Menu Item Articles List All Categories details tab](../../../en/images/menu-items/articles-list-all-categories-details-tab.png)

## Form Fields

- **Title**. The title that will display for this menu item.
- **Alias**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Details tab

#### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Select the Top Level Category**.
  - Root: Include all article categories.
  - Otherwise, select the desired top-level category. All child
    categories of the selected category will show in the menu item.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.

### Categories tab

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-categories-tab.png)

- **Top Level Category Description**. Show the description for the
  top-level category.
- **Alternative Description**. Enter an description to override the
  category description for the menu item.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
- **Empty Categories**. Show categories that don't contain any articles
  or subcategories.
- **Subcategories Descriptions**. Show the description for
  subcategories.
- **\# Articles in Category**. Show a count of the total number of
  articles in each category.

### Category tab

The Category settings control the way that category information is shown by the
menu item.

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-category-tab.png)

- **Category Title**. Show the title of the category.
- **Category Description**. Show the description for the category.
- **Category Image**. Show the category image.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
- **Empty Categories**. Show categories that don't contain any articles
  or subcategories.
- **No Articles Message**. Show a message "There are no articles in this
  category".
- **Subcategories Descriptions**. Show the descriptions for
  subcategories.
- **\# Articles in Category**. Show a count of the total number of
  articles in each category.

### Blog Layout tab

Blog Layout Options control the appearance of the category drill down if
that results in a blog layout.

Note: If there is a Category Blog menu item defined for a category, the
drill down will navigate to that menu item and the options for that menu
item will control the layout. The options here only take effect if there
is no menu item for a category.

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-blog-layout-tab.png)

- **Leading Article Class**. You can add any CSS class for your own
  styling ideas. Add a border on top with class boxed.For image position
  use for example image-left, image-right. Add image-alternate for
  alternate ordering of intro images.
- **Article Class**. You can add any CSS class for your own styling
  ideas. Add a border on top with class boxed.For image position use for
  example image-left, image-right. Add image-alternate for alternate
  ordering of intro images.
- **\# Leading Articles**. Number of Articles to show using the full
  width of the main display area. "0" means that no Articles will show
  when using the full width. If an Article has a "Read more..." break,
  only the part of the text before the break (the Intro text) will
  display.
- **\# Intro Articles**. Determines the number of Articles to display
  after the leading Article. These Articles will display in the number
  of columns set in the Columns parameter below. If an Article has a
  "Read more..." break, only the text before the break (Intro text) will
  display, followed by a "Read more..." link. The order in which to
  display the articles is determined by the Category Order and Article
  Order parameters below.
- **\# Links**. The number of Links to display in the Links area of the
  page. These links allow a User to link to additional Articles, if
  there are more Articles than can fit on the first page of the Blog
  Layout.
- **Include Subcategories**.
  - None: Only articles from the current category will show.
  - All: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
- **Category Order**.
  - No Order: Articles are ordered only by the Article Order, without
    regard to Category.
  - Title Alphabetical: Categories are displayed in alphabetical order
    (A to Z).
  - Title Reverse Alphabetical: Categories are displayed in reverse
    alphabetical order (Z to A).
  - Category Order: Categories are ordered according to the Order column
    entered in Articles: Categories.
- **Article Order**.
  - Featured Articles Order: Articles are ordered according to the Order
    column entered in Articles: Featured.
  - Most Recent First: Articles are displayed starting with the most
    recent and ending with the oldest.
  - Oldest First: Articles are displayed starting with the oldest and
    ending with the most recent.
  - Title Alphabetical: Articles are displayed by Title in alphabetical
    order (A to Z).
  - Title Reverse Alphabetical: Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Author Alphabetical: Articles are displayed by Author in
    alphabetical order (A to Z).
  - Author Reverse Alphabetical: Articles are displayed by Author in
    reverse alphabetical order (Z to A).
  - Most Hits: Articles are displayed by the number of hits, starting
    with the one with the most hits and ending with the one with the
    least hits.
  - Least Hits: Articles are displayed by the number of hits, starting
    with the one with the least hits and ending with the one with the
    most hits.
  - Article Order: Articles are ordered according to the Order column
    entered in
    Articles.
  - Article Reverse Order: Articles are ordered reverse to the according
    of the Order column entered in
    Articles.
- **Date for Ordering**. The date used when articles are sorted by date.
  - Created: Use the article created date.
  - Modified: Use the article modified date.
  - Published: Use the article start publishing date.

### List Layouts tab

The Options control the appearance of the category drill-down page when
that is presented as a Category List.

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-list-layouts-tab.png)

- **Display Select**. Show the Display \# control that allows the user
  to select the number of articles to show.
- **Filter Field**. Show a text field in the Frontend where a user can
  filter the articles.Options in the Backend menu item edit.
  - Hide: Don't show a filter field.
  - Title: Filter on article title.
  - Author: Filter on the author's name.
  - Hits: Filter on the number of article hits.
- **Table Headings**. Show a heading in the article list in the
  Frontend.
- **Date**. Show a date in the list.
  - Hide: Don't show any date.
  - Created: Show the created date.
  - Modified: Show the date of the last modification.
  - Published: Show the start publishing date.
- **Date Format**. Optional format string to control the format of the
  date.
- **Hits**. Show the number of hits for articles.
- **Author**. Show the name of the author.
- **\# Articles to List**. Number of articles shown in the list.

### Shared tab

The Shared Options apply for Shared Options in List, Blog and Featured
unless they are changed by the menu settings.

![Menu Item Articles List All Categories  categories tab](../../../en/images/menu-items/articles-list-all-categories-shared-tab.png)

- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Hide: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Show: Pagination links shown if needed.
  - Auto: Pagination links shown if needed.
- **Pagination Summary**. Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.

## Quick Tips

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
  - In Articles: Options
    you can set the default value for all categories.
  - In Category: Edit
    you can set a value for a specific category. If this is set, it
    overrides the default value.
- Customise 'Date Format': You can use D M Y for day month year or d-m-y
  for a short version for example 17-08-05. If left
  blank, it uses DATE_FORMAT_LC1 from your language file.
