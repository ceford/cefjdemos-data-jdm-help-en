<!-- Filename: Help4.x:Extensions:_Update / Display title: Extensions: Update -->

## Description

This screen allows you to update installed extensions that provide an
update server. Live update of the extension occurs without the need to
manually upload and install the updated extension files. They are
obtained from the remote update server using standard HTTP connection
methods.

## How to Access

- Select **System → Update Panel → Extensions** from the
  Administrator menu. Then to perform an update...
  - Select the checkbox of one or more items to update.
  - Select the **Update** button in the Toolbar.

## Screenshot

<img
src="https://docs.joomla.org/images/d/d7/Help-4x-extensions-extension-manager-update-en.png"
decoding="async" data-file-width="800" data-file-height="363"
width="800" height="363"
alt="extensions update" />

## Column Headers

- **Checkbox**. Check this box to select one or more items. To select
  all items, check the box in the column heading. After one or more
  boxes are checked, click a toolbar button to take an action on the
  selected item or items. Many toolbar actions, such as Publish and
  Unpublish, can work with multiple items. Others, such as Edit, only
  work on one item at a time. If multiple items are checked and you
  press Edit, the first item will be opened for editing.
- **Name.** The name of the extension.
- **Location.** Specifies if this is a site or administrator extension.
- **Type.** The extension type. Examples of extension types are module,
  plug-in, template, component, language or package.
- **Installed.** The version number of the currently installed
  extension.
- **Available.** The version number of the available update.
- **Changelog.** The changelog.
- **Folder.** If the extension is a plug-in, the subdirectory of your
  Joomla! installation's /plugins directory where the extension is
  located. By default Joomla! has the following subdirectories in the
  plugins directory which each represent the different types of plug-ins
  that are defined: authentication, content, editors, editors-xtd,
  extension, search, system, user.
- **Install Type.** The type of installation that will be performed by
  the update. Usually this will be type ***Update*** which will perform
  an in-place update of the extension.

## List Filters

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Filter Options**. Click to display the additional filters.
- **Clear**. Click to clear the Filter field and restore the list to its
  unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of items in a list. Select
  from the dropdown list to change the number displayed.The default for
  a site is '20' but this may be changed in the Global Configuration.

### Filter Options

- **-Select Location-.** Select Site, Administrator or API from the
  drop-down list of available locations.
- **-Select Type-.** Select the extension type from the drop-down list
  box of available types.
- **-Select Folder-.** Select a plug-in folder from the drop-down list
  box of available folders. There is a separate folder for each type of
  plug-in defined in your Joomla installation.

**Page Controls**. When the number of items is more than one page, you
will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Update.** Perform update of selected options. This will fetch an
  update file from the update server and may take several seconds.
  Please be patient!
- **Find Updates.** Query update servers for the latest versions of
  installed extensions. Again, this may take a while.
- **Clear Cache.** Clear the available extension update information
  displayed in the listing.
- **Options.** Opens the Options window where settings such as default
  parameters can be edited.
- **Help**. Opens this help screen.

## Quick Tips

- Only extensions which support the Joomla! update system will be listed
  in this screen. If you use extensions which do not support the new
  update system or you are not sure, consult the extension developer's
  website.
- It is critical to keep your extensions up-to-date. Failure to do so
  may expose a vulnerability in your Joomla! installation which can be
  exploited by hackers.
- It is recommended to backup your Joomla! installation files and
  database before attempting to update extensions or the Joomla!
  installation itself. This will ensure that you can restore your
  Joomla! installation to its previous state if the update fails or
  causes unexpected results.
