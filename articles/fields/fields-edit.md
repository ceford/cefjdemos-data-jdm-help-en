<!-- Filename: Help4.x:Fields:_Edit / Display title: Component: Edit Field -->

## Description

The *Component: Edit Field* page is similar for all components that implement
fields but the page title changes depending on context: *Articles: Edit Field*,
*Contacts: Edit Field* or *Users: Edit Field*.

The **General** tab changes to reflect the type of field being edited and once
a field has been saved its field type cannot be changed. However it easy to
delete fields and create new ones.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Publishing Tab](jdocmanual?article=help/common-elements/edit-publishing).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

* Select **Content → Fields** from the Administrator menu. Or...
* Select **Contact → Fields** from the Administrator menu. Or...
* Select **Users → Fields** from the Administrator menu. Then...
  * Select the **New** button in the Toolbar to create a new field. Or...
  * Select a **Title** from the list to edit an existing field.

**Note:** There is a dropdown list that allows creation of Fields for a
Category, and Mail in the Contact component. They require some coding
experience to prepare suitable template overrides.

## Screenshot

![Articles edit field](../../../en/images/fields/articles-edit-field.png)

## Form Fields

- **Title** The title for this field.

### General tab

#### Left Panel

Parameters for all fields:

- **Type** If you create a field you can choose one of the 16 field
  types. When you save the field this type is permanent.
- **Name** The name will be used to identify the field. Leave this
  blank and Joomla will fill in a default value from the title.
- **Label** Use a descriptive text of the field for the label of the
  field. This text is not translatable. If you do not enter any text for
  a label the title text will also used as label text.
- **Description** The description of the field. A text that will be
  shown as a tool tip when the user moves the mouse over the text box
  while he use it in the Backend creating an article or a contact or a
  third party component that supports fields. This text is not
  translatable. You do not see this description in the Frontend.
- **Required** Is this a mandatory field? In this case the field has to
  be filled before submitting an article or a contact or a third party
  component that supports fields.

#### Right Panel

- **Status** The published status of this field.
  - *Published* The field is visible while editing an article or an
    contact. And it is visible in the Frontend.
  - *Unpublished* The field will not be visible to users while editing an
    article or an contact.
  - *Archived* The field will no longer show on edition an article or an
    contact. You can open it in Fields when you set the filter to archived.
  - *Trashed* The field is deleted but still in the database. It can be
    permanently deleted from the database in Fields with the Empty Trash
    function.
- **Field Group** You may assign a field to a field group.
- **Category** You can assign a field to one or more categories. Note
  that the default *All* does not include *Uncategorised* articles.
- **Access** Select the viewing access level for this field. The access
  levels depend on what has been set up in *Users: Access Levels*.
- **Language** Select the language for this field. If you are not using
  the multi-language feature of Joomla, keep the default of *All*.
- **Note** An optional field to make your personal notes for the field.

### Options tab

![Articles edit field options tab](../../../en/images/fields/articles-edit-field-options-tab.png)

#### Form Options

- **Placeholder** A placeholder text which will appear inside the field
  as a hint for the input. The placeholder is active in the Backend
  while creating an article or a contact or a third party component that
  supports fields. You do do not see it in the Frontend.
- **Field Class** The class attributes of the field when the field is
  rendered. If different classes are needed, list them with spaces.
- **Label Class (Form)** CSS class to apply to the field label when it
  is in edit mode (entering input into a field).
- **Editable In** On which part of the site should the field be shown.
  In the Backend, in the Frontend or both?
- **Showon Attribute** Conditionally show or hide the field depending
  on the value of other fields. The syntax to use here, for example:
  `list-of-items:value1[OR]list-of-items:value2`
  - list-of-items: The *name* of an already created field on
    which this field will depend to be shown.
  - value1: The value needed to have the field on which it depends to
    be shown.
  - `[OR]`: To create a choice among multiple fields. In the example,
    this field will show when the *list-of-items* field has the value:
    *value1* OR *value2*
  - `[AND]`: To combine multiple fields. This field will show only
    when the *list-of-items* field has the value: *value1* AND *value2*
  - You can also use value *does not equal* as in
    *list-of-items!:value1* The syntax will show this field only when
    *list-of-items* is not equal to *value1*
  - To show this field when *list-of-items* field has been selected and
    does not have an empty value, use the syntax *list-of-items!:* (without a
    value specified).

**Note:** Subform fields handle the identifier *name* of *list-of-items*
differently. If you create a Subform custom field and you add this
conditional field there, you need use *field\[ID\]*
instead of *list-of-items*, where ID is the id of the field
*list-of-items*. Therefore, the *showon* attribute for this conditional
field you are creating needs to be: `field36:value1[OR]field36:value2` where
36 is the ID of the field 'List of items'.

#### Display Options

- **Display Class** The class of the field container in the output.
- **Value Class** The class of the field value in the output.
- **Label** Show the label when the field renders.
- **Label Class (Output)** CSS class to apply to the field label when
  it is displayed (displaying the output of a field).
- **Automatic Display** Joomla offers some content events which are
  triggered during the content creation process. This is the place to
  define how the fields should be integrated into content. You can
  choose
  - After Title
  - Before Display Content
  - After Display Content
  - Do not automatically display
- **Prefix** Fixed text to be displayed before a field, for example &pound;.
- **Suffix** Fixed text to be displayed after a field, for example &euro;.
- **Layout** If there is a custom layout then it would be selected here.
- **Display When Read-Only** If the field is read only (perhaps the
  user doesn't have the access level) should the field be displayed or
  hidden.

#### Smart Search

- **Search Index**  Warning: When *Make searchable* is selected, content
  from the field is indexed with the viewing permissions of the content item.
  This might lead to unexpected information disclosure.
