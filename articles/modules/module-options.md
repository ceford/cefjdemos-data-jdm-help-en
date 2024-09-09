<!-- Filename: Help4.x:Modules:_Options / Display title: Module: Options -->

## Description

The *Module: Options* page is used to set global settings for all modules. They
can be overridden in individual modules. The same global options are used for 
Site and Administrator modules.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Context → Site Modules** from the Administrator menu. Then...
- Select the **Options** button in the Toolbar.

## Screenshot

![Module Options general tab](../../../en/images/modules/module-options-general-tab.png)

## Form Fields

### General tab

* **Edit Module** Select if module editing should be opened in the site or
  Administrator interface.

  When opening a module to edit via the Site interface, either an edit form 
  will be opened there or there will be a redirect to the Administrator 
  interface edit form, via an Administrator login form if necessary.

### Administrator Modules tab

* **Language Filtering** Allows filtering administrator modules per
  administrator language.

  Site modules have a Language selector in the right column of the module edit
  form. It may be set to *All* or to one of the installed languages to control
  the visibility of the module.

  The Administrator modules edit form does not usually have the Language 
  selector displayed. So a module cannot be restricted to a specific language.
  With this option set to *Yes* the language selector is displayed in the
  module edit form and can be used to restrict visibility of an Administrator
  module to a single language.

![Module Options general tab](../../../en/images/modules/module-options-administrator-modules-tab.png)

## Tips

* Enable module editing in Global Configuration.
