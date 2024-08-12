<!-- Filename: Help4.x:Menu_Item:_List_All_Contact_Categories / Display title: List All Contact Categories -->

## Description

The **List All Categories in a Contact Category Tree** menu item type is 
used to show a list of contact categories within a category.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [The Integration Tab](jdocmanual?article=help/menu-items-common/menu-item-integration).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new List All Contact Categories menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**).
- Select the New Toolbar button.
- Select the Menu Item Type Select button.
  Then...
  - In the modal dialog select the Contacts item to open a list and then
    select the **List All Contact Categories** item.

To edit an existing List All Contact Categories Menu Item:

- Select its Title in the Menus: Items list.

## Screenshot

![Menu Item Contacts List All Categories tree details tab](../../../en/images/menu-items/contacts-list-all-categories-tree-details-tab.png)

## Form Fields

- **Menu Title:** The title that will display for this menu item.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Categories Tab

The Categories Options control the way categories information is
displayed in the layout. Things that you can modify are:

![Menu Item Contacts List All Categories tree categories tab](../../../en/images/menu-items/contacts-list-all-categories-tree-categories-tab.png)

- **Top Level Category Description** Show or hide the
  description of the top level category or optionally override with the
  text from the description field found in menu item. If using Root as
  top level category, the description field has to be filled.
- **Alternative Description** If you enter some text in this field, it
  will override the Top Level Category Description, if it has one.
- **Subcategory Levels.** The number of subcategory levels to display.
- **Empty Categories** Show or hide empty categories. A category is only 
  empty if it has no Contacts or subcategories.
- **Subcategories Descriptions** Show or hide the subcategories description.
- **\# Contacts in Category.** Show or hide number of contacts in a category.

### Category Tab

The Category Options control the way that category information is shown
in the layout. The Category List Layout has the following Category
Options, as shown below.

![Menu Item Contacts List All Categories tree category tab](../../../en/images/menu-items/contacts-list-all-categories-tree-category-tab.png)

- **Category Title** Show or hide the Category Title as a subheading on the 
  page. The subheading is usually displayed inside the "H2" tag.
- **Category Description** Show or hide the description of the selected Category.
- **Category Image** Show or hide the category image.
- **Subcategory Levels** The number of levels of subcategories to show in the 
  layout. Select *All* to show all levels in the subcategory hierarchy.
- **Empty Categories** Show or hide the categories that contain no content 
  items or subcategories.
- **Subcategories Descriptions** Show or hide the category description of 
  subcategories.
- **\# Contacts in Category** Show or hide the number of Contacts in a 
  Contact Category.

### List Layouts Tab

List Layout Options control the appearance of the list layout.

![Menu Item Contacts List All Categories tree list layouts tab](../../../en/images/menu-items/contacts-list-all-categories-tree-list-layouts-tab.png)

- **Filter Field** Show or hide a Filter field for the list.
- **Display Select** Show or hide the Display \# control that allows the 
  user to select the number of items to show in the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings** Show or hide Table Headings above a list.
- **Position** Show or hide the Contact's current position.
- **Email** Show or hide the Contact's Email address.
- **Phone** Show or hide the Contact's Phone number.
- **Mobile** Show or hide the Contact's Mobile number.
- **Fax** Show or hide the Contact's Fax number.
- **City or Suburb** Show or hide the City or Suburb.
- **State or County**. Show or hide the State or County.
- **Country** Show or hide the Country.
- **Pagination** Show or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    The following options are available.
    - *Use Global:* Use the default value from the component options screen.
    - *Auto:* Pagination links shown if needed.
    - *Show:* Pagination links shown if needed.
    - *Hide:* Pagination links not shown. Note: In this case, Users will not
      be able to navigate to additional pages.
- **Pagination Results** Show or hide the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page.

### Contact Display Options Tab

Contact Display Options control the appearance of the list layout.

![Menu Item Contacts List All Categories tree contact display options tab](../../../en/images/menu-items/contacts-list-all-categories-tree-contact-display-options.png)

- **Contact Category** Show or hide the Contacts Category display view.
    - *Use Global:* Use the default value from the contacts options screen.
    - *Hide:* Do not show the Category name of the contacts.
    - *Show Without Link:* Show Category name of contacts as heading styled
      text only.
    - *Show With Link* Show Category name of contacts as heading styled text
      linked to Category.
- **Contacts Select List**. Allow the user to use a drop down list of all
  contacts in one contact category.
- **Name** Display the contact's *Name*.
- **Tags** Display the contact's *Tags*.
- **Contact Information** If set to Show the following fields are available:
  - **Contact's Position** Show or hide the contact's *Contact's Position*.
  - **Email** Show or hide the contact's *Email*.
  - **Street Address** Show or hide the contact's *Street Address*.
  - **City or Suburb** Show or hide the contact's *City or Suburb*.
  - **State or County** Show or hide the contact's *State or County*.
  - **Postal Code** Show or hide the contact's *Postal Code*.
  - **Country** Show or hide the contact's *Country*.
  - **Telephone** Show or hide the contact's *Telephone*.
  - **Mobile phone** Show or hide the contact's *Mobile phone*.
  - **Fax** Show or hide the contact's *Fax*.
  - **Webpage** Show or hide the contact's *Webpage*.
  - **Image** Show or hide the contact's *Image*.
- **vCard** Display the contact's *vCard*.
- **Miscellaneous Information** Display the contact's *Miscellaneous Information*.
- **User Articles** Display the contact's *Articles*.
- **\# Articles to List** The number the contact's articles to list.
- **Contact Links** Show or hide the contact's *additional links*. These could
  be links to Social Media accounts, such as Twitter, Facebook, Skype...
- **Link \<letter\> Label**. \<A to E\> Labels (5) to override shown
  link's label.

### Mail Options Tab

![Menu Item Contacts List All Categories tree mail options tab](../../../en/images/menu-items/contacts-list-all-categories-tree-mail-options-tab.png)

- **Contact Form** Show or hide the contact's *contact form*.
- **Send Copy to Submitter** Show or hide the a check
  box to allow a Submitter to send a copy of email to themselves.
- **Session Check** Check for the existence of a session cookie. Users without 
  cookies enabled will not be able to send emails.
- **Custom Reply** Turn on or off the custom message reply to contact form's 
  submitter.
- **Contact Redirect** Enter alternative URL to redirect the submitter to
  after a successful contact form email is sent.
