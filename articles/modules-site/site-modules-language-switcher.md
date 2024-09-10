<!-- Filename: Help4.x:Site_Modules:_Language_Switcher / Display title: Modules: Language Switcher -->

## Description

The *Language Switcher* module type allows you to switch between
available Content languages. Selecting a language will take you to the
corresponding page for that language.

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

![language switcher module tab](../../../en/images/modules-site/modules-language-switcher-module-tab.png)

## Form Fields

- **Title** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Pre-text** This is the text or HTML that is displayed above the
  language switcher.
- **Post-text** This is the text or HTML that is displayed below the
  language switcher.
- **Use Dropdown** The three following items change for *Yes* and *No*
  - **No**
    - **Use Image Flags** If set to *Yes*, display the language choice as 
    image flags. Otherwise use the content language native names. If set to
    *No* an extra field appears: **Full Language Names**, which displays
    an upper case two character language code for each language.
    - **Active Language** Display or not the active language.
    If displayed, the class `lang-active` will be added to the element.
    - **Horizontal Display** Default is set to *Yes*, i.e. to create a
    horizontal list display. Set to *No* for a vertical list.
  - **Yes** Tha *Active Language* item is shown selected.
    - **Use Flags For Dropdown** If set to *Yes* the language flag is placed
      before the language name in the dropdown list. 
    - **Full Language Names** If set to *No*, display an upper case two 
      character language code for each language.
    - **Active Language** No effect in the dropdown list.
