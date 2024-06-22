<!-- Filename: Help4.x:Articles:_Options / Display title: Articles: Options -->

## Description

Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global'
is selected for an option in an Articles menu item.

For example, to show the 'Create Date' for an article in your Articles
menu items, then set that option to 'Show' here and it will be the
default value.

You do not need to set any of these options. Your Joomla site will work
with the default settings.

## How To Access

Select the **Options** button in the Toolbar of any *Articles* list page.

## Screenshot

![Articles options screenshot](../../../en/images/articles/articles-options-articles-tab.png "Articles options")

## Form Fields

### Articles tab

Options used in articles and the menu items Blog, List, Featured Articles,
List All Categories and Single Article.

- **Choose a Layout**. Select the default value for Single Article menu
  items.
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
  - **Link Category**. Show the title as a link to that Category.Note:
    You can set this to be either a blog or list layout with the Choose a Layout
    option in the Category Tab.
- **Parent Category**. Show the Article's Parent Category Title.
  - **Link Parent Category**. Show the title as a link to that
    Category.Note: You can set this to be either a blog or list layout
    with the Choose a Layout option in the Category Tab.
- **Associations**. Show the associated flags or Language Code.
  Multilingual only.
  - **Use Image Flags**. Display language choice as image flags is Associations
    is set to *Show*.
- **Author**. Show the author of the Article.
  - **Link to Author's Contact Page**. Show it as a link to a Contact
    layout for that author.Note: The author must be set up as a
    Contact.
    Also, a link will not show if there is an Author Alias value for the article.
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
- **Read More Limit (characters)**. The maximum number of characters
  from the title to include.Note: This can prevent the Read More text to
  become excessively long if the article has a very long title.
- **Tags**. Show the tags for each article.
- **Record Hits**. Record the number of times the article has been
  viewed.
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Unauthorised Links**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Positioning of the Links**.
  - Above: Links are shown above the content.
  - Below: Links are shown below the content.

### Editing Layout tab

Options of the article editing page.

![Articles options editing layout tab](../../../en/images/articles/articles-options-editing-layout-tab.png "Articles options editing layout")

- **Allow Captcha on submit**. Select the captcha plugin
  that will be used in the article submit form. If 'Use Global' is
  selected, make sure a captcha plugin is selected in Global Configuration.
- **Publishing Options**. Hide the Publishing Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Article Options**. Hide the Article Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Edit Screen Options**. Hide the Configure Edit Screen tab
  when editing Articles.
- **Article Permissions**. Hide the Permissions tab
  when editing Articles.
- **Multilingual Associations**. Hide the Associations tab
  when editing Articles.
- **Enable Versions**. Save version history for Articles and Categories.
- **Maximum Versions**. The maximum number of versions to store for an
  Article or Category. If an Article or Category is saved and the
  maximum number of versions has been reached, the oldest version will
  be deleted automatically. If set to "0", then versions will never be
  deleted automatically.
- **Frontend Images and Links**. Hide the Images and Links tab in the
  Frontend article editor screen.
- **Administrator Images and Links**. Hide the Images and Links tab
  in the Backend when editing Articles.
- **URL A Target Window**. Sets the default value for the target for the
  first Link in the article. Choices are:
  - Open in parent window: Opens the in the main browser window,
    replacing the current Joomla article.
  - Open in new window: Opens the link in a new browser window.
  - Open in popup: Opens the link in a popup browser window (without
    full navigation controls).
  - Modal: Opens the link in a modal popup window.
- **URL B Target Window**. Sets the default value for the target for the
  second Link in the article. Same options as URL A.
- **URL C Target Window**. Sets the default value for the target for the
  third Link in the article. Same options as URL A.
- **Intro Image Class**. Sets the class attribute for an Intro Image
  selected in the Intro Image field.
- **Full Text Image Class**. Sets the class attribute for an Full
  Article Image selected in the Full Article Image field.

### Category tab

Options control how a Category and its articles will show. They are used
in categories and the menu items Blog, List and List All Categories.

![Articles options category tab](../../../en/images/articles/articles-options-category-tab.png "Articles options category")

- **Choose a Layout**. Select the default layout to show when you click
  on a Category link.
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

### Categories tab

Options control the display of the menu item List All Categories.

![Articles options categories tab](../../../en/images/articles/articles-options-categories-tab.png "Articles options categories")

- **Top Level Category Description**. Show the description for the
  top-level category.
- **Subcategory Levels**. Control how many levels of subcategories to
  show.
- **Empty Categories**. Show categories that don't contain any articles
  or subcategories.
- **Subcategories Descriptions**. Show the description for
  subcategories.
- **\# Articles in Category**. Show a count of the total number of
  articles in each category.

