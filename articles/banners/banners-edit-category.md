<!-- Filename: Help4.x:Banners:_New_or_Edit_Category / Display title: Banners: Edit Category -->

## Description

This is where you can add a new Banner Category or edit an existing one.
Note that you need to create at least one Banner Category before you can
create a Banner. Also, Banner Categories are separate from other types
of Categories, such as those for Articles, Contacts, and News Feeds.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Category Tab](jdocmanual?article=help/common-elements/edit-category).
* [The Options Tab](jdocmanual?article=help/common-elements/edit-category-options).
* [The Publishing Tab](jdocmanual?article=help/common-elements/edit-publishing).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

Navigate to the Banner Categories list:

- Select **Components → Banners → Categories** from the Administrator menu.
- Either: Select the **New** button in the Toolbar to create a new category.
- Or: Select a **Category Name** in the **Title** column to edit an existing category.

## Screenshot

![Banners edit category](../../../en/images/banners/banners-edit-category-category-tab.png)

## Form Fields

- **Title** The Title for this item. This may or may not display on the
  page, depending on the parameter values you choose.
- **Alias** The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Category tab

#### Left Panel

- **Description** The description for the item. Category, Subcategory
  and Web Link descriptions may be shown on web pages, depending on the
  parameter settings. 

#### Right Panel

- **Parent** The item (category, menu item, and so on) that is the
  parent of the item being edited.
- **Status** The published status of this item.
  - *Published* Item is visible in the Frontend of the site.
  - *Unpublished* Item is will not be visible to guests in the Frontend
    of the site. It may be visible to logged in users who have edit
    state permission for the item.
  - *Archived* Item will no longer show on blog or list menu items.
  - *Trashed* Item is deleted from the site but still in the database.
    It can be permanently deleted from the database with the Empty Trash
    function in Toolbar (see also Deleting an Article.
- **Access** Select the viewing access level for this item from the
  list box. The access levels that display will depend on the what has
  been set up for this site in Users → Access Levels.
  Note that access levels are separate from ACL permissions. Access
  levels control what a user can see. ACL permissions control what
  actions a user can perform.
- **Language** Select the language for this item. If you are not using
  the multi-language feature of Joomla, keep the default of 'All'.
- **Tags** Assign tags to content items. You may select a tag from the
  pre-defined list or enter a new tag by typing the name in the field
  and pressing enter.
- **Note** This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.
- **Version Note** Optional field to identify this version of the item
  in the item's Version History
  window.
