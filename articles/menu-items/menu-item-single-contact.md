<!-- Filename: Help4.x:Menu_Item:_Single_Contact / Display title: Menu Item: Single Contact -->

## Description

The **Single Contact** is used to show a menu link for a Single Contact
with optional settings such as Contact Details, Contact Form and Email
subject and message filters.

## How To Access

To create a new Single Contact Menu Item:

- Select **Menus → \[name of the menu\]** from Administrator menu
  (for example, **Menus → Main Menu**). Then...
  - Select the **New** button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialog select the Contacts item to open a list and then
    select the **Single Contact** item.

To edit an existing Single Contact menu item:

- Select its Title in the Menus: Items list.

## Screenshot

<img
src="https://docs.joomla.org/images/6/64/Help-4x-Menus-Menu-Item-Contact-Single-screen-en.png"
decoding="async" data-file-width="800" data-file-height="812"
width="800" height="812"
alt="Menu Item Single contact screen" />

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
- **Select Contact**. Select a contact to display for this menu item.
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

### Contact Display Options

Contact Display Options control the appearance of the list layout.

<img
src="https://docs.joomla.org/images/2/2a/Help-4x-Menus-Menu-Item-Contact-Category-contact-display-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="343"
width="600" height="343"
alt="Menu Item Single contact display options tab" />

- **Display Format**. Determines the style used to display sections of
  the contact form.
    The following options are available.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Sliders:* Slider contact view.
    - *Tabs:* Tabbed contact view.
    - *Plain:* Plain text contact view.
- **Contact Category**. Set to control the Contacts Category display
  view.
    The following options are available.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Hide:* Do not show the Category name of the contacts.
    - *Show Without Link:* Show Category name of contacts as heading styled
      text only.
    - *Show With Link* Show Category name of contacts as heading styled text
      linked to Category.
- **Show Contacts List**. Allow the user to use a drop down list of all
  contacts in one contact category. Set one of the following options:
- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show to allow users to select a contact in a drop down list.
- *Hide:* Do not display the Contact list.
- **Tags**. Whether to hide or show any tags for this item.

#### Common Contact Display Fields

- **Name**. Display the contact's *Name*.
- **Contact's Position**. Display the contact's *Contact's Position*.
- **Email**. Display the contact's *Email*.
- **Street Address**. Display the contact's *Street Address*.
- **City or Suburb**. Display the contact's *City or Suburb*.
- **State or County**. Display the contact's *State or County*.
- **Postal Code**. Display the contact's *Postal Code*.
- **Country**. Display the contact's *Country*.
- **Telephone**. Display the contact's *Telephone*.
- **Mobile phone**. Display the contact's *Mobile phone*.
- **Fax**. Display the contact's *Fax*.
- **Webpage**. Display the contact's *Webpage*.
- **Misc. Information**. Display the contact's *Misc. Information*.
- **Image**. Display the contact's *Image*.
- **vCard**. Display the contact's *vCard*.
- **Show User Articles**. Display the contact's *Articles*.
- **\# Articles to List**. Display the contact's *Number of articles to
  list*.
- **Show Links**. Display the contact's *additional links*. These could
  be links to Social Media accounts, such as Twitter, Facebook, Skype...

All of the **Common Contact Display Fields** have the following options
available:
- *Use Global:* Use the default value from the contacts options screen.
- *Show:* Show this field.
- *Hide:* Do not display this field.

- **Link \<letter\> Label**. \<A to E\> Labels (5) to override shown
  link's label.

### Mail Options

<img
src="https://docs.joomla.org/images/0/04/Help-4x-Menus-Menu-Item-Contact-Category-single-contact-mail-options-parameters-en.png"
decoding="async" data-file-width="600" data-file-height="291"
width="600" height="291"
alt="Menu Item Single contact mail options tab" />

- **Show Contact Form**. Display the contact's *contact form*.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Show:* Display this.
    - *Hide:* Do not display.
- **Send Copy to Submitter**. Display the a check box to allow a
  Submitter to send a copy of email to themselves.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Show:* Display this.
    - *Hide:* Do not display.
- **Session Check**. Check for the existence of session cookie. Users
  without cookies enabled will not be able to send emails.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Yes:* Check for session cookie.
    - *No:* Do not check for session cookie.
- **Custom Reply**. Turn on or off the custom message reply to contact
  form's submitter.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Yes:* Send an automated reply email.
    - *No:* Do not send an automated reply email.
- **Contact Redirect**. Enter alternative URL to redirect submitter
  after a successful contact form email was sent.

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

- The Category List layout is a convenient way to list a compact
  directory of contacts in a category that can include filtering and
  searching.
