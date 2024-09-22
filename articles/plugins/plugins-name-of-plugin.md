<!-- Filename: Help4.x:Plugins:_Name_of_Plugin / Display title: Plugins: Name of Plugin -->

## Description

The *Plugin* page provides access to edit the details and options of a all
plugins. Common options for all plugins are located in the right hand
part of the *Plugin tab* described below.

### Plugins Groups

There are a large number of core plugins available. They are listed here by
group with links to separate documentation:

* [Action Log Group.](jdocmanual?article=help/plugins/plugin-group-action-logs) (1 Plugin)
* [API Authentication Group.](jdocmanual?article=help/plugins/plugin-group-api-authentication) (2 Plugins)
* [Authentication Group.](jdocmanual?article=help/plugins/plugin-group-authentication) (3 Plugins)
* [Behaviour Group.](jdocmanual?article=help/plugins/plugin-group-behavior) (3 Plugins)
* [Content Group.](jdocmanual?article=help/plugins/plugin-group-content) (10 Plugins)
* [Editors Group.](jdocmanual?article=help/plugins/plugin-group-editors) (3 Plugins)
* [Editor Xtd Button Group.](jdocmanual?article=help/plugins/plugin-group-editors-xtd) (8 Plugins)
* [Extensions Group.](jdocmanual?article=help/plugins/plugin-group-extensions) (3 Plugins)
* [Fields Group.](jdocmanual?article=help/plugins/plugin-group-fields) (16 Plugins)
* [FileSystem Group.](jdocmanual?article=help/plugins/plugin-group-file-system) (1 Plugins)
* [Finder Group.](jdocmanual?article=help/plugins/plugin-group-finder) (5 Plugins)
* [Installer Group.](jdocmanual?article=help/plugins/plugin-group-installer) (5 Plugins)
* [Media Action Group.](jdocmanual?article=help/plugins/plugin-group-media-action) (3 Plugins)
* Multi-factor Authentication Group (5 Plugins)
* [Privacy Group.](jdocmanual?article=help/plugins/plugin-group-privacy) (6 Plugins)
* [Quick Icon Group.](jdocmanual?article=help/plugins/plugin-group-quick-icon) (7 Plugins)
* [Sample Data Group.](jdocmanual?article=help/plugins/plugin-group-sample-data) (2 Plugins, 3 Plugins for Development installations)
* Schema.org Group (9 Plugins)
* [System Group.](jdocmanual?article=help/plugins/plugin-group-system) (24 Plugins)
* Task Group (9 Plugins)
* [User Group.](jdocmanual?article=help/plugins/plugin-group-user) (5 Plugins)
* [Web Services Group.](jdocmanual?article=help/plugins/plugin-group-web-services) (17 Plugins)
* [Workflow Group.](jdocmanual?article=help/plugins/plugin-group-workflow) (3 Plugins)

The complete list of plugins is available in a
[single long list](https://docs.joomla.org/Chunk4x:List_of_Plugins).

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to Access

Starting from the Administrator menu:

- Select **Home Dashboard → Plugins** Or..
- Select **System → Manage panel → Plugins** Then...
  - Select the Plugin's Name in the list of plugins.

## Screenshot

![Plugins plugin tab](../../../en/images/plugins/plugins-plugin-tab.png)

## Form Fields

### Plugin Tab

#### Left Panel

**Plugin Title** set as a `<h2>` heading.

**type/file** set as *badges* help to locate the plugin files in the source code.

**Description** A brief description of what this Plugin does. It cannot be
changed as it is specified by the developer of the plugin. It may be blank if
the developer did not specify a description for the plugin.

If the plugin has configurable options they will appear here. Many plugins
have no configurable options.

#### Right Panel

The right panel is the same for all plugins and has the following
fields:

- **Status** Whether or not the item is enabled.
- **Access** The user *access levels* for this plugin.
- **Ordering** A drop-down list of plugins of the same Type. The list
  of plugins is arranged by their current order. You can change this
  plugin's order in relation to the other plugins by selecting the
  plugin in the drop-down list that you want this plugin to be ordered
  below.
- **Plugin Type** The Type of the Plugin. This value cannot be changed.
- **Plugin File** The name of the Plugin file. Each Plugin has two
  files with this name. One has the file extension '.php' and the other
  has the file extension '.xml'.

## Tips

- Configurable plug-in settings are referred to as *Options*. You may see the
  terms *Options* and *Parameters* used interchangeably in help documentation
  and tutorials you encounter.
