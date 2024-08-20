<!-- Filename: Help4.x:Site_Modules:_Wrapper / Display title: Modules: Wrapper -->

## Description

The **Wrapper** module type allows you to display an external website in
a module. The functionality is the same to that of the 'iFrame Wrapper'
you can add as a menu item. If the page to which the wrapper is linked
is too big, bars will be shown below and to the right of the wrapper,
allowing you to "navigate" the page.

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

![wrapper module tab](../../../en/images/modules-site/modules-wrapper-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **URL** URL to site/file you wish to display within the iframe.
- **Auto Add** By default, http:// will be added unless it detects 
  http:// or https:// in the URL you provide. This allows you
  to switch this ability off.
- **Scroll Bars** Show or hide Horizontal and Vertical Scroll Bars.
- **Width** Width of the iFrame window. You can enter an absolute
  figure in pixels or a relative figure by adding a %.
- **Height** Height of the iFrame window.
- **Auto Height** The height will automatically be set to the size of the 
  external page. This will only work for pages on your own domain.
- **Frame border** Show a frame border which wraps the iframe.
- **Target Name** Name of the iFrame when used as Target