### Blog/Featured Layouts tab

Options control the layout of the menu items Blog, Featured Articles and List
All Categories.

![Articles options blog and featured layout tab](../../../en/images/articles/articles-options-blog-layouts-tab.png "Articles options blog and featured layout")

- **# Leading Articles**. Number of Articles to show using the full
  width of the main display area. "0" means that no Articles will show
  when using the full width. If an Article has a "Read more..." break,
  only the part of the text before the break (the Intro text) will
  display.
- **Leading Article Class**. You can add any CSS class for your own
  styling ideas. Add a border on top with class boxed.For image position
  use for example image-left, image-right. Add image-alternate for
  alternate ordering of intro images.
- **# Intro Articles**. Determines the number of Articles to display
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
- **# Columns**. The number of columns to use in the Intro Articles
  area. This is normally between 1 and 3 (depending on the template you
  are using). If 1 is used, the Intro Articles will display using the
  full width of the display area, just like the Leading Articles.
- **Multi Column Direction**. In multi-column blog layouts, whether to
  order articles Down the columns or Across the columns.
  - Down: Order articles going down the first column and then over to
    the next column.
  - Across: Order articles going across the columns and then back to the
    first column.
- **# Links**. The number of Links to display in the Links area of the
  page. These links allow a User to link to additional Articles, if
  there are more Articles than can fit on the first page of the Blog
  Layout.
- **Include Subcategories**.
  - None: Only articles from the current category will show.
  - All: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
- **Linked Intro Image**. If Yes, a click on the intro image shows the
  article.

### List Layouts tab

Options control the layout of the menu items List and List All Categories.

![Articles options list layouts tab](../../../en/images/articles/articles-options-list-layouts-tab.png "Articles options list layouts")

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
- **Hits**. Show the number of hits for articles.
- **Author**. Show the name of the author.
- **\# Articles to List**. Number of articles shown in the list.

### Shared tab

Options shared by the menu items Blog, List and Featured Articles.

![Articles options shared tab](../../../en/images/articles/articles-options-shared-tab.png "Articles shared")

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
  - Ordering: Articles are ordered according to the Order column entered
    in Articles.
  - Ordering Reverse: Articles are ordered reverse to the according of
    the Order column entered in Articles.
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
- **Featured Articles**.
  - Show: Display featured articles and non-featured articles.
  - Hide: Display only non-featured articles.
  - Only: Display only featured articles.

### Integration tab

Options control how Articles integrate News Feeds, Routing, Custom
Fields and Workflow.

![Articles options integration tab](../../../en/images/articles/articles-options-integration-tab.png "Articles options integration")

#### News Feeds panel

- **RSS Feed Link**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- **Include in Feed**.
  - Intro Text: Only the article's intro text will show in the feed.
  - Full Text: The entire text of the article will show in the feed.
- **"Read More" Link**. Show a "Read more" link in the feed.

#### Routing panel

- **Remove IDs from URLs**. Remove the database id of articles in a
  link.

#### Custom Fields panel

- **Edit Custom Fields**. Enable the creation of custom fields.

#### Workflow panel

- **Enable Workflow**. Use customised workflows to manage articles.

### Permissions tab

This section lets you set up the default Access Control List
permissions for all articles in all categories.

![Articles options permissions tab](../../../en/images/articles/articles-options-permissions-tab.png "Articles options permissions")

To change the permissions for articles and categories, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Configure ACL & Options**. Users can edit the options and
      permissions.
    - **Configure Options Only**. Users can edit the options exept the
      permissions.
    - **Access Administration Interface**. Users can access user
      administration interface.
    - **Create**. Users can create articles and categories.
    - **Delete**. Users can delete articles and categories.
    - **Edit**. Users can edit articles and categories.
    - **Edit State**. User can change the published state and related
      information.
    - **Edit Own**. Users can edit own created articles and categories.
    - **Edit Custom Field Value**. Users can edit any value of custom
      fields submitted in articles and categories.
    - **Manage Workflows**. Users can manage workflows.
    - **Execute Transition**. Users can execute transitions.
3.  Select the desired permission for the action you wish to change.
    - **Inherited**. Inherited for users in this Group from the Global Configuration
      permissions.
    - **Allowed**. Allowed for users in this Group.Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Denied**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Save**. Saves the articles options and stays in the current screen.
- **Save & Close**. Saves the articles options and closes the current
  screen.
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Toggle Inline Help**. Show help text below some options.
- **Help**. Opens this help screen.

## Quick Tips

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here. When you set up menu items and create articles,
  you will be able to accept the default values for most options.
- All values set here can be overridden at the menu item, category, or
  article level.
