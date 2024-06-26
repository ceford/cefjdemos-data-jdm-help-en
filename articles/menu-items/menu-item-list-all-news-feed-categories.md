<!-- Filename: Help4.x:Menu_Item:_List_All_News_Feed_Categories / Display title: Menu Item: List All News Feed Categories -->

## Description

The **List All News Feed Categories** menu item type is used to show a
list of all RSS News Feed Categories. Categories are shown in a
hierarchical list, as shown below. Depending on the selected options for
this layout, you can click on a category Title to show the News Feeds in
that category.

## How To Access

To create a new List All News Feed Categories menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the News Feeds item to open a list and
    then select the **List All News Feed Categories** item.

To edit an existing List All News Feeds Categories menu item:

- Select its Title in Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/a/a6/Help-4x-Menus-Menu-Item-News-Feed-Categories-screen-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menu Item News Feed Categories screen" />

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Details Tab

#### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Choose a Category**. The Categories that are within this category
  will be displayed. This layout requires a starting top-level category
  selection. To include all article categories, select *Root*.
  Otherwise, select the desired top-level category. All child categories
  of the selected category will show in the layout.
- **Target Window.** Select from the drop-down list.
- **Template Style.** Select from the drop-down list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.
- **Parent Item.** The parent menu item for this menu item. Used to
  determine whether a Menu Item is a top-level item or a submenu item.
  Select 'Menu Item Root' (the default value) if this is a top-level
  Menu Item. Otherwise, select the Menu Item that is this item's parent.
- **Ordering.** You can change the order of an item within a list as
  follows:
  - If the list Filter Options include a Position filter select the
    desired Position. This will limit the list to items that are
    assigned to that Position.
  - Select the Ordering icon <img
    src="https://docs.joomla.org/images/e/ee/Help30-Ordering-colheader-icon.png"
    decoding="async" data-file-width="12" data-file-height="23" width="12"
    height="23" alt="Ordering column header icon" /> in the Table
    heading to make it the active ordering item. The ordering icons in
    each row will change from light grey to dark grey and the pointer
    will change to a drag arrow on hover.
  - Select one of the Ordering icons <img
    src="https://docs.joomla.org/images/8/87/Help30-Ordering-colheader-grab-bar-icon.png"
    decoding="async" data-file-width="10" data-file-height="21" width="10"
    height="21" alt="Ordering drag icon" /> and
    drag it up or down to change the position of that row in the list.
    The items will display in the new order within the Position.
- **Status**. The published status of the item.
- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).
- **Default Page**. If Yes, this menu item is the default or home page
  for the site. There must be exactly one menu item set as the default
  page. You can change the default page in two ways:
  1.  Click on the Home column of the desired menu item in the Menus: Items
      screen.
  2.  Open the menu item for the new default page and change the Default
      Page setting to Yes.
- **Access**. The viewing Access  Level   for this item.
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### Categories Tab

<img
src="https://docs.joomla.org/images/thumb/8/82/Help-4x-Menus-Menu-Item-News-Feeds-Categories-categories-options-parameters-en.png/600px-Help-4x-Menus-Menu-Item-News-Feeds-Categories-categories-options-parameters-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/8/82/Help-4x-Menus-Menu-Item-News-Feeds-Categories-categories-options-parameters-en.png 1.5x"
data-file-width="800" data-file-height="482" width="600" height="362"
alt="Menu Item News Feed Categories categories tab" />

- **Top Level Category Description.** (Use Global/Hide/Show) Whether to
  hide or show the description of the top-level category. Note that this
  description can be overridden for this layout by entering a
  Alternative Description below.
- **Alternative Description.** If you enter some text in this field, it
  will replace the Top Level Category Description, if it has one. If the
  Top Level Description option is set to *Show*, this entered
  description will show instead of the normal category description.
- **Subcategory Levels.** (Use Global/All/1-5) The number of levels of
  subcategories to show in the layout. Select *All* to show all levels
  in the subcategory hierarchy.
- **Empty Categories.** (Use Global/Hide/Show) Whether to hide or show
  the categories that contain no content items or subcategories.
- **Subcategories Descriptions.** (Use Global/Hide/Show) Whether to hide
  or show the category description of subcategories.
- **\# Feeds in Category**. (Use Global/Hide/Show) Show or hide the
  number of News Feeds in a Category.

### Category Tab

<img
src="https://docs.joomla.org/images/7/73/Help-4x-Menus-Menu-Item-News-Feeds-Categories-categories-category-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="406"
width="600" height="406"
alt="Menu Item News Feed Categories Catogory tab" />

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
- **\# Feeds in Category**. (Use Global/Hide/Show) Show or hide the
  number of News Feeds in a Category.

### List Layouts Tab

<img
src="https://docs.joomla.org/images/f/f7/Help-4x-Menus-Menu-Item-News-Feeds-Categories-categories-list-layout-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="384"
width="600" height="384"
alt="Menu Item News Feed Categories list layouts tab" />

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
  heading above a list, like generic heading image shown below.
    If set to *Show*, this heading will show above the list. If set to
    *Hide*, the list will show with no headings.
- **\# Articles**. (Use Global/Hide/Show) Show or hide the number of
  Articles in each News Feed. Other options are available to set this
  value in each individual News Feed.
- **Feed Links**. (Use Global/Hide/Show) Show or hide the feed links
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

<img
src="https://docs.joomla.org/images/e/e5/Help-4x-Menus-Menu-Item-News-Feeds-Categories-feed-display-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="243"
width="600" height="243"
alt="Menu Item News Feed Categories feed display" />

The List All News Feed Categories Layout has the following Feed Display
Options, as shown below. In addition to Yes/No or Hide/Show, these
options allow the "Use Global" setting. This uses the default value from
*News Feed: Options*.
The Feed Display Options are as follows.
- **Feed Image**. (Use Global/Hide/Show) Show or hide the image of News
  Feeds.
- **Feed Description.** (Use Global/Hide/Show) Hide or Show the
  description text of the News Feed.
- **Feed Content**. (Use Global/Hide/Show) Show or hide the content of
  News Feeds.
- **Characters count**. Number of characters to show if Feed Content
  from News Feeds is set to show.

### Common Options

See Menus: New Item for help on fields common to all Menu Item types, including:

- Right Panel
- Link Type
- Page Display
- Metadata
- Associations
- Module Assignment

## Toolbar

At the top of the page you will see the toolbar shown in the Screenshot
above. The functions are:

- **Save.** Saves the menu item and stays in the current screen.
- **Save & Close**. Saves the menu item and closes the current screen.
- **Save & New**. Saves the menu item and keeps the editing screen open
  and ready to create another menu item.
- **Save as Copy**. Saves your changes to a copy of the current menu
  item. Does not affect the current menu item. This toolbar icon is not
  shown if you are creating a new menu item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. Or
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

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
