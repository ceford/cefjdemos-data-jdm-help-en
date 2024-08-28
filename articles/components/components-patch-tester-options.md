<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Patch Tester Options -->

## Description

The Joomla! Patch Tester is used by Testers to check that code patches
produced by Developers actually do what they are supposed to do without
unwanted side effects. The Options page is used to set up the Github
connection.

More Information:

- <a
  href="https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing"
  class="external text" target="_blank"
  rel="nofollow noreferrer noopener">A Dummies Guide to Joomla Bug
  Testing</a>

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Components → Patch Tester** from the Administrator menu.
  - Click the *Options* button on the Toolbar.

## Screenshot

<img
src="https://docs.joomla.org/images/a/a3/Help-4x-Component-Patch-Tester-Options-screenshot-en.png"
decoding="async" data-file-width="800" data-file-height="290"
width="800" height="290"
alt="Component Patch Tester Options screenshot" />

## Form Fields

### GitHub Repository Tab

- **GitHub Repository** The default is Joomla! CMS. Use it.

### Github Authentication Tab

You need a Github account and a Github Token. All free - see the GitHub
Authentication Tab for details.

<img
src="https://docs.joomla.org/images/5/5c/Help-4x-Component-Patch-Tester-Options-github-authentication-subscreen-en.png"
decoding="async" data-file-width="600" data-file-height="459"
width="600" height="459"
alt="Component Patch Tester Options github authentication subscreen" />

- **GitHub Authentication Method** Choose the Token method. The
  Credentials method will not work from September 2020.
- **GitHub Token** Paste in the Token obtained from GitHub.

### CI Server Settings Tab

These settings are used for automated testing. Use the defaults for
manual testing

<img
src="https://docs.joomla.org/images/7/7c/Help-4x-Component-Patch-Tester-Options-ci-server-settings-subscreen-en.png"
decoding="async" data-file-width="600" data-file-height="257"
width="600" height="257"
alt="Component Patch Tester Options ci server settings subscreen" />

- **CI Server Address** Default:
  <a href="https://ci.joomla.org" rel="noreferrer noopener">https://ci.joomla.org</a>
- **Switch CI Integration** Default: Off.

