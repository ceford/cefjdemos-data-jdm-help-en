<!-- Filename: Help4.x:Menu_Item:_List_Contacts_in_a_Category / Display title: List Contacts in a Category -->

## Description

The **List Contacts in a Category** menu item type is used to show
contacts in a given Category in a list layout. Settings include: Contact
Details, Contact Form, presentation(slider, tabs, plain view), and Email
subject and message filters.

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

To create a new List Contacts in a Category menu item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**).
  - Select the **New** Toolbar button. Then...
  - Select the Menu Item Type Select button
  - In the modal dialog select the Contacts item to open a list and then
    select the **List Contacts in a Category** item.

To edit an existing List Contacts in a Category menu item:

- Select its Title in the Menus: Items list.

## Screenshot

![Menu Item List Contacts in a Category details tab](../../../en/images/menu-items/contacts-list-contacts-in-a-category-details-tab.png)

## Form Fields

- **Menu Title** The title that will display for this menu item.
- **Alias** The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Category Tab

The Category Options control the way that category information is shown
in the layout. The Category List Layout has the following Category
Options, as shown below.

![Menu Item List Contacts in a Category category tab](../../../en/images/menu-items/contacts-list-contacts-in-a-category-category-tab.png)

- **Category Title** Show or hide the Category Title which
  will show as a subheading on the page. The subheading is usually
  displayed inside the "H2" tag.
- **Category Description** Show or hide the description of the selected
  Category.
- **Category Image** Show or hide the category image.
- **Subcategory Levels** The number of levels of subcategories to show in
  the layout. Select *All* to show all levels in the subcategory hierarchy.
- **Empty Categories** Show or hide the categories that contain no content
  items or subcategories.
- **Subcategories Descriptions** Show or hide the category description of
  subcategories.
- **\# Contacts in Category** Show or hide the number of Contacts in a
  Contact Category.

### List Layouts Tab

List Layout Options control the appearance of the list layout.

![Menu Item List Contacts in a Category list layouts tab](../../../en/images/menu-items/contacts-featured-contacts-list-layouts-tab.png)

- **Filter Field** Show or hide the Filter Field which creates a text field
  for the front-end user to enter some part of a contact name to search for.
- **Display Select** Show or hide the Display \# control that allows the user
  to select the number of items to show in the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings** Show or hide the Table Headings above a list.
- **Image** Show or hide an Image column in the list of Contacts.
- **Position** Show or hide the position this contact holds
  in the organisation. For example CEO, Secretary, Janitor.
- **Email** Show or hide the contact Email display in the list.
- **Phone** Show or hide the contact Phone number display in the list.
- **Mobile** Show or hide the contact Mobile number display in the list.
- **Fax** Show or hide the contact Fax number display in the list.
- **City or Suburb** Show or hide the contact City or Suburb display in the
  list.
- **State or County** Show or hide the contact State or County display in the
  list.
- **Country** Show or hide the contact Country display in the list.
- **Pagination** Show or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
    The following options are available.
    - *Use Global* Use the default value from the component options screen.
    - *Auto* Pagination links shown if needed.
    - *Show* Pagination links shown if needed.
    - *Hide* Pagination links not shown. Note: In this case, Users will not
    be able to navigate to additional pages.
- **Pagination Results** Show or hide current page number and total number of
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.
- **Sort by** Choose an ordering field name for sorting the list.

### Contact Display Tab

Contact Display fields control the appearance of the list layout.
![Menu Item List Contacts in a Category contact display tab](../../../en/images/menu-items/contacts-featured-contacts-form-tab.png)

- **Choose a Layout** Select from the list of templates.
- **Contact Category** Show or hide the Contact Category display view.
    The following options are available.
    - *Use Global* Use the default value from the contacts options screen.
    - *Hide* Do not show the Category name of the contacts.
    - *Show Without Link* Show Category name of contacts as heading styled
      text only.
    - *Show With Link* Show Category name of contacts as heading styled text
    linked to Category.
- **Contact Select List** Show or hide to allow the user to use a drop down
  list of all contacts in one contact category.
- **Name** Show or hide the contact's *Name*.
- **Tags** Show or hide any contact's tags.
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

Contact Mail Options control the appearance of a Contact's → *Contact Form*
if it is enabled.

![Menu Item List Contacts in a Category mail options tab](../../../en/images/menu-items/contacts-featured-contacts-mail-options-tab.png)

- **Contact Form** Show or hide the contact's *contact form*.
- **Send Copy to Submitter** Show or hide the a check
  box to allow a Submitter to send a copy of email to themselves.
- **Session Check** Check for the existence of a session cookie. Users without
  cookies enabled will not be able to send emails.
- **Custom Reply** Turn on or off the custom message reply to contact form's
  submitter.
- **Contact Redirect** Enter alternative URL to redirect the submitter to
  after a successful contact form email is sent.

## Tips

- The Category List layout is a convenient way to list a compact
  directory of contacts in a category that can include filtering and
  searching.
