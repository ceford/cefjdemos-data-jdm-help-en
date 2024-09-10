<!-- Filename: Help4.x:Site_Modules:_Menu / Display title: Modules: Menu -->

## Description

This *Menu* module type allows you to place a Menu at the desired
position and on the desired web pages. A web site may have more than one
menu on a single page and different menus on different web pages.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Modules: Modules Tab](jdocmanual?article=help/modules/modules-module-tab).
* [The Modules: Menu Assignment Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [The Modules: Advanced Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **System → Manage Panel → Site Modules** from the
  Administrator menu. Then...
  - To create a new module: select the **New** button from the Toolbar. Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

![menu module tab](../../../en/images/modules-site/modules-menu-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Select Menu** Select a menu from the list of available menus.
- **Base Item** Select a menu item
  to be used always as the base for the menu display. You must set the
  Start Level to the same level or higher than the level of the base
  item. This will cause the module to be displayed on all assigned
  pages. If Current is selected the currently active item is used as the
  base. This causes the module to display only when the parent menu item
  is active.
- **Start Level** Level to start rendering the menu at. Setting the start 
  and end levels to the same \# and setting *Show Sub-menu Items* to *Show* 
  will only display that single level.
- **End Level** Level to stop rendering the menu at. If you choose *All*, all 
  levels will be shown depending on the *Show Sub-menu Items* setting.
- **Sub-menu Items** Show or hide the sub-menu items.
