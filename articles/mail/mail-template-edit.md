<!-- Filename: Help4.x:Mail_Template:_Edit / Display title: Edit Mail Template -->

## Description

The *Mail Template: Edit* page is used to change the default text for
the Subject, Body and/or HTML Body of a mail message.

### Common Elements

One element of the this page is covered in a separate Help article:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to Access

- Select **System → Templates panel → Mail Templates** from the
  Administrator menu. Then...
  - Select the Title of the template you wish to edit or select 
    the flag for the language version you wish to edit.

## Screenshot

![Edit Mail Template](../../../en/images/mail/edit-mail-template.png)

The Mail Options allow sending Plain Text or HTML messages or both. If only 
one method is selected the alternative will not be present in the message 
edit form.

This screenshot shows the plain text message edit form. If the HTML option
is enabled its edit field uses the same WYSIWYG editor used for articles.

## Form Fields

### Mail Tab

The first part of the form has information on the name and purpose of the
template.

- **Subject** This may display a string or a placeholder or a mixture of the
  two in plain text. 
- **Body** The plain text message content.
- **HTML** The HTML message content.

Items in curly braces are placeholders that will be replaced when a message
is sent. They should not be changed. For example, `{SITENAME}` is a placeholder 
that will be replaced by your site name when a message is sent. The 
placeholders are listed as *Insert Tags* to the right of the form. The 
placeholders available change from message to message.

