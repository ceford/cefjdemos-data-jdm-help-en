<!-- Filename: Help4.x:Articles:_New_or_Edit_Category / Display title: Articles: Edit Category -->

## Description

Categories are are used to organize Articles, Contacts and other
components for ease of management and display. They can be organised
into tree-like structures like file systems. For example, category Pets
may be a parent to category Dogs, category Cats and Category Goldfish.
Categories can be nested to any level. All Articles must be assigned
either to a parent Category or a child Category or to the default
Category named 'Uncategorized'.

The edit form is used to create a new Category or to alter the properties of
an existing Category.

### Common Elements

Some elements of the Category edit page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars "").
* [The Publishing Tab](jdocmanual?article=help/common-elements/edit-publishing "").
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations "").
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions "").

## How to Access

To add a new category, starting from the Administrator menu:

- Select **Home Dashboard → Site panel → Categories + button**.
  Or...
- Select **Content → Categories + button**. Or...
- Select **Content → Categories**. Then...
  - Select the **New** button in the Toolbar to create a new Category.
    Or...

To edit an existing Category:

- Select **Content → Categories**. Then...
  - Select a **Category title** From the list of categories.

## Screenshot

![Edit category screenshot](../../../en/images/articles/articles-edit-category-category-tab.png "Edit category")

## Form Fields

- **Title.** The Title for this item. This may or may not display on the
  page, depending on the parameter values you choose.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Category Tab

#### Left Panel

- **Description**. The description for the item. Category, Subcategory
  and Web Link descriptions may be shown on web pages, depending on the
  parameter settings. These descriptions are entered using the same
  editor that is used for Articles.
- **Toggle Editor**. A Toggle Editor button show below the edit window.
  This button allows you to toggle between the TinyMCE editor and No
  Editor.

#### Right Panel

- **Parent.** The item (category, menu item, and so on) that is the
  parent of the item being edited.
- **Status.** (Published/Unpublished/Archived/Trashed) The published
  status of the item.
- **Access Level.** Who has access to this item. Default options are:
  - **Public:** Everyone has access
  - **Guest:** Everyone has access
  - **Registered:** Only registered users have access
  - **Special:** Only users with author status or higher have access
  - **Super Users:** Only super users have access
  - Enter the desired level using the drop-down list box. Custom Access
    Control Levels created will show if they exist.
- **Language.** Item language.
- **Tags.** Enter one or more optional tags for this item. You can
  select existing tags by entering in the first few letters. You may
  also create new tags by entering them here. Tags allow you to see
  lists of related items across content types (for example, articles,
  contacts, and categories).
- **Note.** Item note. This is normally for the site administrator's use
  (for example, to document information about this item) and does not
  show in the front end of the site.
- **Version Note.** Optional field to identify this version of the item
  in the item's Version History
  window.

### Options

This shows Options for this Category, as shown below when tab is
clicked:

![Edit category options tab](../../../en/images/articles/articles-edit-category-options-tab.png "Edit category options tab")

- **Layout**. Use a different layout from the supplied components view
  or overrides in the templates.
- **Image**. Choose an image to be displayed with this item/category in
  the Frontend.
- **Alt Text**. Alternative text used for visitors without access to
  images.

### Workflow

![Edit category workflow tab](../../../en/images/articles/articles-edit-category-workflow-tab.png "Edit category workflow tab")

- **Workflow.** Select from the drop-down list.
