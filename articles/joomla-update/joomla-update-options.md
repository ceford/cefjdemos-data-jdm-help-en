<!-- Filename: Help4.x:Joomla_Update:_Options / Display title: Joomla Update: Options -->

## Description

The Joomla Update: Options page is used to set parameters to control the 
Joomla core update process.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars)

## How to Access

- Select **System → Update panel → Joomla** from the Administrator menu. Then...
  - Select the **Options** button in the Toolbar.

## Screenshot

![Joomla Update Options Update Source](../../../en/images/joomla-update/joomla-update-options.png)

## Form Fields

### Update Source Tab

- **Update Channel**
  - **Default** This setting causes Joomla to display a notice when a new 
  minor or patch version is available for the current major version. 
  - **Joomla Next** This setting causes Joomla to display a notice when a 
  new stable major version is available and all existing minor versions and
  extensions are up to date.
  - **Custom URL** For Joomla Developers. More fields will appear.
- **Minimum Stability** The minimum stability of the extension updates
  you would like to see. Development is the least stable, Stable is
  production quality. If an extension doesn't specify a level it is
  assumed to be Stable.
  - **Development** For Joomla Developers sites.
  - **Alpha** For Alpha testing sites.
  - **Beta** For Beta testing sites.
  - **Release Candidate** For Release Candidate sites.
  - **Stable** For Production sites.
- **Custom URL** If a Custom URL was selected in the Update Channel a field to enter the URL appears here.
- **Potentially incompatible extensions checkbox** Shows the checkbox in the 
  pre–update check if any of the extensions installed on your site is 
  potentially incompatible with the version of Joomla you are upgrading to. 
  *Note:* the checkbox is displayed when upgrading to a new Joomla version 
  family (minor or major version).
- **Confirm Backup Checkbox** Shows the checkbox to confirm you have taken 
  a backup and you are ready to update in the final step before the update is 
  actually applied. 

### Automated Updates tab

***Automated Updates are available from Joomla 5.4 onwards for sites that are publicly accessible on the internet. If your site is behind a firewall or not publicly accessible, such as a local test environment, you will need to update manually.***

![Joomla Update Options Update Source](../../../en/images/joomla-update/joomla-update-options-automated-updates.png)

- **Automated Update** When set to *Yes* your site will update automatically to the latest minor or patch release (including security patches) as soon as it becomes available. Major releases are not included.
- **Update Token** This is a token that identifies this site. It is created by the remote Joomla update server and cannot be changed by the user.
- **Last Checked** The most recent date your site contacted the update server.
- **Send Email to User Groups** All users in the selected groups will receive emails about successful or failed Automated Updates. If no users are found, the emails are sent to all Super Users. Recipients must have the Receive System Emails option enabled.

Please use the *Toggle Inline Help* button for more details.
