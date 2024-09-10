<!-- Filename: Help4.x:Users:_Edit_Profile / Display title: Users: New or Edit -->

## Description

The User Edit screen is used to create a new user or edit an existing
user.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to access

To edit an existing user:

- Select **Users → Manage** from the Administrator menu. Then...
  - Search for the required user and select the name link in the
    **Name** column.

To create a new user:

- Select **Users → Manage** from the Administrator menu. Then...
  - Select the **New** button in the Toolbar.
- Or... Select **Users → Manage → Plus icon** from the
  Administrator menu.
- Or... Select **Users → Dashboard icon** from the Administrator
  menu. Then...
  - Select the **Plus** icon from the Users panel.
- Or... Select **Home Dashboard → Site Panel → Users Plus icon**
  starting from the Administrator menu.

## Screenshot

![user edit details tab](../../../en/images/users/users-edit-account-details-tab.png)

## Form Fields

### Account Details

- **Name** Enter the name of the user.
- **Login Name** Enter the login name (Username) for the user.
- **Password** Fill in a (new) password. Although this field is not
  required, the user will not be able to log in when no password is set.
- **Confirm Password** Fill in the password from the field above again,
  to verify it. This field is required when you filled in the New
  password field.
- **Email** Enter an email address for the user.
- **Registration Date** Registration Date of the user.
- **Last Visit Date** Date the user visited the site last time.
- **Last Reset Date** Date and time of last password reset.
- **Password Reset Count** Number of password resets since starting the
  last reset time.
- **Receive System Emails** (*Yes*/*No*) If set to yes, the user will
  receive system emails.
- **User Status** (*Blocked*/*Enabled*) Enable or block this user.
- **Require Password Reset** (*Yes*/*No*) If set to yes, the user will
  have to reset their password the next time they log into the site.
- **ID** Record number in the database.

### Assigned User Groups

![user edit assigned user groups tab](../../../en/images/users/users-edit-assigned-user-groups-tab.png)

### Basic Settings

![user edit basic settings tab](../../../en/images/users/users-edit-basic-settings-tab.png)

- **Backend Template Style** (*Use Default*/*Hathor - Default*/*isis -
  Default*) Select the template style for the Administrator Backend
  interface. This will only affect this User.
- **Backend Language** (*Use Default*/*English (United Kingdom)*)
  Select the Language for the Administrator Backend interface. This will
  only affect this User.
- **Frontend Language** (*Use Default*/*English (United Kingdom)*)
  Select the Language for the frontend interface. This will only affect
  this User.
- **Editor** Select an Editor for this user. The default is TinyMCE unless 
  changed in the Global Configurations. 
- **Time Zone** There is a long list of time zones to choose from organised by
  continent with Europe near the end. The site default time zone is set in the
  Global Configurations.

### Accessibility Settings

![user edit accessibility settings tab](../../../en/images/users/users-edit-accessibility-settings-tab.png)

- **Monochrome** Yes/No
- **High Contrast** Yes/No
- **Highlight Links** Yes/No
- **Increase Font Size** Yes/No

### User Actions Log Options

This tab is available for Super Users only!

- **Send notifications for User Actions Log** (*Yes/No*) If set to yes,
  the User will receive user actions log notification by email
- **Select events to be notified for** Select the user actions log
  notifications to be sent by email.

### W3C Web Authentication (WebAuthn) Login

This tab is only present when the site is accessed using https. To set
up passwordless login you need a hardware device, available from Amazon
and similar outlets for about £15, or a device with fingerprint or face
recognition or similar biometric software. You may add more than one
authenticator. Once set up, you can login by clicking the Web
Authentication button in the Login form and then pressing the button on
the device when prompted.

This tab is present but cannot be used in the User edit form because
passwordless login can only be set up by the individual user via the
Edit Profile form.

### Joomla API Token

This tab is used to manage the security tokens used for authenticating
to the Joomla API application (remote access to your site). If you are
not sure what this does chances are you don't need it and can safely
ignore these settings.

The token is only visible for your own account.

### Multi-factor Authentication

![user edit multi factor authentication tab](../../../en/images/users/users-edit-multi-factor-authentication-tab.png)

This tab allows you to set one or more methods to allow access to your
account after login with Username and Password. It is only present when
editing your own profile. There are several methods available. If you
lose access to one method for any reason you can choose another method
from the post-login verification screen. The alternative mthods must
have been set up in advance!

#### Backup Codes

This method generates a set of numbers that you can save or print. Each
number can be used only once, so remember to amend your list after use.

#### Verification code

An extra form to fill out with alternative methods of setting up the
code. Have a look and click the Cancel button if you decide not to
proceed.

#### Yubi Key

This is for another type of hardware key that provides a code on a
screen display. Have a look and select Cancel if you decide not to
proceed.

#### Web Authentication

For a hardware device with a button to press. Have a look and select
Cancel if you decide not to proceed. Note that this method will be
bypassed if you use the separate WebAuthn Login method.

#### Code by Email

With this method a code is sent to your email address. You will be
prompted to enter that code to gain site access. It is a one-time code.
A new one is sent for every login. Have a look and select Cancel if you
decide not to proceed.

## Tips

- Name, Login Name, and Email are required.
- If you did not fill in a particular language, editor, help site and/or
  time zone, the default settings from the Global Configuration,
  Language Manager and/or Template Manager are set.
