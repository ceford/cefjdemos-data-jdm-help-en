<!-- Filename: Help4.x:Permissions_for_Group / Display title: Permissions for Group -->

## Description

The *Permissions for Group* page shows a permissions report showing the exact 
permissions for any given user group across all site assets. It is useful for 
debugging user access problems.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to access

- Select **Users → Groups** from the Administrator menu. Then...
  - Select the **Permissions** icon for a specific group from the user
    groups list.

## Screenshot

![users permissions for group](../../../en/images/users/users-permissions-for-group.png)

Above the Permissions table are selected items showing access permissions
using icons for *Allowed*, *Not Allowed* and *Forbidden*. The icon key is below
the table. 

- **Site Login** Can users in the group login to the site Frontend.
- **Administrator Login** Can users in the group login to the site Backend.
- **Web Services Login** Can users in the group access the Joomla Web Services
  API via a Super User API Token.
- **Offline Access** Can users in the group access the site Frontend when it
  is offline.
- **Super User** Can users in the group perform any action over
  the whole site regardless of any other permission settings.

### Column Headers

In the table containing the site assets shows permission for the selected group.

- **Asset Title** The asset name in plain language.
- **Asset Name** The internal asset name.
- **Configure Options** Can users in the group edit the
  options (except permissions) of this asset.
- **Access Administration Interface** Can users in the group access the 
  administration interface of the asset.
- **Create** Can users in the group create content in the asset.
- **Delete** Can users in the group delete content in the asset.
- **Edit** Can users in the group edit content in the asset.
- **Edit State** Can users in the group edit the state of the asset.
- **Edit Own** Can users in the group edit any content they own in the asset.
- **Edit Custom Field Value** Can users in the group edit any
  custom field value in the asset.
- **LFT** The left and right values in the nesting hierarchy. This is used
  for asset nesting and ordering.
- **ID** This is a unique identification number for this item assigned
  automatically by Joomla. It is used to identify the item internally,
  and cannot be changed. 
