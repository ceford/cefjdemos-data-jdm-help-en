<!-- Filename: Help4.x:Contacts:_New_or_Edit / Display title: Contacts: Edit -->

## Description

The Contacts: Edit Form is used to add a new Contact or edit an existing Contact.

**Be aware:** If a contact has a menu item then the Contact Menu
Settings override some settings available here. Be careful not to
disclose personal information by mistake!

### Common Elements

Some aspects of the *Contacts: Edit* page are covered in separate Help
articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars "").
* [The Schema Tab](jdocmanual?article=help/common-elements/edit-schema "").
* [The Publishing Tab](jdocmanual?article=help/common-elements/edit-publishing "").
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations "").

## How to Access

- Select **Components → Contacts → Contacts** in the Administrator menu. Then...
- To **Add** a new Contact:
  - Select the **New** button in the Toolbar.
- To **Edit** an existing Contact:
  - Select a contact title in the **Title** column.

## Screenshot

![Contacts edit contact tab](../../../en/images/contacts/contacts-edit-contact-tab.png)

## Form Fields

In this section, you can enter information about the Contact, such as
name, address, e-mail, and so on. The options allow you to control
settings such as what information gets displayed for each Contact.

- **Name.** The full name of the Contact.
- **Alias**. The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

### Edit Contact tab

Here you enter the basic information about the contact.

- **Linked User.** Select the User, if any, that this Contact is linked
  to from the drop-down list box. This allows you to link this Contact's
  information to a registered Joomla! User. If this Contact is not
  linked to a User, select "-No User-".
- **Image.** Image to display for this Contact. Select an image file
  from the drop-down list box. This lists images in the 'images/stories'
  folder. Images can be uploaded using the Media component.
- **Position:** The Contact's current position.
- **E-mail.** The Contact's e-mail address. Note that e-mail addresses
  in Joomla! can be protected from "spambots" by enabling "Content-Email
  Cloaking" Plugin. This is enabled by default.
- **Address.** The Contact's street address.
- **City or Suburb.** The Contact's town or suburb.
- **State or Province.** The Contact's state or county.
- **Postal / ZIP Code.** The Contact's postal code.
- **Country.** The Contact's country.
- **Telephone.** The Contact's phone number.
- **Mobile.** The Contact's mobile phone number.
- **Fax.** The Contact's fax number.
- **Website.** The Contact's web site address.
- **Sort Fields.** To enable sort fields for Category lists go to the
  **Contacts → Options** screen and set **List Layouts → Sort
  By** to **Sort Name**. Then you need to use real words for sorting.
  For example, set First Sort Field to **Doe**, second field to **John**
  for the first contact; then First Sort Field to **Doe**, second field
  to **Jane** for the second contact. The third field is not used in
  this case. The sort fields are character fields so if you want to sort
  by age you need to enter 0x for ages under 10, so 08 for example.
  - **First Sort Field.** The name to use as the first sort field.
  - **Second Sort Field.** The name to use as the second sort field.
  - **Third Sort Field.** The name to use as the third sort field.
- **Status**: Published status of the item. Possible values are:
  - *Published*: The item is published. This is the only state that will
    allow regular website users to view this item.
  - *Unpublished*: The item is unpublished.
  - *Archived*: The item has been archived.
  - *Trashed*: The item has been sent to the Trash.
- **Category.** The Category this item belongs to.
- **Featured.** Whether or not the item will be displayed in featured
  view.
- **Access**. The viewing Access  Level   for this item.
- **Language**. Item language.
- **Tags**. Enter one or more optional tags for this item. You can
  select existing tags by entering in the first few letters. You may
  also create new tags by entering them here. Tags allow you to see
  lists of related items across content types (for example, articles,
  contacts, and categories).
- **Version Note**. Optional field to identify this version of the item
  in the item's Version History
  window.

### Miscellaneous Information tab

![Contacts edit contact tab](../../../en/images/contacts/contacts-edit-miscellaneous-tab.png)

Other information about this Contact can be entered using the editor.

### Display tab

![Contacts edit contact tab](../../../en/images/contacts/contacts-edit-display-tab.png)

- **Show Category.** Show or hide the Contact's category.
- **Show Contact List.** Show or hide the Contact list.
- **Display format.** Determines the style used to display sections of
  the contact form.
- **Tags**. Whether to hide or show any tags for this item.
- **Contact Information.** Hide or Show the Contact information.
- **Miscellaneous Information.** Hide or Show the Miscellaneous
  information.
- **vCard.** Hide or Show the vCard link for this Contact.
- **Show User Articles.** If this contact is mapped to a user, and if
  this is set to Show, then a list of articles created by this user will
  show.
- **\# Articles to List.** Number of articles to list.
- **User Profile.** If this contact is mapped to a user, and if this is
  set to Show, then the profile of this user will show.
- **Show User Custom Field Groups.** Show user custom fields which
  belong to all or only selected field groups.
- **Contact Links.** Show or hide the contact links.
- **Link A Label.** Label for an additional link for this contact.
- **Link A URL.** The additional link URL for this contact.
- **Link B Label.** Label for an additional link for this contact.
- **Link B URL.** The additional link URL for this contact.
- **Link C Label.** Label for an additional link for this contact.
- **Link C URL.** The additional link URL for this contact.
- **Link D Label.** Label for an additional link for this contact.
- **Link D URL.** The additional link URL for this contact.
- **Link E Label.** Label for an additional link for this contact.
- **Link E URL.** The additional link URL for this contact.
- **Layout.** Use a different layout from the supplied component view or
  overrides in the templates.

### Form tab

![Contacts edit contact tab](../../../en/images/contacts/contacts-edit-form-tab.png)

- **Contact Form.** Hide or Show the E-mail form. If Show is selected, a
  form is displayed that allows the user to send an e-mail to the
  Contact from the web site.
- **Send Copy to Submitter.** Hide or Show the checkbox: 'E-mail a copy
  of this message to your own address.'
- **Session Check.** Check for the existence of session cookie. This
  means that users without cookies enabled will not be able to send
  emails.
- **Custom Reply.** Turns off the automated reply, allowing for Plugins
  to handle integration with other systems.
- **Contact Redirect.** Enter an alternative url, where user will be
  redirected to after the mail is sent.

