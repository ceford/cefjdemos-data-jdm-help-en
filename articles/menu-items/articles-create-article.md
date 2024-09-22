<!-- Filename: Help4.x:Menu_Item:_Create_Article / Display title: Create Article -->

## Description

The *Create Article* menu item allows users to submit an article via the
Site interface. Normally this is available only to users who have logged
in to the Frontend of the site. Users must have permission to create articles.

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

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  Select the **New** button in the Toolbar.
2.  Select the *Menu Item Type* **Select** button.
3.  Select the **Articles** item in the popup dialogue.
4.  Select the **Create Article** item.

To edit a Menu Item:

- Select a **Title** from the list

## Screenshot

![Menu Item Articles Create Article details tab](../../../en/images/menu-items/articles-create-article-details-tab.png)

## Form Fields

- **Title** The title that will display for this menu item.
- **Alias** The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Details

#### Left Panel

- **Menu Item Type** The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Link** The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window** Select from the dropdown list.
- **Template Style** Select from the dropdown list.

#### Right Panel

- **Menu** Shows which menu the link will appear in.

### Options

![Menu Item Articles Create Article details tab](../../../en/images/menu-items/articles-create-article-options-tab.png)

- **Specific Category**
  - *Yes* Articles will be assigned to the specified category. The user
    will not be able to select a category.
  - *No* The user may select the category from the list box. Only
    categories for which the user has *Create* permission will show.
- **Submission/Cancel Redirect** Select the page the user will be
  redirected to after a successful article submission.
- **Custom Redirect on Cancel**
  - *Yes* Set a page to redirect to when user Cancels article submission.
  - *No* When user Cancels article submission, the user is redirected to
    the *Submission/Cancel Redirect* page.

## Example Frontend Screenshot

This Screenshot shows Joomla core Frontend Template **Cassiopeia** with all
Editing Layout options set to 'Hide'.

[articles-create-article-frontend.png](../../../en/images/menu-items/articles-create-article-frontend.png)

## Tips

An unauthorised user will normally get an error on selection of a
*Create Article* menu item. For this reason, it is normal practice to give
the menu item a viewing Access Level that can only be seen by users
authorised to add articles.
