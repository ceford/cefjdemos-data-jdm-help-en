<!-- Filename: Help4.x:Languages:_Edit_Override / Display title: Languages: Edit Override -->

## Description

In the Joomla code, text strings that are to appear in the User
Interface, either the Site interface or the Administrator interface, are
expressed as string constants. For example, the string *Your session has
expired. Please log in again.* is expressed as
`JLIB_ENVIRONMENT_SESSION_EXPIRED`. The text string can be translated
into any language. The default language is British English. There are
thousands of such strings in a Joomla installation.

If a string does not suit your site you can use the Language Override
feature to replace the original. The *Languages: Overrides* page shows a list
of existing overrides, so it is empty initially.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to Access

- Select **System → Manage Panel → Language Overrides**. Then...
  - Select a **Language and Client** from the drop down list. Then...
    - Select the **New** button in the Toolbar to create a new override.
      Or...
    - Select the constant link in the **Constant** column to edit an
      existing override.

## Screenshot

![Languages Edit Override](../../../en/images/languages/languages-edit-override.png)

## Form Fields

### Right Panel: Search text you want to change

- **Search For** Start here! You are more likely to know the Value
  (expired) than the Constant (`_EXPIRED`). In either case, the search is
  a case insensitive for the partial string.
- **Search Text** Enter the text to search for and select the *Search* button.
- **Search Results** A list of strings containing the search term
  appears in a separate Results panel beneath the Right panel. Select the 
  one you are looking for. The constant and text will be copied into the 
  *left panel* to be updated and saved. 

### Left Panel: Create a New Override or Edit this Override

- **Language** and **Location** These were selected before opening this
  edit form and cannot be changed.
- **Language Constant** This is the string used in the code by the
  developer. If the value does not exist in the code the string will
  never be used.
- **Text** This is where you override the default term with your
  version.
- **For Both Locations** Select to apply the override to both front end and
  back end.
- **File** This shows where the override file is located in the file
  system. You might need to know this for trouble-shooting.
