<!-- Filename: Help4.x:Plugins:_Name_of_Plugin / Display title: Plugins: Name of Plugin -->

## Description

The Plugin screen allows you to edit the details and options of a
plugin. Common options for all plugins are located in the right hand
part of the Plugin Tab and described below.

Plugins by Group:

- **Action Log Group.** (1
  Plugin)
- **API Authentication Group.** (2
  Plugins)
- **Authentication Group.** (3
  Plugins)
- **Behaviour Group.** (2
  Plugins)
- **CAPTCHA Group**. (2
  Plugins)
- **Content Group.** (1
  Plugin)
- **Editors Group.** (3
  Plugins)
- **Editor Button Group.** (8
  Plugins)
- **Extensions Group.** (3
  Plugins)
- **Fields Group.** (6
  Plugins)
- **FileSystem Group.** (1
  Plugin)
- **Finder Group.** (5
  Plugins)
- **Installer Group.** (5
  Plugins)
- **Media Action Group.** (3
  Plugins)
- **Privacy Group.** (6
  Plugins)
- **Quick Icon Group.** (6
  Plugins)
- **Sample Data Group.** (2
  Plugins)
- **System Group.** (22
  Plugins)
- **Two Factor Authentication Group.** (2
  Plugins)
- **User Group.** (5
  Plugins)
- **Web Services Group.** (5
  Plugins)
- **Workflow Group.** (3
  Plugins)

The complete list of plugin groups above is available in one long
document: **List of
Plugins**.

## How to Access

Starting from the Administrator menu:

- Select **Home Dashboard → Plugins**. Or..
- Select **System → Manage panel → Plugins**. Then...
  - Select the Plugin's Name in the list of plugins.

## Screenshot

<img
src="https://docs.joomla.org/images/4/41/Help-4x-Extensions-Plugin-Manager-Edit-screen-en.png"
decoding="async" data-file-width="800" data-file-height="469"
width="800" height="469"
alt="Plugins by group screen" />

## Form Fields

### Plugin Tab

#### Left Panel

If the plugin has configurable options they will appear here. The
example shown in the Screenshot is the *Content - Confirm Consent*
plugin which has several configurable parameters which change as options
are selected.

#### Right Panel

The right panel is the same for all plugins and has the following
fields:

- **Status.** Whether or not the item is enabled.
- **Access.** Which user 'access levels' have access to this item. You
  can change an item's Access Level by clicking on its name to open it
  up for editing. The default user 'access levels' which come
  preconfigured with Joomla! are:
  - Public: Everyone has access including website visitors who have not
    logged in
  - Registered: Only users with registered status or higher will have
    access
  - Special: Only users with author status or higher have access
- **Ordering.** A drop-down list of plugins of the same Type. The list
  of plugins is arranged by their current order. You can change this
  plugin's order in relation to the other plugins by selecting the
  plugin in the drop-down list that you want this plugin to be ordered
  below.
- **Plugin Type.** The Type of the Plugin. This value cannot be changed.
- **Plugin File.** The name of the Plugin file. Each Plugin has two
  files with this name. One has the file extension '.php' and the other
  has the file extension '.xml'.
- **Description.** The description of what this Plugin does. This cannot
  be changed. The developer of the plugin specifies this. This may be
  blank if the developer did not specify a description for the plugin.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Help**. Opens this help screen.

## Quick Tips

- If you are using the TinyMCE editor, you can control which options
  appear on the editor's toolbar by setting the parameters in the
  "Editor - TinyMCE" plugin.
- Configurable plug-in settings are referred to as 'options'. In
  previous versions of Joomla! these configurable settings were referred
  to as 'parameters'. You may see the terms 'options' and 'parameters'
  used interchangeably in help documentation and tutorials you
  encounter.
