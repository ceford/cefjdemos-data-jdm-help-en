<!-- Filename: Help4.x:Menu_Item:_Login_Form / Display title: Menu Item: Login Form -->

## Description

The **Login Form** menu item type is used to create a page containing a
Login form.

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

<img
src="https://docs.joomla.org/images/a/a0/Help-4x-Menus-Menu-Item-User-Login-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menu Item Login Form screenshot" />

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

### Options Tab

<img
src="https://docs.joomla.org/images/e/e7/Help-4x-Menus-Menu-Item-User-Login-basic-options-screenshot-en.png"
decoding="async" data-file-width="800" data-file-height="385"
width="800" height="385"
alt="Menu Item Login Form options tab" />

- **Choose Login Redirect Type:** 'Internal URL' lets you manually enter
  any internal URL in the Redirect field. 'Menu Item' lets you directly
  select an existing menu item. For a multilingual site, it is
  recommended to use 'Menu Item'.
- **Menu Item Login Redirect:** Select or create the page the user will
  be redirected to after a succesful login. The default is to remain on
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
  be redirected to after succesfully ending their current session by
  logging out. The default is to remain on the same page.
- **Logout Description:** Show or hide logout description.
- **Logout Description Text:** Enter text to display on Logout page.
- **Logout Image:** Select or upload an image to display on Logout page.

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
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. Or
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.

## Front End Screenshot

*Example Front End Site images are generic images using Joomla! core
installation supplied free Front End Templates. The actual view can
depend on the installed custom template used and the template's style
for those views on a Joomla! website.*

User Login shown:

<img
src="https://docs.joomla.org/images/1/1a/Help-4x-Menus-Menu-User-Login-front-end-screenshot-en.png"
decoding="async" data-file-width="350" data-file-height="426"
width="350" height="426"
alt="Menu Item Login Form front end screenshot" />

## Quick Tips

- The **Login and Logout URL** can be used to send a user to a specific
  page('article') created to provide some feedback to the user. For
  example, a page titled, 'You are now Logged In' with some general
  information. The use of a User Module to show links for Updating User
  Profile, Viewing User Profile and other User functions could be shown
  on this page enhancing a user's site experience.
