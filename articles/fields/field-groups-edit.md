<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group / Display title: Component: Edit Field Group -->

## Description

Field Groups are used to collect related fields under a named Tab in a
data entry form. The Component: Edit Field Group is similar for all components 
that implement fields but the page title changes depending on context: 
Articles: Edit Field Group, Contacts: Edit Field Group or Users: Edit Field
Group. 

### Common Elements

Some aspects of this page are covered in 
separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Publishing Tab](jdocmanual?article=help/common-elements/edit-publishing).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

* Select **Content → Field Groups** from tha Administrator menu. Or...
* Select **Contact → Field Groups** from tha Administrator menu. Or...
* Select **Users → Field Groups** from tha Administrator menu. Then...
  * select the **New** button in the Toolbar to create a new field. Or...
  * Select a **Title** from the list to edit an existing field.

**Note:** There is a dropdown list that allows creation of Fields for a
Category, and Mail in the Contact component. They require some coding 
experience to prepare suitable template overrides.

## Screenshot

This example is an Articles: Fields page. Contacts: Fields and Users: Fields are
similar.

![articles edit field group](../../../en/images/fields/articles-edit-field-group.png)

## Form Fields

- **Title**. The Title for this field group.

### General

#### Left Panel

- **Description**. Text that will be displayed as a tool tip when on hover 
  over the text box while creating an article or a contact or a
  third party component that supports custom fields. This text is not
  translatable. You do not see this description in the Frontend.

#### Right Panel

- **Status**. The published status of this field group.
  - Published: The field group is visible while editing an article or a
    contact. And it is visible in the Frontend.
  - Unpublished: The field group will not be visible to users while
    editing an article or a contact.
  - Archived: The field group will no longer show on editing an article
    or a contact. You can open it in Field Groups when you set the filter 
    to archived.
  - Trashed: The field group is deleted but still in the database. It
    can be permanently deleted from the database in Field Groups with the 
    Empty Trash function.
- **Access**. Select the viewing access level for this field group. The
  access levels depend on what has been set up in Users: Access Levels.
- **Language**. Select the language for this field group. If you are not
  using the multi-language feature of Joomla, keep the default of 'All'.
- **Note**. An optional field to make your personal notes for the field
  group.

### Options

- **Display When Read-Only**. If the field group is read only (perhaps
  the user doesn't have the access level) should the field group be
  displayed or hidden.
