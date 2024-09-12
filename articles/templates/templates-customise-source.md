<!-- Filename: Help4.x:Templates:_Customise_Source / Display title: Templates: Customise Source -->

<div class="alert alert-warning">
This page appears in the index of Help pages but is not used via a Help button.
This is a bug that is likely to be corrected.
</div>

## Description

The *Templates: Customise Source* page is where the source code of template 
files is edited. It provides a plain text interface to edit the template files. 
HTML and PHP programming syntax is highlighted to make the source code files 
easier to read. In the Title bar the word *Source* appears as the name of the
template, for example *(Cassiopeia)*.

## How to Access

- Select **System → Templates Panel → Site Templates** from the
  Administrator menu. Or...
- Select **System → Templates Panel → Administrator Templates**
  from the Administrator menu. Then...
  - Select a template name from the **Templates** column. Then...
    - Select a file to edit from the Editor tab.

## Screenshot

![Templates customise cassiopeia editor tab](../../../en/images/templates/templates-customise-cassiopeia-edit-component-editor-tab.png)

## Form Fields

### Editor Tab

- Select a file to edit. The edit area shows syntax highlighted text for
  most types of file.

### Create Overrides Tab

- Select an item to override. If a folder is selected it is expanded to display
  a list of files. If a file is selected it is immediately copied to the html 
  folder with no prompt for confirmation. The override is placed in the 
  appropriate location. There is a confirmation message, for example: 
  *Override created in /templates/cassiopeia/html/mod_whosonline*.

### Updated Files Tab

If there have been no updates to the template since overrides were
created this tab will contain a simple message:

- **Notice** Overridden files are up to date. Nothing has been changed
  in the last extension or Joomla update.

If there have been updates, a table will show a list of overrides that
need to be reviewed.

### Template Description Tab

- **Thumbnail and Description** Information on this template.

## Toolbar

The Toolbar icons change with the action being taken. You may see:

- **Save** Saves the item and stays in the current screen.
- **Save & Close** Saves the item and closes the current screen.
- **Copy Template** Copies the current template. A dialogue box prompts
  for a new name.
- **Template Preview** Select to open the Site in a new browser tab.
- **Manage Folders** Allows creation and deletion of template folders
  using a dialogue box.
- **New File** Allows upload of a file from your computer to the
  template file hierarchy using a dialogue box.
- **Rename File** Select a file to edit. Select the Rename button to
  prompt for a new name.
- **Delete File** You will be prompted to Confirm or Cancel.
- **Close File** Closes the open file and returns to the Editor Tab.
- **Help** Opens this help screen.

## Tips

- Important: Do not delete the default template files using FTP because
  it generates an error in both the frontend and backend.
- Before editing the HTML and the CSS file of the template, it is a good
  idea to make a backup of the file you are editing. Also, you can edit
  these files outside of Joomla! using the HTML or CSS editor of your
  choice.
