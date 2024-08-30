<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Patch Tester Options -->

## Description

The Joomla! Patch Tester is used by Testers to check that code patches
produced by Developers actually do what they are supposed to do without
unwanted side effects. The Options page is used to set up the Github
connection.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

More Information: [A Dummies Guide to Joomla Bug Testing](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## How to Access

- Select **Components → Patch Tester** from the Administrator menu.
  - Click the *Options* button on the Toolbar.

## Screenshot

![Patchtester Options form](../../../en/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Form Fields

### GitHub Repository Tab

- **GitHub Repository** The default is Joomla! CMS. Use it.

### Github Authentication Tab

You need a Github account and a Github Token. All free - see the GitHub
Authentication Tab for details.

![Patchtester Options github authentication tab](../../../en/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **GitHub Authentication Method** Choose the Token method. The
  Credentials method will not work from September 2020.
- **GitHub Token** Paste in the Token obtained from GitHub.

### CI Server Settings Tab

These settings are used for automated testing. Use the defaults for
manual testing

![Patchtester Options github ci server settings tab](../../../en/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **CI Server Address** Default: `https://ci.joomla.org`
- **Switch CI Integration** Default: Off

