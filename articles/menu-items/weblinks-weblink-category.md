<!-- Filename: Help4.x:Menus_Menu_Item_Weblink_Category / Display title: List Web Links in a Category -->

## Description

Used to show a list of Web Links in a Category. Categories are shown in
a hierarchical list, parent with child (sub) categories. Depending on
the selected layout options, click on a category Title to show the Web
Links in that category or sub categories.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new **List Web Links in a Category** Menu Item:

- Select **Menus → \[name of the menu\]** from the drop-down menu on
  the back-end of your Joomla! installation (for example,
  **Menus → Main Menu**).
- Click the New Toolbar button to create a new menu item.
- Click the Menu Item Type Select button and then click
  the List Web Links in a Category Menu Item link under Weblinks link.

To edit an existing List Web Links in a Category Menu Item, click its
Title in Menu Manager: Menu Items.

## Screenshot

![Menu item type List Web Links in a Category](../../../en/images/menu-items/weblinks-list-web-links-in-a-category-details-tab.png)

## Form Fields

- **Title** The title that will display for this menu item.

### Details Tab

- **Menu Item Type** The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Choose a Category** The Categories that are within this category
  will be displayed.
- **Menu** Shows which menu the link will appear in.

### Category tab

Category Options control the appearance of the screen when you click on
a category link. The following options are available.

![Menu item type List Web Links in a Category](../../../en/images/menu-items/weblinks-list-web-links-in-a-category-category-tab.png)

- **Category Title** (Use Global/Hide/Show) If Show, the Category Title
  will show as a subheading on the page. The subheading is usually
  displayed inside the "H2" tag.
- **Category Description** (Use Global/Hide/Show) Show or hide the
  description of the selected Category.
- **Category Image** (Use Global/Hide/Show) Whether to hide or show the
  category image.
- **Subcategory Levels** (Use Global/All/1-5) The number of levels of
  subcategories to show in the layout. Select *All* to show all levels
  in the subcategory hierarchy.
- **Empty Categories** (Use Global/Hide/Show) Whether to hide or show
  the categories that contain no content items or subcategories.
- **Subcategories Descriptions** (Use Global/Hide/Show) Whether to hide
  or show the category description of subcategories.
- **\# Web links**. (Use Global/Hide/Show) Show or hide the number of
  'Web Links' in each category.

### List Layouts tab

The List Layout options control the appearance of the category
drill-down page when that is presented as a Category List. The following
options are available:

![Menu item type List Web Links in a Category](../../../en/images/menu-items/weblinks-list-web-links-in-a-category-list-layouts-tab.png)

- **Filter Field** (Use Global/Hide/Show) Whether to show a Filter
  field for the list. Select Hide to hide the filer field
- **Display Select** (Use Global/Hide/Show) Whether to hide or show the
  Display \# control that allows the user to select the number of items
  to show in the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings** (Use Global/Hide/Show) Table Headings show a
  heading above a list.
    If set to *Show*, this heading will show above the list. If set to
    *Hide*, the list will show with no headings.
- **Links Description**. (Use Global/Hide/Show) Show or hide the
  description of the list of links.
- **Hits**. (Use Global/Hide/Show) Show or hide the number of hits
  (refers to \# of clicks) to a link in the list of links.
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

## Tips

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
