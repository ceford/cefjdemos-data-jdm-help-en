<!-- Filename: Help4.x:Mass_Mail_Users / Display title: Mass Mail Users -->

## Description

The *Mass Mail Users* page allows members of the *Super Users* group to send an
email message to registered users of the site. Recipients can be selected based
on user groups.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to access

Select **Users → Mass Mail Users** from the Administrator menu.

## Screenshot

![mass mail users](../../../en/images/users/mass-mail-users.png)

## Details and Message

- **Mail to Child Groups** Whether or not to send the Email to members
  of all child groups of the selected group. For example, if this box is
  checked and the *Public* group is selected, the email would be sent to
  almost all users, since most groups are child groups of *Public*.
- **Send in HTML mode** Whether or not to send the Email with headers
  that identify it as an HTML document. Email clients that support this
  will render any HTML codes.
- **Send to Disabled Users** If checked, disabled users will be
  included when sending mail.
- **Recipients as BCC** If checked, all recipients will be included as
  BCC entries, so none will see any of the other recipients' Email
  addresses. Because many mail routers treat Email without a *To:* entry
  as spam, the site email will be used for the *To:* entry.
- **Group** Select the groups you want to send the Email to.
- **Subject** Enter the Subject of the Email. Try to make it as
  descriptive as possible. Any text entered in the *Subject Prefix*
  parameter in Options (User Options → Mass Mail)
  will be placed in front of the subject you enter here.
- **Message** Enter the body of the Email. Any text entered in the
  *Mailbody Suffix* parameter in Options (User Options → Mass Mail)
  will be added to the text you enter here.
