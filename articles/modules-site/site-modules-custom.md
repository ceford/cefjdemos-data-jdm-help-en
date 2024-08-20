<!-- Filename: Help4.x:Site_Modules:_Custom / Display title: Site Modules: Custom -->

## Description

The **Custom** module type allows you to create a self-contained HTML
unit and then put it in any valid location on a page.

There are many cases where you might want to put free-form HTML inside a
web page. For example, you might want to create an HTML Image Map or you
might want to copy HTML code from PayPal, Amazon, or some other site.

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
  - To create a new module: select the **New** button from the Toolbar.
    Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

![custom module tab](../../../en/images/modules-site/modules-custom-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Editor** The editor does not allow you to enter certain HTML tags.
  To work around this, you can temporarily change your User's editor to
  "No Editor", create the Custom HTML Module, and then change the editor
  back to TinyMCE. Another option is to use an editor from an Extension
  that allows HTML code to be entered. Another possibility is (if the
  editor has this option) to switch to the HTML mode, enter the code,
  save and switch back to normal view.

### Options Tab

- **Prepare Content** Optionally prepare the content with Joomla Content Plugins.
- **Select a Background Image** If you select an image here it will be
  inserted automatically as an inline style for the wrapping div element.
