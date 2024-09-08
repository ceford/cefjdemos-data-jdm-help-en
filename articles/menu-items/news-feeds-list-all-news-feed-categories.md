<!-- Filename: Help4.x:Menu_Item:_List_All_News_Feed_Categories / Display title: List All News Feed Categories -->

## Description

The **List All Categories in a News Feed Category Tree** menu item type is used 
to show a list of all RSS News Feed Categories. Categories are shown in a
hierarchical list. Depending on the selected options for this layout, a category
Title may be selected to show the News Feeds in that category.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [The Category Tab](jdocmanual?article=help/menu-items-common/menu-item-category).
* [The List Layouts Tab](jdocmanual?article=help/menu-items-common/menu-item-list-layouts).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new List All Categories in a News Feed Category Tree menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the News Feeds item to open a list and
    then select the **List All News Feed Categories** item.

To edit an existing List All News Feeds Categories menu item:

- Select its Title in Menus: Items list.

## Screenshot

![Menu Item list all News Feed Categories details tab](../../../en/images/menu-items/news-feeds-list-all-categories-details-tab.png)

## Form Fields

### Categories Tab

![Menu Item list all News Feed Categories categories tab](../../../en/images/menu-items/news-feeds-list-all-categories-tree-categories-tab.png)

- **Top Level Category Description** Show or hide the description of the 
  top-level category. Note that this description can be overridden for this 
  layout by entering an *Alternative Description*.
- **Alternative Description** If you enter some text in this field, it
  will replace the Top Level Category Description, if it has one. If the
  Top Level Description option is set to *Show*, this description will show
  instead of the normal category description.
- **Subcategory Levels** The number of levels of subcategories to show in the 
  layout. Select *All* to show all levels in the subcategory hierarchy.
- **Empty Categories** Show or hide the categories that contain no content 
  items or subcategories.
- **Subcategories Descriptions** Show or hide the category description of 
  subcategories.
- **\# Feeds in Category** Show or hide the number of News Feeds in a Category.

### Feed Display Options Tab

![Menu Item list all News Feed Categories categories tab](../../../en/images/menu-items/news-feeds-list-all-categories-tree-feed-display-options-tab.png)

- **Feed Image** Show or hide the image of News Feeds.
- **Feed Description** Show or hide the descriptions of the News Feeds.
- **Feed Content** Show or hide the content of News Feeds.
- **Characters count** Number of characters to show if the Feed Content
  from News Feeds is set to show.

## Tips

- Categories can be *nested* into levels, similar to folders on a disk
  drive. In theory there is no absolute limit on the number of levels
  you can have. However, as a practical matter it is recommended to keep
  the levels to a minimum. The Show All Categories layout may not work
  correctly if the number of levels shown is greater than five.
- If you set up category titles as linkable, the user can navigate to
  the category. If there is a pre-existing menu item for this category
  (for example, a Category List menu item), then that menu item/s options will
  control the display of that page. Otherwise, the options set for the current
  Show All Categories menu item will control the page display.
- You can set the option to link to a list in two places.
  - In *News Feed: Options* you can set the default value for all categories.
  - In *Category: Edit* for a Newsfeeds Category you can set a value for a
    specific category. If this is set, it overrides the default value.
