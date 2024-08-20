<!-- Filename: Help4.x:News_Feed:_Options / Display title: News Feed: Options -->

## Description

News Feed Options configuration allows setting of parameters used
globally for all news feeds.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Components → News Feeds → Feeds** from the
  Administrator menu. Or...
- Select **Components → News Feeds → Categories** from the
  Administrator menu. Then...
  - Click the *Options* button on the Toolbar.

## Screenshot

![News feeds options news feed tab](../../../en/images/news-feeds/news-feeds-options-news-feed-tab.png)

## Form Fields

### News Feed Tab

These settings apply for all News Feeds unless they are changed for a
specific menu item or News Feed

- **Choose a layout** Select a layout to use for articles.
- **Enable Versions** Whether or not to save version history
  for this component. If No, version history will not be saved for
  component items or for this component's categories.
- **Maximum Versions** The maximum number of versions to store for an
  item. If an item is saved and the maximum number of versions has been
  reached, the oldest version will be deleted automatically. If set to
  0, then versions will never be deleted automatically. Also, specific
  versions may be flagged as "Keep Forever" and will not be deleted
  automatically. Note that versions may be deleted manually using the
  Delete button in the Version History
  screen.
- **Feed Image** Show or hide the feed image.
- **Feed Description** Show or hide the feed description.
- **Feed Content** Show or hide the feed content.
- **Characters Count** The maximum number of characters to display for
  each feed. This is a way to limit the size of the feed.
- **Feed Display Order** The order in which to show the feeds.
- **First Image Float** Where to display the image on the page.
- **Second Image Float** Where to display the image on the page.
- **Show Tags** Show or hide the feed's tags.

### Category Tab

![News feeds options category tab](../../../en/images/news-feeds/news-feeds-options-category-tab.png)

- **Choose a layout** (Blog/List/user defined). This lets you select
  the default layout to show when you click on a Category link. If you
  create an alternative layout for a category layout, you may select
  that as the default.
- **Category Title** (Show/Hide). Show or hide the title of the
  category.
- **Category Description** (Show/Hide). Show or hide the description
  for the category.
- **Category Image** (Show/Hide). Show or hide the category image.
- **Subcategory Levels** (None/All/1-5). Categories in Joomla can be
  created in a hierarchy. This lets you control how many levels of
  subcategories to show when showing a category view.
- **Empty Categories** (Show/Hide). Show or hide categories that don't
  contain any items or subcategories.
- **Subcategories Descriptions** (Hide/Show). Show or hide the
  descriptions for subcategories that are shown.
- **\# Feeds in Category** (Show/Hide). Show or hide the number of news
  feeds in category.
- **Show Tags** (Show/Hide). Show or hide the tags for a single
  category.

### Categories Tab

![News feeds options categories tab](../../../en/images/news-feeds/news-feeds-options-categories-tab.png)

- **Top Level Category Description** (Show/Hide). Show or hide the
  description of the top-level category.
- **Subcategory Levels** (All/1-5). How many levels in the hierarchy to
  show.
- **Empty Categories** (Show/Hide). Show or hide categories that
  contain no items and no subcategories.
- **Subcategories Descriptions** (Hide/Show). Show or hide the
  description of each subcategory.
- **\# Feeds in Category** (Show/Hide). Show or hide the number of news
  feeds in category.

### List Layouts Tab

![News feeds options list layouts tab](../../../en/images/news-feeds/news-feeds-options-list-layouts-tab.png)

- **Filter Field** The Filter Field creates a text field where a user
  can enter a field to be used to filter the articles shown in the list.
    - *Hide:* Don't show a filter field.
    - *Title:* Filter on article title.
    - *Author:* Filter on the author's name.
    - *Hits:* Filter on the number of article hits.
- **Display Select** (Show/Hide) Whether to show or hide the Display \#
  control that allows the user to select the number of items to show in
  the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings** (Hide/Show) Table Headings show a heading above
  the article list.
    If set to *Show*, this heading will show about the list. Otherwise the
    list will show with no headings.
- **\# Articles** (Show/Hide). Whether to show or hide the number or
  articles in each feed.
- **Feed Links** (Show/Hide). Whether to show or hide the feed links
  URL.
- **Pagination** Hide or Show Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    - *Use Global:* Use the default value from the component options screen.
    - *Auto:* Pagination links shown if needed.
    - *Show:* Pagination links shown if needed.
    - *Hide:* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Results** Hide or Show the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.

### Integration Tab

![News feeds options integration tab](../../../en/images/news-feeds/news-feeds-options-integration-tab.png)

- **Remove IDs from URLs** Whether or not to show the database id of a 
  newsfeed in a link.

## Quick Tips

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here. When you set up menu items and create news feed
  menu items, you will be able to accept the default values for most
  options.
- All values set here can be overridden at the menu item, category, or
  news feed level.
