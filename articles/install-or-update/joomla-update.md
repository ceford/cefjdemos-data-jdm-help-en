<!-- Filename: Help4.x:Joomla_Update / Display title: Joomla Update -->

## Description

This screen allows Joomla! to be updated quickly using an update package
from the Joomla! code repository. It is best and safest to let Joomla update
itself

## How to Access

In the **Home Dashboard → Notifications Panel** the Joomla icon will have
one of two messages:
- **Joomla is up to data**
- **X.Y.Z Available - Update now!**
Select the icon

Also, in the **System → Update Panel → Joomla** will display a tick, meaining it
is up to date, or a version number, meaning that a new version is available.

## Screenshot

If your site is up to date you will see this screen:

![Upload & Update](../../../en/images/install-or-update/upload-update-up-to-date.png "")

If an update is available you will see this screen:

![Upload & Update](../../../en/images/install-or-update/upload-update-available.png "")

If updating a major or minor version you will see a pre-update check screen:

![pre update check](../../../en/images/install-or-update/upload-update-pre-update-check.png "")

Select each of the three menu items to see if anything needs attention.

## Start Update

If you are not on the latest version of Joomla, you can install the
latest update from this screen. To do so make sure you have taken a backup
and check the **I am aware...** checkbox to indicate you have done so. Then
select the **Start Update** button and Joomla will install the latest version.

### The screen while updating

<img
src="https://docs.joomla.org/images/0/05/Help-4x-joomla-update-manager-updating-screen-en.png"
decoding="async" data-file-width="800" data-file-height="173"
width="800" height="173"
alt="joomla update updating in progress screen" />

### Upload and Update

You can use this button to update Joomla if your server is behind a
firewall or otherwise unable to contact the update servers. First
download the Joomla Upgrade Package in ZIP format from the official
Joomla download page.

You must have your PHP *upload_max_filesize* and *post_max_size* set to 64Mb
and your PHP memory limit set to 256 Mb. Otherwise the update may fail. One
good reason for taking that backup!

![upload and install](../../../en/images/install-or-update/upload-update-upload-install.png "")

## For Developers

There are options to select the type of update:

- **Default.** This should be used for production sites.
- **Joomla Next.** For ...
- **Testing.** For ...
- **Custom URL.** For Developers.

Select the **Options** button in the Toolbar to check or change the
current selection.
