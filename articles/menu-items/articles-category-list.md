<!-- Filename: Help4.x:Menu_Item:_Category_List / Display title: Category List -->

## Description

The Category List menu item type is used to show articles belonging to a
specific Category in a list layout.

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

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Category List** item.

To edit a Menu Item:

- select a **Title** from the list

## Screenshot

![Menu Item Category List](../../../en/images/menu-items/articles-category-list-details-tab.png)

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

![Menus Item Category List category tab](../../../en/images/menu-items/articles-category-list-category-tab.png)

- **Category Title**. Show or hide the title of the category.
- **Category Description**. Show or hide the description for the category.
- **Category Image**. Show or hide the category image.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
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

### List Layouts tab

These parameters control the layout of the page produced by this menu item type.

![Menu Item type Category List - list layouts tab](../../../en/images/menu-items/articles-category-list-list-layouts-tab.png)

- **Display Select**. Show or hide the Display \# control that allows the user
  to select the number of articles to show.
- **Filter Field**. Show or hide a text field in the Frontend where a user can
  filter the articles.Options in the Backend menu item edit.
  - Hide: Don't show a filter field.
  - Title: Filter on article title.
  - Author: Filter on the author's name.
  - Hits: Filter on the number of article hits.
  - Tags: Filter on the article tags.
  - Month (published): Filter on the month of published articles.
- **Table Headings**. Show or hide a heading in the article list in the
  Frontend.
- **Date**. Show a date in the list.
  - Hide: Don't show any date.
  - Created: Show the created date.
  - Modified: Show the date of the last modification.
  - Published: Show the start publishing date.
- **Date Format**. Optional format string to control the format of the
  date.
- **Hits**. Show or hide the number of hits for articles.
- **Author**. Show or hide the name of the author.
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
- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Hide: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Show: Pagination links shown if needed.
  - Auto: Pagination links shown if needed.
- **Pagination Summary**. Show or hide the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.
- **\# Articles to List**. Number of articles shown in the list.
- **Featured Articles**.
  - Show: Display featured articles and non-featured articles.
  - Hide: Display only non-featured articles.
  - Only: Display only featured articles.

### Options tab

These parameters control the layout of each article in the page produced by 
this menu item type.

![Menu Item type Category List - options tab](../../../en/images/menu-items-common/articles-article-options.png)

- **Choose a Layout**. Select from the dropdown list.
- **Title**. Show or hide the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Intro Text**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- **Category**. Show or hide the Article's Category Title.
- **Link Category**. Show the title as a link to that Category.Note: You
  can set this to be either a blog or list layout with the Choose a Layout
  option in the Category Tab.
- **Parent Category**. Show or hide the Article's Parent Category Title.
- **Link Parent Category**. Show the title as a link to that
  Category. Note: You can set this to be either a blog or list layout
  with the Choose a Layout
  option in the Category Tab.
- **Associations**. Show or hide the associated flags or Language Code.
  Multilingual only.
- **Author**. Show or hide the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  Contact.
  Also, a link will not show if there is an Author Alias
  value for the article.
- **Create Date**. Show or hide the Article's create date.
- **Modify Date**. Show or hide the Article's modify date.
- **Publish Date**. Show or hide the Article's start publishing date.
- **Navigation**. Show or hide a navigation link *Prev* or *Next* when you drill
  down to the article.
- **"Read More" Link**. Show or hide the Read More link to link from the part of
  the article before the Read More break to the rest of the Article.
- **Read More with Title**.
  - Show: The article title is part of the Read More link. The link will
    be in the format "Read More: \[article title\]".
  - Hide: The link will be "Read more".
- **Hits**. Show or hide the number of times the article has been displayed by a
  user.
- **Unauthorised Links**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

## Quick Tips

- The Category List layout is a convenient way to list a compact
  directory of articles in a category that can include filtering and
  searching.
