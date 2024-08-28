<!-- Filename: Help4.x:Joomla_Update / Display title: Joomla Update -->

## Description

This page allows Joomla! to be updated using an update package from the Joomla! 
code repository. It is best and safest to let Joomla update itself using this
method.

## How to Access

In the **Home Dashboard → Notifications Panel** the Joomla icon will have
one of two messages:
- **Joomla is up to data**
- **X.Y.Z Available - Update now!**
Select the icon

Also, in the **System → Update Panel → Joomla** will display a tick, meaning it
is up to date, or a version number, meaning that a new version is available.

## Screenshot

If your site is up to date you will see this screen:

![Upload & Update](../../../en/images/joomla-update/upload-update-up-to-date.png)

If an update is available you will see this screen:

![Upload & Update](../../../en/images/joomla-update/upload-update-available.png)

If updating a major or minor version you will see a pre-update check screen:

![pre update check](../../../en/images/joomla-update/upload-update-pre-update-check.png)

Select each of the three menu items to see if anything needs attention.

## Start Update

If you are not on the latest version of Joomla, you can install the
latest update from this page. To do so make sure you have taken a backup
and check the **I am aware...** checkbox to indicate you have done so. Then
select the **Start Update** button and Joomla will install the latest version.

The update screen shows a progress while the update is in progress.

### Upload and Update

You can use this button to update Joomla if your server is behind a
firewall or otherwise unable to contact the update servers. First
download the Joomla Upgrade Package in ZIP format from the official
Joomla download page.

You must have your PHP *upload_max_filesize* and *post_max_size* set to 64Mb
and your PHP memory limit set to 256 Mb. Otherwise the update may fail. One
good reason for taking that backup!

![upload and install](../../../en/images/joomla-update/upload-update-upload-install.png)

## Update Options

The Toolbar Options button allows you to select the type of update:

- **Default** This is used for sites set to stay with the installed version.
- **Joomla Next** This is used for sites that normally move to the next major
  version as soon as a stable version is released.
- **Custom URL** For Developers to select an update source.

