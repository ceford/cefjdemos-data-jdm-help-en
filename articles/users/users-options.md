<!-- Filename: Help4.x:Users:_Options / Display title: Users: Options -->

## Description

The *Users: Options* page is used to set set global options for all users, 
including:

- Captcha,
- registration allowed and type of registration,
- default user group for new users,
- reset password or username counter,
- new user registration email notice to administration and more.

## How to Access

* Select **Site → Users** from the *Home Dashboard*. Or...
* Select **Users → Manage** from the Administrator menu. Then...
* Select the **Options** toolbar button

## Screenshot

![users options user options tab](../../../en/images/users/users-options-user-options-tab.png)

## Form Fields

### User Options tab

- **Allow User Registration**
  - *Yes* Users can register from the Frontend of the site using the
    *Create an Account* link provided in the Login form.
  - *No* The *Create an Account* link will not show.
- **New User Registration Group** The group that users are assigned to by
  default when they register on the site. Defaults to *Registered*.
- **Guest User Group** The group that guests are assigned to (Guests
  are visitors to the site who are not logged in). It is possible to
  create content on the site that is visible to guests but not visible
  to logged in users.
- **Send Password** If set to *Yes* the user's first password will be
  emailed to the user as part of the registration mail.
- **New User Account Activation**
  - *None* User account will be active immediately with no action required.
  - *Self* User will receive an email with an activation link. The
    account will be activated when the user selects the activation link.
  - *Administrator* User will receive an email with an activation link.
    When the user selects this link, the Site Administrator will be notified via
    email and asked to activate the user's account.
- **Send Mail to Administrators** Send email notification to
  administrators with *New User Account Activation* set to *None* or *Self*.
- **Captcha** The Captcha plugin for User Account Registration, User Password 
  reminder and Username reminder.
- **Frontend User Parameters**
  - *Show* Users will be able to modify Basic Settings from the site Frontend.
  - *Hide* User will not be able to change these settings.
- **Frontend Language** Show or Hide the site language. ...
- **Change Username** Allow user to change Username.

### Email Domain Options tab

![users options email domains tab](../../../en/images/users/users-options-email-domain-options-tab.png)

- **Domain Name** Enter a list of allowed and disallowed email domains.
  By default, all domains are allowed. Wildcards (\*) are supported. For
  example:
  - \* (Asterisk): Allows or disallows all domains
  - \*.com: Allows or disallows all '.com' domains
  - \*.joomla.org: Allows or disallows all 'joomla.org' subdomains.
- **Rule** Select whether to allow or disallow the domain.

### Password Options tab

![users options password options tab](../../../en/images/users/users-options-password-options-tab.png)

- **Maximum Reset Count** The maximum number of password resets allowed
  within the time period. Zero indicates no limit.
- **Reset Time** The time period, in hours, for the reset counter.
- **Minimum Length** Set the minimum lenth for a password.
- **Minimum Integers** Set the minimum number of integers that must be
  included in a password.
- **Minimum Symbols** Set the minimum number of symbols (such as !@#\$)
  required in a password.
- **Minimum Upper Case** Set the minimum number of upper case
  alphabetical characters required for a password.
- **Minimum Lower Case** Set the minimum number of lower case
  alphabetical characters required for a password.

### Multi-factor Authentication tab

![users options multi factor authentication tab](../../../en/images/users/users-options-multi-factor-authentication-tab.png)

- **Allowed frontend module positions** When displaying the frontend
  Multi-factor Authentication page all modules will be hidden except
  those in the positions selected here.
- **Show title in frontend** Display a title in the frontend
  Multi-factor Authentication verification page? Please note that the
  title is always displayed in the backend. If you need to change the
  title please override the language key `COM_USERS_HEADING_MFA` using
  Languages: Overrides.
- **Allowed backend module positions** When displaying the backend
  Multi-factor Authentication page all modules will be hidden except
  those in the positions selected here. Please note that modules in the
  `title` position are always shown: this is required to show the
  backend page icon and title.
- **Disable Multi-factor Authentication** Any user who belongs in *any*
  of the selected user groups will be exempt from Multi-factor
  Authentication. Even if they have set up Multi-factor Authentication
  methods they will not be asked to use them when they are logging in,
  nor will they be able to view them, remove them, or change their
  configuration.
- **Enforce Multi-factor Authentication** Any user who belongs in *any*
  of the selected user groups will be required to enable Multi-factor
  Authentication before being able to use the site.
- **Frontend template style** Choose the frontend template style to use
  in the Multi-factor Authentication page. Select *Use Default* to use
  the default site template style.
- **Multi-factor Authentication after silent login** Should the user
  have to go through Multi-factor Authentication after a silent user
  login? Silent logins are those which do not require a username and
  password for example the Remember Me feature, WebAuthn etc.
- **Silent login authentication response types (for experts)** For
  experts. A comma separated list of Joomla authentication response
  types which are considered silent logins. The default is `cookie` (the
  Remember Me feature) and `passwordless` (WebAuthn).
- **Onboard new users** If the user has not yet set up Multi-factor
  Authentication and this option is enabled they will be redirected to
  the Multi-factor Authentication setup page or the custom URL you set
  up below. This is meant to be a simple way to to let your users know
  that Multi-factor Authentication is an option on your site.
- **Custom redirection URL** If it's not empty, redirects to this URL
  instead of the Multi-factor Authentication setup page when the option
  above is enabled. Warning: This must be a URL inside your site. You
  cannot log in to an external link or to a different subdomain.

### User Notes History tab

![users options user notes history tab](../../../en/images/users/users-options-user-notes-history-tab.png)

- **Enable Versions** Save version history for User Notes.
- **Maximum Versions** The maximum number of versions to store for a
  User Note. If a User Note is saved and the maximum number of versions
  has been reached, the oldest version will be deleted automatically. If
  set to 0, then versions will never be deleted automatically.

### Mass Mail Users tab

![users options mass mail users tab](../../../en/images/users/users-options-mass-mail-users-tab.png)

- **Subject Prefix** Enter optional text to be inserted automatically
  before the subject of the mass email.
- **Mailbody Suffix** Enter optional text to be inserted automatically
  after the body of the email (for example, a signature).

### Integration tab

![users options integration tab](../../../en/images/users/users-options-integration-tab.png)

- **Enable Custom Fields** Enable the creation of custom fields.

## Tips

If you are a novice user, keep the default values here
until you learn more about using global options.
