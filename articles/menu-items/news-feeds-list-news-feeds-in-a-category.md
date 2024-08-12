<!-- Filename: Help4.x:Menu_Item:_List_News_Feeds_in_a_Category / Display title: List News Feeds in a Category -->

## Description

The **List News Feeds in a Category** menu item type is used to show a
list of all RSS News Feeds in a Category. Depending on the selected
options for this layout, you can include subcategories of a News Feed
category.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new **List News Feeds in a Category** menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the **New** button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the News Feeds item to open a list and
    then select the **List News Feeds in a Category** item.

To edit an existing List News Feeds in a Category menu item:

- Select its Title in the Menus: Items list.

## Screenshot

![Menu Item List News Feeds in a Category details tab](../../../en/images/menu-items/news-feeds-list-newsfeeds-in-a-category-details-tab.png)

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Category Tab

![Menu Item List News Feeds in a Category details tab](../../../en/images/menu-items/news-feeds-list-newsfeeds-in-a-category-category-tab.png)

- **Category Title.** (Use Global/Hide/Show) If Show, the Category Title
  will show as a subheading on the page. The subheading is usually
  displayed inside the "H2" tag.
- **Category Description**. (Use Global/Hide/Show) Show or hide the
  description of the selected Category.
- **Category Image.** (Use Global/Hide/Show) Whether to hide or show the
  category image.
- **Subcategory Levels.** (Use Global/All/1-5) The number of levels of
  subcategories to show in the layout. Select *All* to show all levels
  in the subcategory hierarchy.
- **Empty Categories.** (Use Global/Hide/Show) Whether to hide or show
  the categories that contain no content items or subcategories.
- **Subcategories Descriptions.** (Use Global/Hide/Show) Whether to hide
  or show the category description of subcategories.
- **Feeds in Category.** (Use Global/Hide/Show) Show or hide the number
  of News Feeds in a Category.

### List Layout Tab

![Menu Item List News Feeds in a Category details tab](../../../en/images/menu-items/news-feeds-list-newfeeds-in-a-category-list-layouts-tab.png)

- **Filter Field:** (Use Global/Hide/Show) Whether to show a Filter
  field for the list. Select Hide to hide the filer field
- **Display Select.** (Use Global/Hide/Show) Whether to hide or show the
  Display \# control that allows the user to select the number of items
  to show in the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings.** (Use Global/Hide/Show) Table Headings show a
  heading above a list.
    If set to *Show*, this heading will show above the list. If set to
    *Hide*, the list will show with no headings.
- **\# Articles.** (Use Global/Hide/Show) Show or hide the number of
  Articles in each News Feed. Other options are available to set this
  value in each individual News Feed.
- **Feed Links.** (Use Global/Hide/Show) Show or hide the feed links
  URLs.
- **Pagination.** Hide or Show Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    The following options are available.
    - *Use Global:* Use the default value from the component options screen.
    - *Auto:* Pagination links shown if needed.
    - *Show:* Pagination links shown if needed.
    - *Hide:* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Results.** Hide or Show the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.

### Feed Display Options Tab

![Menu Item List News Feeds in a Category details tab](../../../en/images/menu-items/news-feeds-list-newfeeds-in-a-category-feed-display-options-tab.png)

- **Feed Image**. (Use Global/Hide/Show) Show or hide the image of News
  Feeds.
- **Feed Description.** (Use Global/Hide/Show) Hide or Show the
  description text of the News Feed.
- **Feed Content**. (Use Global/Hide/Show) Show or hide the content of
  News Feeds.
- **Characters count.** Number of characters to show if Feed Content
  from News Feeds is set to show.
- **Feed display order.** (Use Global/Most recent first/Oldest first)
  Select the feed display order, most recent first, oldest first, or
  Global, the setting in News Feeds Options.

## Quick Tips

- Categories can be "nested" into levels, similar to folders on a disk
  drive. In theory there is no absolute limit on the number of levels
  you can have. However, as a practical matter it is recommended to keep
  the levels to a minimum. The Show All Categories layout may not work
  correctly if the number of levels shown is greater than five.
- If you set up category titles as linkable, the user can drill down on
  the category. If there is a pre-existing menu item for this category
  (for example, a Category List menu item), then that menu item will
  show in the drill down and the options set for that menu item will
  control the page display. Otherwise, the options set for the current
  Show All Categories menu item will control the page display.
- You can set the option to drill down to a list in two places.
  - In *News Feed: Options*
    you can set the default value for all categories.
  - In Category: Edit A Newsfeeds Category you can set a value for a
    specific category. If this is set, it overrides the default value.
