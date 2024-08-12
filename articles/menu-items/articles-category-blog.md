<!-- Filename: Help4.x:Menu_Item:_Category_Blog / Display title: Category Blog -->

## Description

A Category Blog menu item typically has one or two leading article
tasters occupying the full width of the content area followed by more
articles tasters in one, two or three columns and additional links to
more Articles in the same category.

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
4.  select the **Category Blog** item.

To edit a Menu Item:

- select a **Title** from the list

## Screenshot

![Menu Item Category Blog](../../../en/images/menu-items/articles-category-blog-details-tab.png)

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
- **Choose a Category**. The articles that are within this category will
  be displayed.
- **Tags**. Optionally restrict displayed articles to those having the
  selected Tags.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.

### Category tab

These parameters control the way that category information is shown in the
page produced by this menu item type.

![Menu Item category tab](../../../en/images/menu-items/articles-category-blog-category-tab.png)

- **Category Title**. Show or hide the title of the category.
- **Category Description**. Show or hide the description for the category.
- **Category Image**. Show or hide the category image.
- **Subcategory Levels**. Control how many levels of subcategories to show.
- **Empty Categories**. Show or hide categories that don't contain any articles
  or subcategories.
- **No Articles Message**. Show or hide a message "There are no articles in this
  category".
- **Subcategories Heading**. Show or hide the Subcategories as subheading on the
  page.
- **Subcategories Descriptions**. Show or hide the descriptions for
  subcategories.
- **\# Articles in Category**. Show or hide a count of the total number of
  articles in each category.
- **Tags**. Show or hide the tags for the category.

### Blog Layout tab

These parameters control the layout of the page produced by this menu item type.

![Menu Item blog layout tab](../../../en/images/menu-items/articles-category-blog-blog-layout-tab.png)

- **\# Leading Articles**. Number of Articles to show using the full
  width of the main display area. "0" means that no Articles will show
  when using the full width. If an Article has a "Read more..." break,
  only the part of the text before the break (the Intro text) will
  display.
- **Leading Article Class**. You can add any CSS class for your own
  styling ideas. Add a border on top with class boxed.For image position
  use for example image-left, image-right. Add image-alternate for
  alternate ordering of intro images.
- **\# Intro Articles**. Determines the number of Articles to display
  after the leading Article. These Articles will display in the number
  of columns set in the Columns parameter below. If an Article has a
  "Read more..." break, only the text before the break (Intro text) will
  display, followed by a "Read more..." link. The order in which to
  display the articles is determined by the Category Order and Article
  Order parameters below.
- **Article Class**. You can add any CSS class for your own styling
  ideas. Add a border on top with class boxed.For image position use for
  example image-left, image-right. Add image-alternate for alternate
  ordering of intro images.
- **\# Columns**. The number of columns to use in the Intro Articles
  area. This is normally between 1 and 3 (depending on the template you
  are using). If 1 is used, the Intro Articles will display using the
  full width of the display area, just like the Leading Articles.
- **Multi Column Direction**. In multi-column blog layouts, whether to
  order articles Down the columns or Across the columns.
  - Down: Order articles going down the first column and then over to
    the next column, for example:
  - Across: Order articles going across the columns and then back to the
    first column, for example:
- **\# Links**. The number of Links to display in the Links area of the
  page. These links allow a User to link to additional Articles, if
  there are more Articles than can fit on the first page of the Blog
  Layout.
- **Featured Articles**.
  - Show: Display featured articles and non-featured articles.
  - Hide: Display only non-featured articles.
  - Only: Display only featured articles.
- **Linked Intro Image**. If Yes, a click on the intro image shows the
  article.
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
  - Random Order: Articles are displayed in random order.
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
  - Unpublished: Use the article unpublished date.
- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Hide: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Show: Pagination links shown if needed.
  - Auto: Pagination links shown if needed.
- **Pagination Summary**. Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.
