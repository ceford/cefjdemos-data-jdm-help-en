<!-- Filename: Help4.x:Admin_Modules:_Custom / Display title: Modules: Custom -->

## Description

The *Custom* module type allows you to create a self-contained HTML
unit and then place it in any valid location on a page.

There are many cases where free-form HTML might be shown in the administrator
interface. For example, a temporary system message might be displayed at the 
top of all Administrator pages (th customtop position). Additional styling 
may be required via the Advanced tab.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Modules: Module Tab](jdocmanual?article=help/modules/modules-module-tab).
* [The Modules: Advanced Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **System → Manage Panel → Administrator Modules** from
  the Administrator menu. Then...
  - To create a new module: select the **New** button from the Toolbar.
    Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

![modules articles latest tab](../../../en/images/modules-admin/modules-custom-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Editor** The editor does not allow entry of certain HTML tags. This can be
  configured in the Global Configuration *Text Filters* tab and the specific
  editor plugin.
