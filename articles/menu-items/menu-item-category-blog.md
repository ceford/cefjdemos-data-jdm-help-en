<!-- Filename: Help4.x:Menu_Item:_Category_Blog / Display title: Menu Item: Category Blog -->

## Description

A Category Blog menu item typically has one or two leading article
tasters occupying the full width of the content area followed by more
articles tasters in one, two or three columns and additional links to
more Articles in the same category.

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

<img
src="https://docs.joomla.org/images/thumb/b/bc/Help-4x-Menus-Item-Articles-Category-Blog-screen-en.png/800px-Help-4x-Menus-Item-Articles-Category-Blog-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/bc/Help-4x-Menus-Item-Articles-Category-Blog-screen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-screen-en.png 1.5x, https://docs.joomla.org/images/thumb/b/bc/Help-4x-Menus-Item-Articles-Category-Blog-screen-en.png/1600px-Help-4x-Menus-Item-Articles-Category-Blog-screen-en.png 2x"
data-file-width="2880" data-file-height="1404" width="800" height="390"
alt="Menu Item type Category Blog" />

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

The Options control the way that category information is shown in the
menu item.
Options include "Use Global". If this is selected, the setting from the
Articles: Options
will be used.

<img
src="https://docs.joomla.org/images/thumb/1/17/Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/17/Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/1/17/Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-en.png 2x"
data-file-width="2880" data-file-height="1340" width="600" height="279"
alt="Menu Item category tab" />

- **Category Title**. Show the title of the category.
- **Category Description**. Show the description for the category.
- **Category Image**. Show the category image.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
- **Empty Categories**. Show categories that don't contain any articles
  or subcategories.
- **No Articles Message**. Show a message "There are no articles in this
  category".
- **Subcategories Heading**. Show the Subcategories as subheading on the
  page.
- **Subcategories Descriptions**. Show the descriptions for
  subcategories.
- **\# Articles in Category**. Show a count of the total number of
  articles in each category.
- **Tags**. Show the tags for the category.

### Blog Layout tab

The Options control the appearance of the blog menu item.

<img
src="https://docs.joomla.org/images/thumb/a/ab/Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/ab/Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/a/ab/Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-en.png 2x"
data-file-width="2880" data-file-height="1340" width="600" height="279"
alt="Menu Item blog layout tab" />

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
-
  - Across: Order articles going across the columns and then back to the
    first column, for example:
-
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

### Options

The Options determine how the articles will show in the blog menu
item.
Options include "Use Article Settings". If this is selected, the setting
from Articles: Edit will be used.

<img
src="https://docs.joomla.org/images/thumb/e/e5/Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/e5/Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/e/e5/Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-en.png 2x"
data-file-width="2880" data-file-height="1340" width="600" height="279"
alt="Menu Category Blog options tab" />

- **Choose a Layout**. Select from the dropdown list.
- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Intro Text**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- **Position of Article Info**.
  - Above: Puts the article information block above the text.
  - Below: Puts the article information block below the text.
  - Split: Splits the article information block into 2 separate blocks.
    One block is above and the other is below the text.
- **Article Info Title**. Displays 'Details' on top of the article
  information block.
- **Category**. Show the Article's Category Title.
- **Link Category**. Show the title as a link to that Category.Note: You
  can set this to be either a blog or list layout with the Choose a Layout
  option in the Category Tab.
- **Parent Category**. Show the Article's Parent Category Title.
- **Link Parent Category**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the Choose a Layout
  option in the Category Tab.
- **Associations**. Show the associated flags or Language Code.
  Multilingual only.
- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  Contact.
  Also, a link will not show if there is an Author Alias
  value for the article.
- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.
- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **"Read More" Link**. Show the Read More link to link from the part of
  the article before the Read More break to the rest of the Article.
- **Read More with Title**.
  - Show: The article title is part of the Read More link. The link will
    be in the format "Read More: \[article title\]".
  - Hide: The link will be "Read more".
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Tags**. Show the tags for each article.
- **Unauthorised Links**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

### Integration tab

The Options determine whether a news feed will be available for the page
and what information it will show.

<img
src="https://docs.joomla.org/images/thumb/7/78/Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/78/Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/7/78/Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-en.png 2x"
data-file-width="2880" data-file-height="709" width="600" height="148"
alt="Menu Category Blog integration tab" />

- **RSS Feed Link**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- **Include in Feed**.
  - Intro Text: Only the article's intro text will show in the feed.
  - Full Text: The entire text of the article will show in the feed.

### Common Options

See Menus: New Item
for help on fields common to all Menu Item types, including:

- Right Panel
- Link Type
- Page Display
- Metadata
- Associations
- Module Assignment

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Save**. Saves the menu item and stays in the current screen.
- **Save & Close**. Saves the menu item and closes the current screen.
  - **Save & New**. Saves the menu item and keeps the editing screen
    open and ready to create another menu item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.
