<!-- Filename: Help4.x:Menu_Item:_Category_List / Display title: Menu Item: Category List -->

## Description

The Category List menu item type is used to show articles belonging to a
specific Category in a list layout.

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

<img
src="https://docs.joomla.org/images/thumb/4/42/Help-4x-Menus-Item-Articles-Category-List-screen-en.png/800px-Help-4x-Menus-Item-Articles-Category-List-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/4/42/Help-4x-Menus-Item-Articles-Category-List-screen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-List-screen-en.png 1.5x, https://docs.joomla.org/images/thumb/4/42/Help-4x-Menus-Item-Articles-Category-List-screen-en.png/1600px-Help-4x-Menus-Item-Articles-Category-List-screen-en.png 2x"
data-file-width="2880" data-file-height="1407" width="800" height="391"
alt="Menu Item Category List screen" />

## Form Fields

- **Title**. The title that will display for this menu item.
- **Alias**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Details

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

### Category

The Options control the way that category information is shown in the
menu item.
Options include "Use Global". If this is selected, the setting from the
Articles: Options
will be used.

<img
src="https://docs.joomla.org/images/thumb/7/72/Help-4x-Menus-Item-Articles-Category-List-category-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-List-category-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/72/Help-4x-Menus-Item-Articles-Category-List-category-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-List-category-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/7/72/Help-4x-Menus-Item-Articles-Category-List-category-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-List-category-subscreen-en.png 2x"
data-file-width="2878" data-file-height="1337" width="600" height="279"
alt="Menus Item Category List category tab" />

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

### List Layouts

List Layout Options control the appearance of the menu item.

<img
src="https://docs.joomla.org/images/thumb/a/a4/Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/a/a4/Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/a/a4/Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-en.png 2x"
data-file-width="2878" data-file-height="1326" width="600" height="276"
alt="Menus Item Category List list layouts tab" />

- **Display Select**. Show the Display \# control that allows the user
  to select the number of articles to show.
- **Filter Field**. Show a text field in the Frontend where a user can
  filter the articles.Options in the Backend menu item edit.
  - Hide: Don't show a filter field.
  - Title: Filter on article title.
  - Author: Filter on the author's name.
  - Hits: Filter on the number of article hits.
  - Tags: Filter on the article tags.
  - Month (published): Filter on the month of published articles.
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
- **Pagination Summary**. Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.
- **\# Articles to List**. Number of articles shown in the list.
- **Featured Articles**.
  - Show: Display featured articles and non-featured articles.
  - Hide: Display only non-featured articles.
  - Only: Display only featured articles.

### Options

The Options determine how the articles will show in the list menu item.

<img
src="https://docs.joomla.org/images/thumb/0/0c/Help-4x-Menus-Item-Articles-Category-List-options-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-List-options-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0c/Help-4x-Menus-Item-Articles-Category-List-options-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-List-options-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/0/0c/Help-4x-Menus-Item-Articles-Category-List-options-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-List-options-subscreen-en.png 2x"
data-file-width="2878" data-file-height="1344" width="600" height="280"
alt="Menus Item Category List options tab" />

- **Choose a Layout**. Select from the dropdown list.
- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Intro Text**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
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
- **Unauthorised Links**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

### Integration

The Options determine whether a news feed will be available for the page
and what information it will show.

<img
src="https://docs.joomla.org/images/thumb/d/d6/Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-en.png/600px-Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/d6/Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-en.png/900px-Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/d/d6/Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-en.png/1200px-Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-en.png 2x"
data-file-width="2878" data-file-height="710" width="600" height="148"
alt="Menus Item Category List integration tab" />

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

## Quick Tips

- The Category List layout is a convenient way to list a compact
  directory of articles in a category that can include filtering and
  searching.
- To create a new Category see Articles: Edit Category.
- To create a new menu see Menus.
