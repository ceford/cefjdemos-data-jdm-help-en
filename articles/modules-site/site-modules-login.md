<!-- Filename: Help4.x:Site_Modules:_Login / Display title: Modules: Login -->

## Description

The **Login** module type displays a username and password Login form.
It also displays a link to retrieve a forgotten password. If User
registration is enabled in the User Settings of the Global Configuration
screen, then the link "Create an Account" will be shown to invite Users
to self-register.

### Common Elements

Some elements of the this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Modules: Modules Tab](jdocmanual?article=help/modules/modules-module-tab).
* [The Modules: Menu Assignment Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [The Modules: Advanced Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **System → Manage Panel → Site Modules** from the
  Administrator menu. Then...
  - To create a new module: select the **New** button from the Toolbar.
    Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

![login module tab](../../../en/images/modules-site/modules-login-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Pre-text** This is the text or HTML that is displayed above the
  login form.
- **Post-text** This is the text or HTML that is displayed below the
  login form.
- **Login Redirection Page** Select or create the page the user will be 
  redirected to after a successful login. Select from all the pages listed in 
  the popup menu list.  If no menu item is selected, users will stay on the same 
  page after login. 
- **Logout Redirection Page** Select or create the page the user will be 
  redirected to after a successful logout. Select from all the pages listed in 
  the popup menu list.  If no menu item is selected, users will stay on the 
  same page after logout. 
- **Registration Page** Select or create a page for registration.
- **Greeting** Show or hide the simple greeting text.
- **Name/Username** Displays name or username after login.
- **Profile link** Show or hide a link to the profile of the User.
- **Display Labels** Choose text or icons to display the fields labels. The
  default is icons.
