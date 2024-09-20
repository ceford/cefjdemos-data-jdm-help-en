<!-- Filename: Help4.x:Components_Version_History / Display title: Edit Version History -->

## Description

A Version History popup shows prior versions of the item being edited. It is
available for Articles, Banners and Clients, Contacts, News Feeds, User Notes
and all Categories.

Each time an item is saved a new version is created automatically. The number
of versions to keep for each item is set in the component Options. One or
more versions can be marked to keep forever. Such versions will not be deleted
automatically even if the maximum number of versions entered in the options
is exceeded.

**Note:** If versioning is used, custom fields are not stored in different versions.

## How to Access

Select the **Versions** button in the Toolbar of an item edit page.

## Screenshot

![Version history popup](../../../en/images/common-elements/articles-edit-versions.png)

## Column Headers

- **Checkbox** Check this box to select one or more items. To select all
items, check the box in the column heading. After boxes are checked,
select a toolbar button to take an action on the selected items.
- **Date** The time and date that the version was saved. Selecting this
link opens the Preview of that version in a pop-up window. Note that one
of the dates will be followed by a star symbol. This indicates that this
is the version that is currently saved and being edited.
- **Version Note** A Version Note can be used to help identify the nature of the
changes from one version to the next. A Version Note entered before saving an
item will show in this column.
- **Keep Forever** This column shows whether the version has been marked to
Keep Forever. Normally, each version will be retained according to
the settings in the component options page. The default settings are
to keep a maximum of 10 prior versions for an item. When an item is saved that
already has 10 saved versions, the oldest version is deleted. If a version is
marked as Keep Forever it will not be counted as one of the saved versions and
will not be deleted when the maximum number is reached.
  - To toggle the Keep Forever state on or off select a *No* or *Yes* button or select
  the version's check box and then select the Keep On/Off button in the toolbar.
- **Author** The user who saved this version.
- **Character Count** The total characters saved in this version. Note
that this includes the database column names as well as the actual
characters typed in.

## Toolbar

- **Restore** The current version of the item is marked with a star to
the right of the Date. To restore one of the other saved
versions, check the check box for the desired version and select the
Restore button. The current version of the item will be replaced with
the selected version, and the edit screen will reload with the restored
version loaded in the editor.
- **Preview** To preview a version, either select the Date column for the desired
version or select the check box and then the Preview button. A separate popup
window will load showing the selected version of the item.
- **Compare** To compare two versions to see what was changed, select the
check boxes for each of the versions and then the Compare button. A
new browser window will open showing a list of changed fields and the changes
made in those fields.
  - The first column is the field name, the second is the older version, the
third is the newer version, and the last column highlights the
differences between the two versions.
- **Keep On/Off** This button toggles on or off the Keep Forever feature for a
version. Normally, the oldest version of an item will be deleted automatically
when the maximum number of versions (set in the Options for the component) has
been exceeded. If you set the Keep Forever property for a version, it will
never be automatically deleted.
- **Delete** This button allows manual deletion of one or more versions. Check
the check box for the versions to be deleted and then select on the Delete
button. Note that this does *not* delete the item being edited. It only deletes
the version history for the item.
