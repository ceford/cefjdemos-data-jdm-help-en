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

- Select its Title in the *Menus: Items* list.

## Screenshot

![Login form details tab](../../../en/images/menu-items/users-login-form-details-tab.png)

## Form Fields

### Options Tab

![Login form details tab](../../../en/images/menu-items/users-login-form-options-tab.png)

#### Login panel

- **Choose Login Redirect Type** This may be a *Menu Item* or an *Internal URL*.
  The following fields change depending on the setting of this parameter. For 
  a multilingual site, *Menu Item* is recommended.
  - **Menu Item Login Redirect** Select or create a menu item for the page
    to redirect to after a successful login. If no menu item is selected, 
    users will be redirected to the their profile after login. 
  - **Login Redirect** Select an internal URL to redirect to after login.
- **Login Description** Show or hide the login description.
- **Login Description Text** Enter text to display on Login page.
- **Login Image** Select or upload an image to display on Login page.
- **Image Description (Alt Text)** Required for screen readers for accessibility
  purposes.
- **No Description** A checkbox to select if the image is purely decorative and
  requires no explanation.

#### Logout panel

This panel uses the same fielding headings to control the logout process.

## Tips

- The **Login and Logout URL** can be used to send a user to a specific
  page created to provide some feedback to the user. For example, a page 
  entitled *You are now Logged In* with some general information. The use of
  a User Module to show links for Updating User Profile, Viewing User Profile 
  and other User functions could be shown on this page enhancing a user's 
  site experience.
