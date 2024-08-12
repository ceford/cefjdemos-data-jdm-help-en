<!-- Filename: Help4.x:Menu_Item:_Featured_Contacts / Display title: Featured Contacts -->

## Description

The **Featured Contacts** menu item type is used to show a list of
featured contacts.

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

To create a new Featured Contacts Menu Item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the New button in the Toolbar. Then...
  - Select the Menu Item Type Select button
  - In the modal dialog select the Contacts item to open a list and then
    select the **Featured Contacts** item.

To edit an existing Featured Contacts menu item:

- Select its Title in the Menus: Items list.

## Screenshot

![Menu Item Featured Contacts Details tab](../../../en/images/menu-items/contacts-featured-contacts-details-tab.png)

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### List Layouts tab

List Layout Options control the appearance of the list layout.

![Menu Item Featured Contacts list layouts tab](../../../en/images/menu-items/contacts-featured-contacts-list-layouts-tab.png)

- **Filter Field** Show or hide the list filter.
- **Display Select** Show or hide the number of items to show in the list.
  - If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings** Show or hide the list table Headings.
- **Position**. Show or hide a Position column in the list of Contacts.
- **Email** Show or hide the Email display.
- **Phone** Show or hide the Phone display.
- **Mobile** Show or hide the Mobile display.
- **Fax** Show or hide the Fax display.
- **City or Suburb** Show or hide the City or Suburb display.
- **State or County** Show or hide the State or County display.
- **Country** Show or hide the Country display.
- **Pagination** Shoe or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    The following options are available.
    - *Use Global:* Use the default value from the component options screen.
    - *Auto:* Pagination links shown if needed.
    - *Show:* Pagination links shown if needed.
    - *Hide:* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Summary** Show or hide the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.

### Form Tab

![Menu Item Featured Contacts form tab](../../../en/images/menu-items/contacts-featured-contacts-form-tab.png)

- **Tags** Show or hide the contact's *Tags*.
- **Contact Information** Show or hide the contact's *Contact Information*.
- **vCard** Show or hide the contact's *vCard*.
- **Miscellaneous Information** Show or hide the contact's *Miscellaneous
  Information*.
- **User Articles** Show or hide the contact's *User Articles*.
- **\# Articles to List** Show or hide the contact's *\# Articles to List*.
- **Contact Links** Show or hide the contact's *Contact Links*.
- **Link \<letter\> Label**. \<A to E\> Labels (5) to override the shown
  link's label.

### Mail Options Tab

Contact Mail Options control the appearance of a Contact's → *Contact Form* if 
it is enabled.

![Menu Item Featured Contacts mail options tab](../../../en/images/menu-items/contacts-featured-contacts-mail-options-tab.png)

- **Contact Form** Show or hide the contact's *contact form*.
- **Send Copy to Submitter**. Show or hide the a check box to allow a
  Submitter to send a copy of email to themselves.
- **Session Check** Check for the existence of session cookie. Users
  without cookies enabled will not be able to send emails.
    It has the following options available:
    - *Use Global:* Use the default value from the contacts options screen.
    - *Yes:* Check for session cookie.
    - *No:* Do not check for session cookie.
- **Custom Reply** Turn on or off the custom message reply to contact
  form's submitter, allowing for Plugins to handle integration with
  other systems.
    It has the following options available:
    - *Use Global:* Use the default value from the contacts options screen.
    - *Yes:* Send an automated reply email.
    - *No:* Do not send an automated reply email.
- **Contact Redirect** Enter an alternative URL to redirect the submitter
  after the email is sent.

## Quick Tips

- To feature a contact do one of the following using the Contacts list:
  - Select the Featured symbol (circle with a star) in the Featured column, 
  - Select the Item select check box and select Feature in the Actions 
  drop-down list in the Toolbar. Several items can be selected to Feature 
  or Unfeature via the Actions list.
