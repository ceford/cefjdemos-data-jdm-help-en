<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_User_Group / Display title: User Group -->

## Group Description

### User - Contact Creator

![User contact creator form](../../../en/images/plugins/plugin-group-user-contact-creator.png)

- **Automatic Webpage** A formatted string to automatically generate a contact's web page. [name] is replaced with the name, [username] is replaced with the username, [userid] is replaced with the user ID and [email] is replaced with the email.
- **Category** Category to assign contacts to by default.
- **Automatically Publish the Contact** Optionally have the automatically created contact set to the published state and visible to website visitors.

### User - Joomla API Token

Allows the management of security tokens used for authenticating to the Joomla API application (remote site access). These tokens are strictly personal. You can view your own token but you can only disable or reset other users' tokens.

![User joomla api token form](../../../en/images/plugins/plugin-group-user-joomla-api-token.png)

- **Allowed User Groups** Select one or more to allow a group to use Joomla Tokens to authenticate to the Joomla API application.

### User - Joomla!

![User joomla form](../../../en/images/plugins/plugin-group-user-joomla.png)

- **Auto-create Users** Whether or not to automatically create registered Joomla! users where possible. Default is *Yes*.
- **Notification Mail to User** When an administrator creates a user account, this determinates if an email, which has their username and password, is sent to the user.
- **Force Logout for all Sessions?** Set to No to disable this.

### User - Profile

This plugin adds user profile capability to a website. Website users will be able to fill out profile fields enabled in the options section of this plugin. It allows control of which profile fields are shown in the new user registration form and/or each user's editable profile screen. To control what fields are shown in the new user registration form, set the field options in the section labeled User profile information required at registration. For profile fields shown in the user's profile screen which it editable after login, set the field option in the options section labeled Required user profile information. Each field has the following options:

- **Required** The field is visible in user profiles and users are required to fill it out.
- **Optional** The field is visible in user profiles but is optional and users do not need to fill it out.
- **Disabled** The field is disabled and not visible in user profiles.

![User profile form](../../../en/images/plugins/plugin-group-user-profile.png)

- **All fields** The three options are available except for the Terms of Service field which offers a choice between *Required* and *Disabled*.

### User - Terms and Conditions

This plugin allows collection of user consent to the site's terms and conditions.

![User terms and conditions form](../../../en/images/plugins/plugin-group-user-terms-and-conditions.png)

- **Short Terms & Conditions** Allows entry of a summary of Terms & Conditions or use of the language default.
- **Terms & Conditions Article** Select or Create an article for Terms & Conditions to link to a user's form.