<!-- Filename: Help4.x:Media:_Options / Display title: Media: Options -->

## Description

The *Media: Options* page is used to set the media global parameters.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Content → Media** from the Administrator menu.
- Select the **Options** button in the Toolbar.

## Screenshot

![Media Options](../../../en/images/media/media-options.png)

## Form Fields

### Media

- **Maximum Size (in MB)** Use zero for no limit. Note: The server has
  a maximum limit.
- **Path to Files Folder** Enter the path to the files folder relative
  to the root of your webspace. Do not start the path with a slash.
  Changing to another path than the default *images* may break your links. 
- **Path to Images Folder** Enter the path to the images folder
  relative to the root of your webspace. Do not start the path with a slash.
- **Restrict Uploads** Restrict uploads for lower than manager users to
  images if `Fileinfo` or `MIME Magic` isn't installed.
  - **Allowed Extensions** Restrict uploads for lower than manager
    users to files in the list.
  - **Check MIME Types** Use `Fileinfo` or `MIME Magic` to attempt to
    verify files. Try disabling this if you get invalid mime type errors.
- **Legal Image Extensions (File Types)** Image extensions (file types)
  you are allowed to upload (comma separated). These are used to check
  for valid image headers and to select images.
- **Legal Audio Extensions (File Types)** Audio extensions (file types)
  you are allowed to upload (comma separated). These are used to check
  for valid audio headers and to select audio files.
- **Legal Video Extensions (File Types)** Video extensions (file types)
  you are allowed to upload (comma separated). These are used to check
  for valid video headers and to select videos.
- **Legal Document Extensions (File Types)** Document extensions (file
  types) you are allowed to upload (comma separated). These are used to
  check for valid document headers and to select documents.
- **Ignored Extensions** Ignored file extensions for MIME type checking
  and restricted uploads.
- **Legal MIME Types** A comma separated list of legal MIME types to upload.

## Tips

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here.
