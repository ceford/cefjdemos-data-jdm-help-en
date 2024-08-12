<!-- Filename: Help4.x:Joomla_Update:_Options / Display title: Joomla Update: Options -->

## Description

The Joomla Update: Options page is used to set parameters to control the 
Joomla core update process.

### Common Elements

Some aspects of the *Joomla Update: Options* page are covered in separate Help
articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars)

## How to Access

- Select **System → Update panel → Joomla** from the
  Administrator menu. Then...
  - Select the **Options** button on the Toolbar.

## Screenshot

![Joomla Update Options](../../../en/images/joomla-update/joomla-update-options.png)

## Form Fields

### Update Source Tab

- **Update Channel**
  - **Default.** This setting causes Joomla to display a notice when a new 
  minor or patch version is available for the current major version. 
  - **Joomla Next.** This setting causes Joomla to display a notice when a 
  new stable major version is available and all existing minor versions and
  extensions are up to date.
  - **Testing.** For Joomla Testers. More fields will appear.
  - **Custom URL.** For Joomla Developers. More fields will appear.
- **Minimum Stability** The minimum stability of the extension updates
  you would like to see. Development is the least stable, Stable is
  production quality. If an extension doesn't specify a level it is
  assumed to be Stable.
  - **Development.** For Joomla Developers sites.
  - **Alpha.** For Alpha testing sites.
  - **Beta.** For Beta testing sites.
  - **Release Candidate.** For Release Candidate sites.
  - **Stable.** For Production sites.
- **Potentially incompatible extensions checkbox** Shows the checkbox in the 
  pre–update check if any of the extensions installed on your site is 
  potentially incompatible with the version of Joomla you are upgrading to. 
  Note: the checkbox is displayed when upgrading to a new Joomla version 
  family (minor or major version).
- **Confirm Backup Checkbox**  Shows the checkbox to confirm you have taken 
  a backup and you're ready to update in the final step before the update is 
  actually applied. 
