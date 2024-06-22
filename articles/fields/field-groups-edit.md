<!-- Filename: Help4.x:Component:_New_or_Edit_Field_Group / Display title: Field Groups: Edit -->

## Description

Field Groups are used to collect related fields under a named Tab in a
data entry form.

The helpscreen show as example Contacts.

## How to Access

Select **Content → Field Groups** from tha Administrator menu. Or...
Select **Contact → Field Groups** from tha Administrator menu. Or...
Select **Users → Field Groups** from tha Administrator menu. Then...

Select an item from the list in the filter bar. The options are:

- Content: Articles or Category.
- Contact: Contact, Mail or Category.
- User: No options.

To add a Field Group: select the **New** toolbar button

To edit a Field Group: select a **Title** from the list

## Screenshot

<img
src="https://docs.joomla.org/images/thumb/1/15/Help-4x-Field-Groups-Edit-screen-en.png/800px-Help-4x-Field-Groups-Edit-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/15/Help-4x-Field-Groups-Edit-screen-en.png/1200px-Help-4x-Field-Groups-Edit-screen-en.png 1.5x, https://docs.joomla.org/images/thumb/1/15/Help-4x-Field-Groups-Edit-screen-en.png/1600px-Help-4x-Field-Groups-Edit-screen-en.png 2x"
data-file-width="2880" data-file-height="1370" width="800" height="381"
alt="Field Groups Edit general tab" />

## Form Fields

- **Title**. The Title for this field group.

### General

#### Left Panel

- **Description**. The description of the field group. A text that will
  be shown as a tool tip when the user moves the mouse over the text box
  while he use it in the Backend creating an article or a contact or a
  third party component that supports custom fields. This text is not
  translatable. You do not see this description in the Frontend.

#### Right Panel

- **Status**. The published status of this field group.
  - Published: The field group is visible while editing an article or an
    contact. And it is visible in the Frontend.
  - Unpublished: The field group will not be visible to users while
    editing an article or an contact.
  - Archived: The field group will no longer show on edition an article
    or an contact. You can open it in Field
    Groups
    when you set the filter to archived.
  - Trashed: The field group is deleted but still in the database. It
    can be permanently deleted from the database in Field
    Groups
    with the Empty Trash function.
- **Access**. Select the viewing access level for this field group. The
  access levels depend on what has been set up in Users: Access Levels.
- **Language**. Select the language for this field group. If you are not
  using the multi-language feature
  of Joomla, keep the default of 'All'.
- **Note**. An optional field to make your personal notes for the field
  group.

### Publishing

<img
src="https://docs.joomla.org/images/thumb/c/ca/Help-4x-Field-Groups-Edit-publishing-subscreen-en.png/600px-Help-4x-Field-Groups-Edit-publishing-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/c/ca/Help-4x-Field-Groups-Edit-publishing-subscreen-en.png/900px-Help-4x-Field-Groups-Edit-publishing-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/c/ca/Help-4x-Field-Groups-Edit-publishing-subscreen-en.png/1200px-Help-4x-Field-Groups-Edit-publishing-subscreen-en.png 2x"
data-file-width="2880" data-file-height="970" width="600" height="202"
alt="Field Groups Edit publishing tab" />

- **Created Date**. The current time when the field group was created.
  Enter in a different date and time or click on the calendar icon to
  find the desired date.
- **Created By**. Name of the User who created this field group. This
  will default to the currently logged-in user. If you want to change
  this to a different user, click the Select User button.
- **Modified Date**. Date of last modification.
- **Modified By**. Username who performed the last modification.
- **ID**. A unique identification number for this field group, you
  cannot change this number. When creating a new field group, this field
  group displays "0" until you save the new entry.

### Options

<img
src="https://docs.joomla.org/images/thumb/b/b8/Help-4x-Field-Groups-Edit-options-subscreen-en.png/600px-Help-4x-Field-Groups-Edit-options-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/b8/Help-4x-Field-Groups-Edit-options-subscreen-en.png/900px-Help-4x-Field-Groups-Edit-options-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/b/b8/Help-4x-Field-Groups-Edit-options-subscreen-en.png/1200px-Help-4x-Field-Groups-Edit-options-subscreen-en.png 2x"
data-file-width="2880" data-file-height="550" width="600" height="115"
alt="Field Groups Edit options tab" />

- **Display When Read-Only**. If the field group is read only (perhaps
  the user doesn't have the access level) should the field group be
  displayed or hidden.

### Permissions

This is where you can enter permissions for this field group.

<img
src="https://docs.joomla.org/images/thumb/5/54/Help-4x-Field-Groups-Edit-permissions-subscreen-en.png/600px-Help-4x-Field-Groups-Edit-permissions-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/54/Help-4x-Field-Groups-Edit-permissions-subscreen-en.png/900px-Help-4x-Field-Groups-Edit-permissions-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/5/54/Help-4x-Field-Groups-Edit-permissions-subscreen-en.png/1200px-Help-4x-Field-Groups-Edit-permissions-subscreen-en.png 2x"
data-file-width="2880" data-file-height="1378" width="600" height="287"
alt="Field Groups Edit permissions tab" />

To change the permissions for this field group, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Create**. Users can create a field group.
    - **Delete**. Users can delete this field group.
    - **Edit**. Users can edit this field group.
    - **Edit State**. User can change the published state and related
      information for this field group.
    - **Edit Own**. Users can edit any field group they own.
    - **Edit Custom Field Value.** Users can edit the field group value.
3.  Select the desired permission for the action you wish to change.
    - **Inherited**. Inherited for users in this Group from the Global Configuration,
      parent group, or category.
    - **Allowed**. Allowed for users in this Group.Note: If this action
      is Denied at one of the higher levels, the Allowed permission here
      will not take effect. A Denied setting cannot be overridden.
    - **Denied**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Save**. Saves the field group and stays in the current screen.
- **Save & Close**. Saves the field group and closes the current screen.
  - **Save & New**. Saves the field group and keeps the editing screen
    open and ready to create another field group.
  - **Save as Copy**. Saves your changes to a copy of the current field
    group. Does not affect the current field group.
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help**. Opens this help screen.
