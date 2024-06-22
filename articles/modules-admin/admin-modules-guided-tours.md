<!-- Filename: Help4.x:Admin_Modules:_Tours_Menu / Display title: Modules: Guided Tours -->

## Description

The **Guided Tours** module shows a list of available guided tours.

It will present itself as a dropdown, available in the Administrator Title Bar.

<img alt="Guided Tours Dropdown Menu" src="https://docs.joomla.org/images/1/1d/Guidedtours_button_en.png" decoding="async" data file width="140" data file height="48" width="140" height="48">

## How to Access

Select **System** → **Manage** Panel → **Administrator Modules** from the Administrator menu. Then...

- To create a new module: select the **New** button from the Toolbar. Then...
  - Select the required module type.
- To edit an existing module:
  - Find the module in the list of installed modules and select the title link in the **Title** column.

## Screenshot

<img alt="Guided Tours module" src="https://docs.joomla.org/images/4/4c/Admin_module_guided_tours_en.png" decoding="async" width="1031" height="913" data file width="1031" data file height="913">

## Form Fields

- **Title.** The title of the module. This is also the title displayed for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Contextual Tour Count.** (in Joomla 5) The maximum number of tours presented in the dropdown related to a particular page.
- **Tour Count.** The maximum number of tours presented in the dropdown.

In the following screenshot for Joomla 5, the module is expanded, showing a 3-parts dropdown.

- the first section shows tours that are related to a page (or in the context of a page),
- the second section shows tours that are not in context (set tour count to 0 to hide this section),
- the third section offers access to a modal containing all tours.

<img alt="Admin module guided tours sample" src="https://docs.joomla.org/images/2/2b/Admin_module_guided_tours_sample_en.png" decoding="async" width="247" height="395" data file width="247" data file height="395">

The initial ordering of the tours is dictated by the tour order in the administrator's tours view.

#### Right Panel

- **Show Title**. (Show/Hide) Choose whether to show or hide the modules title. The title will be the one in the Form Field above.
- **Position.** Choose the module position you wish this module to be displayed
  in. An adequate position is *status*.
- **Status**. The published status of the item.
- **Access**. The viewing Access Level for this item.
- **Module Ordering.** This shows a drop down of every module in the position that the current module is in. This is the order that the modules will display in the Modules page.
- **Start Publishing**. Date and time to start publishing. Use this field if you want to enter content ahead of time and then have it published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this field if you want to have content automatically changed to Unpublished state at a future time (for example, when it is no longer applicable).
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for example, to document information about this item).

## Advanced Tab

<img alt="Advanced parameters tab" src="https://docs.joomla.org/images/c/ca/Module_guidedtours_advanced_en.png" decoding="async" width="1231" height="803" data file width="1231" data file height="803">

- **Layout.** If you have defined one or more alternative layouts for a module either in the template or Joomla! Core, you can select the layout to use for this module.
- **Module Class.** A suffix applied to the CSS class of the Module. This allows you to create customized CSS styles that will apply just to this module. You would then modify the "user.css" file of your template to apply styling to this new class. Enter this parameter with a leading space to create a new CSS class for this module. Enter the parameter without a leading space to change the CSS class name for this module.
- **Module Tag.** The HTML tag for the module to be placed in. By default this is a div tag but other HTML5 elements can also be used.
- **Bootstrap Size.** (Values 0 to 12) This allows you to choose the width of the module via the span element built into bootstrap.
- **Header Tag.** The HTML tag to use for the modules header or title. This can be an h1, h2, h3, h4, h5, h6 or a p tag. Note that you must use a module style (chrome) of html5 or add your custom module styles in ``<mytemplate/html/modules.php`.
- **Header Class.** Here you can add optional CSS classes to add to the modules header or title element.
- **Module Style.** You can use this option to override the templates style for its position.

### Permissions Tab

<img alt="Permissions tab" src="https://docs.joomla.org/images/1/1c/Module_guidedtours_permissions_en.png" decoding="async" width="1230" height="719" data file width="1230" data file height="719">

To change the permissions, do the following.

- Select the **Group** by clicking its title located on right.
- Find the desired **Action**. Possible Actions are:
  - **Delete**. Users can delete the module.
  - **Edit**. Users can edit the module.
  - **Edit State**. User can change the published state and related information for the module.
- Select the desired permission for the action you wish to change. Possible settings are:
  - ***Inherited.*** Inherited for users in this Group from the Global Configuration, Article Manager Options, or Category permissions.
  - ***Allowed.*** Allowed for users in this Group. Note that, if this action is Denied at one of the higher levels, the Allowed permission here will not take effect. A Denied setting cannot be overridden.
  - ***Denied.*** Denied for users in this Group.
- Select **Save** in the **Toolbar**. When the screen refreshes, the Calculated Setting column will show the effective permission for this Group and Action.

## Toolbar

At the top of the page you will see the toolbar shown in the Screenshot above. The functions are:

- **Save.** Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and ready to create another item.
- **Save as Copy**. Saves your changes to a copy of the current item. Does not affect the current item. This toolbar icon is not shown if you are creating a new item.
- **Close**. Closes the current screen and returns to the previous screen without saving any modifications you may have made.
- **Help**. Opens this help screen.
