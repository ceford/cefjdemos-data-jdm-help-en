<!-- Filename: Help4.x:Extensions_Module_Manager_Weblinks / Display title: Modules: Weblinks -->

## Description

The Weblinks module will display weblinks from within the Weblinks
component.

## How to Access

From the Administrator menu:
* Select **Content / Site Modules**
* To add a new Weblinks module select **New** from the Toolbar.
* To edit an existing Weblinks module select ites **Title** in the module list.

## Screenshot

![weblinks module data entry form](../../../en/images/modules-site/modules-site-weblinks.png)

## Form Fields

- **Title** The title of the module is displayed if the *Show Title* field is
set to *Show*.

## Module tab

### Left Panel

- **Category:** (*Sample Data-Weblinks*/*Park Links*/*Joomla! Specific
  Links*/*Other Resources*/*Uncategorised*). Choose the Weblinks
  category to display
- **Count:** Number of Web Links to display
- **Direction:** (*Ascending*/*Descending*). Set the ordering direction
- **Target Window:** (*Open in new window*/*Open in popup*/*Open in
  parent window*). Target browser window when the link is clicked
- **Follow/No Follow:** (*Follow*/*No follow*). Robots index - allow to
  follow or not
- **Description:** (*Show*/*Hide*). Display Web Link description
- **Hits:** (*Show*/*Hide*). Show Hits
- **Count Clicks:** (*Use Global*/*No*/*Yes*). If set to yes, the number
  of times the link has been clicked will be recorded

### Right panel

- **Show Title.** (Show/Hide) Choose whether to show or hide the modules
  title in the front end. The title will be the one in the Form Field
  above.
- **Position.** Choose the module position
  you wish this module to be displayed in. A custom module position can
  be entered for use with the load position plugin
  or the position button can be pressed to select a module position from
  the template.
- **Status**. The published status of the item.
- **Access**. The viewing Access  Level   for this item.
- **Module Ordering.** This shows a drop down of every module in the
  position that the current module is in. This is the order that the
  modules will display in when displayed on in the front end as well as
  in the Modules page
- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

## Menu Assignment tab

- **Module Assignment.** Select **On All Pages**, **No Pages**, **Only
  on the pages selected** or **On all pages except those selected** from
  the List.
- **Menu Selection.** If the latter two options are selected a list will
  show all of the menu items. This allows you to assign modules to some
  but not all pages, and by selecting the menu links that you want the
  module associated with you can customize on what pages modules
  appear/don't appear. See How do you assign a module to specific
  pages?
  for more information.

## Advanced tab

<img
src="https://docs.joomla.org/images/thumb/f/fc/Help-4x-module-manager-advanced-options-screenshot-en.png/670px-Help-4x-module-manager-advanced-options-screenshot-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fc/Help-4x-module-manager-advanced-options-screenshot-en.png/1005px-Help-4x-module-manager-advanced-options-screenshot-en.png 1.5x, https://docs.joomla.org/images/f/fc/Help-4x-module-manager-advanced-options-screenshot-en.png 2x"
data-file-width="1042" data-file-height="446" width="670" height="287"
alt="weblinks advanced options screenshot" />

- **Layout.** If you have defined one or more alternative layouts for a
  module either in the template or Joomla! Core, you can select the
  layout to use for this module.
- **Module Class.** A suffix applied to the CSS class of the Module.
  This allows you to create customized CSS styles that will apply just
  to this module. You would then modify the "template.css" file of your
  template to apply styling to this new class.
  - Enter this parameter with a leading space to create a new CSS class
    for this module. Enter the parameter without a leading space to
    change the CSS class name for this module.
- **Caching.** Use Global/No Caching. Whether or not to cache the
  content of this Module. A setting of "Use Global" will use the Cache
  Settings from the Global Configuration screen.
- **Cache Time.** The number of seconds for which to cache the item
  locally. It can safely be left at the default.
- **Module Style.** You can use this option to override the templates
  style for its position.
- **Module Tag.** The HTML tag for the module to be placed in. By
  default this is a div tag but other HTML5 elements can also be used.
- **Bootstrap Size.** (Values 0 to 12) This allows you to choose the
  width of the module via the span element built into bootstrap.
- **Header Tag.** The HTML tag to use for the modules header or title.
  This can be an h1, h2, h3, h4, h5, h6 or a p tag. Note that you must
  use a module style (chrome) of *html5* or add your custom module
  styles in \<mytemplate\>*/html/modules.php*.
- **Header Class.** Here you can add optional CSS classes to add to the
  modules header or title element.

## Permissions tab

<img
src="https://docs.joomla.org/images/thumb/2/26/Help-4x-module-manager-menu-permissions-screenshot-en.png/670px-Help-4x-module-manager-menu-permissions-screenshot-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/26/Help-4x-module-manager-menu-permissions-screenshot-en.png/1005px-Help-4x-module-manager-menu-permissions-screenshot-en.png 1.5x, https://docs.joomla.org/images/2/26/Help-4x-module-manager-menu-permissions-screenshot-en.png 2x"
data-file-width="1040" data-file-height="667" width="670" height="430"
alt="weblinks module permissions screenshot" />

- **Delete:** (*Inherited*/*Allowed*/*Denied*). Allow or deny Delete for
  users in the Public group. Delete Allows users in the group to delete
  any content in this extension.
- **Edit:** (*Inherited*/*Allowed*/*Denied*). Allow or deny Edit for
  users in the Public group. Edit Allows users in the group to edit any
  content in this extension.
- **Edit State:** (*Inherited*/*Allowed*/*Denied*). Allow or deny Edit
  State for users in the Public group. Edit State Allows users in the
  group to change the state of any content in this extension.

## Toolbar

At the top left you will see the toolbar:

- **Save:** Saves the module and stays in the current screen.
- **Save & Close:** Saves the module and closes the current screen.
- **Save & New:** Saves the module and keeps the editing screen open and
  ready to create another module.
- **Save as Copy:** Saves your changes to a copy of the current module.
  Does not affect the current module. This toolbar icon is not shown if
  you are creating a new module.
- **Close:** Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help:** Opens this help screen.
