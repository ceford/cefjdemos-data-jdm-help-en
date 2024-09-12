<!-- Filename: Help4.x:Permissions_for_User / Display title: Permissions for User -->

## Description

The *Permissions for User* page shows a permissions report showing the exact 
permissions for any given user across all site assets. It is useful for 
debugging user access problems.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to access

- Select **Users → Manage** from the Administrator menu. Then...
  - Select the **Permissions** button for a specific user.

## Screenshot

![users permissions for user](../../../en/images/users/users-permissions-for-user.png)

Above the Permissions table are selected items showing access permissions
using icons for *Allowed*, *Not Allowed* and *Forbidden*. The icon key is below
the table. 

- **Site Login** Can the user login to the site Frontend.
- **Administrator Login** Can the user login to the site Backend.
- **Web Services Login** Can the user access the Joomla Web Services
  API via a Super User API Token.
- **Offline Access** Can the user access the site Frontend when it
  is offline.

### Column Headers

In the table containing the site assets shows permission for the selected user.

- **Asset Title** The asset name in plain language.
- **Asset Name** The internal asset name.
- **Super User** Can the user perform Super User actions for the asset 
  regardless of any other permission settings.
- **Configure Options** Can the user edit the asset options (except permissions).
- **Access Administration Interface** Can the user access the administration 
  interface of the asset.
- **Create** Can the user create content in the asset.
- **Delete** Can the user delete content in the asset.
- **Edit** Can the user edit content in the asset.
- **Edit State** Can the user edit the state of the asset.
- **Edit Own** Can the user edit any user owned content in the asset.
- **Edit Custom Field Value** Can the user edit any
  custom field value in the asset.
- **LFT** The left and right values in the nesting hierarchy. This is used
  for asset nesting and ordering.
- **ID** This is a unique identification number for this item assigned
  automatically by Joomla. It is used to identify the item internally,
  and cannot be changed. 
