<!-- Filename: Help4.x:Menu_Item:_Login_Form / Display title: Login Form -->

## Description

The **Login Form** menu item type is used to create a page containing a
Login form.

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

To create a new **Login Form** menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the Users item to open a list and then
    select the **Login Form** item.

To edit an existing Login Form menu item:

- Select its Title in the Menus: Items list.

## Screenshot

![Login form details tab](../../../en/images/menu-items/users-login-form-details-tab.png)

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Options Tab

![Login form details tab](../../../en/images/menu-items/users-login-form-options-tab.png)

- **Choose Login Redirect Type:** 'Internal URL' lets you manually enter
  any internal URL in the Redirect field. 'Menu Item' lets you directly
  select an existing menu item. For a multilingual site, it is
  recommended to use 'Menu Item'.
- **Menu Item Login Redirect:** Select or create the page the user will
  be redirected to after a successful login. The default is to remain on
  the same page.
- **Login Description:** *(Show or Hide)* Show or hide the login
  description.
- **Login Description Text:** Enter text to display on Login page.
- **Login Image:** Select or upload an image to display on Login page.
- **Choose Logout Redirect Type:** 'Internal URL' lets you manually
  enter any internal URL in the Redirect field. 'Menu Item' lets you
  directly select an existing menu item. For a multilingual site, it is
  recommended to use 'Menu Item'.
- **Menu Item Logout Redirect:** Select or create the page the user will
  be redirected to after successfully ending their current session by
  logging out. The default is to remain on the same page.
- **Logout Description:** Show or hide logout description.
- **Logout Description Text:** Enter text to display on Logout page.
- **Logout Image:** Select or upload an image to display on Logout page.

## Quick Tips

- The **Login and Logout URL** can be used to send a user to a specific
  page('article') created to provide some feedback to the user. For
  example, a page titled, 'You are now Logged In' with some general
  information. The use of a User Module to show links for Updating User
  Profile, Viewing User Profile and other User functions could be shown
  on this page enhancing a user's site experience.
