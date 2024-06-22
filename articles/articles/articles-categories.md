<!-- Filename: Help4.x:Articles:_Categories / Display title: Articles: Categories -->

## Description

The Articles Categories list is used to find, add, and edit articles
categories.

Categories are are used to organise Articles for ease of management and
display. They can be organised into tree-like structures like file
systems. All Articles must be assigned either to a parent Category or a
child Category.

## How to Access

There are two routes to the Categories list page:
* From the **Home Dashboard → Site panel** Select **Article Categories**
* From Administrator menu select **Content → Categories**

## Screenshot

![Articles: Categories list](../../../en/images/articles/articles-categories-list.png "Articles: Categories list")

## Column Headers

- **Checkbox**. Check this box to select categories. To select all
  categories, check the box in the column heading. After boxes are
  checked the toolbar button 'Actions' get active.
- **Ordering**. You can change the order of an category within a list as
  follows:
  - Select the Ordering icon <i class="fa-solid fa-sort"></i> in the first
    column heading to make it active.
  - Select one of the vertical ellipsis icons <span class="icon-ellipsis-v"></span>
    and drag it up or down to change the position of that row in the list.
  - In the Filter Options you may limit the list to categories that are
    assigned for example to a Language.
- **Status**. Status of category. Hover icon for informations.
- **Title**. The title of the category. Edit the category by clicking on
  the Title.
- **Icons**. Counts of number of Published, Unpublished, Archived and
  Trashed Articles in each Category. Click on a number to get a list of
  the categories.
- **Access**. The viewing Access level  for this category.
- **Associations**. Shows the associated categories. Click on the
  Language Code to open the category. Multilingual only!
- **Language**. Categories language, default is 'All'.
- **ID**. A unique identification number for this category, you cannot
  change this number.

## List Filters

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Filter Options**. Click to display the additional filters.
- **Clear**. Click to clear the Filter field and restore the list to its
  unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of categories in a list.
  Select from the dropdown list to change the number displayed.The
  default for a site is '20' but this may be changed in the Global
  Configuration.

### Filter Options

Near the top of the page you will see the filter bar shown in the
Screenshot above.

- **Select Status**. Select from Trashed / Unpublished / Published /
  Archived / All.
- **Select Access**. Select from the list of available viewing access
  levels.
- **Select Language**. Select from the list of available languages.
- **Select Tag**. Select from the list of available tags.
- **Select Max Levels**. Select from the list of available levels.

### Pagination

**Page Controls**. When the number of categories is more than one page,
you will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **New**. Opens the editing screen to create a new category.
- **Actions**. Reveals a list of actions for selected categories. Check
  one or more categories checkboxes to activate the list.
  - **Publish**. Makes the selected categories available to visitors to
    your website.
  - **Unpublish**. Makes the selected categories unavailable to visitors
    to your website.
  - **Archive**. Changes the status of the selected categories to
    indicate that they are archived.
  - **Check-In**. Checks-in the selected categories.
  - **Trash**. Changes the status of the selected categories to indicate
    that they are trashed.
  - **Batch**. Batch processes the selected categories.
- **Rebuild**. Reconstructs and refreshes the categories table.
  Normally, you do not need to rebuild this table. This function is
  provided in case the data in the table becomes corrupted.
- **Options**. Opens Articles: Options.
- **Help**. Opens this help screen.

## Batch Process

The Batch Process allows a change in settings for a group of selected
categories.

![Batch process categories](../../../en/images/articles/articles-categories-batch.png "Batch process categories")

**How to Batch Process** a group of categories:

1.  Select one or more categories on the list by checking the desired
    checkboxes.
2.  Click the Batch Toolbar button.
3.  Set one or more of the following values:
    - To change the **Language**, select the desired language from the
      Set Language list box.
    - To change the **Access Levels**, select the desired new access
      level from the Set Access Level list box.
    - To change the **Category**, select a category. To leave the
      category unchanged, use the default value of 'Select'.
      - To **copy** the categories to a different category, select the
        desired category from the category list box and check the Copy
        option. In this case, the original categories are unchanged and
        the copies are assigned to the new category and, if selected,
        the new language, access level, and tag.
      - To **move** the categories to a different category, select the
        desired category from the category list box and check the Move
        option. In this case, the original categories will be moved to a
        new category and, if selected, be assigned the new language,
        access level, and tag.
    - To add **Tags**, select the desired Tags from the dropdown or
      choose to keep the tags currently added to the original
      categories.
4.  When all of the settings are entered, click on Process to perform
    the changes. A message **"Batch process completed successfully."**
    will show.

## Quick Tips

- Click on the icon in the Status column to toggle between Published and
  Unpublished.
