<!-- Filename: Help4.x:Templates:_Customise / Display title: Templates: Customise -->

## Description

This is where you edit a template's source code. You can edit the
template's master files and stylesheets from this screen.

## How to Access

- Select **System → Templates Panel → Site Templates** from the
  Administrator menu. Or...
- Select **System → Templates Panel → Administrator Templates**
  from the Administrator menu. Then...
  - Select a template name from the **Templates** column.

## Screenshot

The Administrator and Site Templates screens use the same layout. The
Site Template screen is illustrated here.

![templates customise cassiopeia editor tab](../../../en/images/templates/templates-customise-cassiopeia-editor-tab.png)

## Form Fields

### Editor Tab

- Select a file to edit. The edit area shows syntax highlighted text for
  most types of file.

### Create Overrides Tab

![templates customise cassiopeia create overrides tab](../../../en/images/templates/templates-customise-cassiopeia-create-overrides-tab.png)

- Select an item to override. Items marked with a solid file icon open to
  reveal a list of items. Items marked with superimposed open and filled page
  icons create an override immediately with no prompt for confirmation. The
  override is placed in the appropriate location. There is a confirmation
  message, for example:
  Override created in /templates/cassiopeia/html/mod_whosonline

### Updated Files Tab

![templates customise cassiopeia updated tab](../../../en/images/templates/templates-customise-cassiopeia-updated-files-tab.png)

If there have been no updates to the template since overrides were
created this tab will contain a simple message:

<div class="alert alert-success">
Overridden files are up to date. Nothing has been changed
in the last extension or Joomla update.
</div>

If there have been updates, a table will show a list of overrides that
need to be reviewed.

### Template Description Tab

![templates customise cassiopeia template description tab](../../../en/images/templates/templates-customise-cassiopeia-template-description-tab.png)

- **Thumbnail and Description** Information on this template.

## Toolbar

Note that the Toolbar buttons change when a file is selected for editing.

### No file selected

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Create Child Template** Select to make a complete a new child
  template. You will be prompted for a new child template name. There is
  also an opportunity to Close without creating a new child template. To
  remove the new child template: select the **Close** button, select the
  Styles button in the Templates list Toolbar, check the template check
  box for the new child template and select Delete in the toolbar.
- **Template Preview** Select to open the Site default view using this
  template.
- **Manage Folders** Select to create a new folder within the template
  hierarchy. A popup window appears. **Important:** select the folder in
  which the new folder is to appear before creating the new folder.
- **New File** Select to create a new file or to upload a file from
  your computer to your Joomla! template hierarchy. A popup window
  appears. **Important** Select the folder in which the new file is to appear
  before creating the new file.
- **Check Overrides** Activated when an Override is selected in the
  *Overrides* tab. The options are:
  - Mark Checked
  - Mark Unchecked
  - Remove Record
- **Close** Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Help** Opens this help screen.

### File selected

- **Save** Saves the item and stays in the current screen.
- **Save & Close** Saves the item and closes the current screen.
- **Rename File** Select a file to edit. Select the Rename button to
  prompt for a new name.
- **Delete File** You will be prompted to Confirm or Cancel.
- **Check Overrides** Activated when an Override is selected in the
  *Overrides* tab.
- **Close File** Closes the open file and returns to the Editor Tab.
- **Help** Opens this help screen.

## Tips

- Before editing the HTML and the CSS file of the template, it is a good
  idea to make a backup of the file you are editing. Also, you can edit
  these files outside of Joomla! using the HTML or CSS editor of your
  choice.
