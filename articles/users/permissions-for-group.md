<!-- Filename: Help4.x:Permissions_for_Group / Display title: Permissions for Group -->

## Description

The Advanced Permissions Report maps out the exact permissions for any
given user group across all assets on your Joomla! installation. It is
useful for debugging user access problems.

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

### Column Headers

In the table containing the assets from your Joomla! site, you will see
different columns. For each asset the permission for this group is
shown, color coded as per legend.

- **Asset Title** The asset as we know it.
- **Asset Name** The asset as known internally.
- **Site Login** Allows users in the group to login to the Frontend
  site.
- **Administrator Login** Allows users in the group to login to the
  Backend Administrator site.
- **Web Services Login** Allows utilization of the Joomla Web Services
  API via a Super User API Token.
- **Offline Access** Allows users in the group to access the Frontend
  site when site is offline.
- **Super User** Allows users in the group to perform any action over
  the whole site regardless of any other permission settings.
- **Configure Options Only** Allows users in the group to edit the
  options (except permissions) of any extension.
- **Access Administration Interface** Allows users in the group to
  access all of the administration interface except Global
  Configuration.
- **Create** Allows users in the group to create any content in any
  extension.
- **Delete** Allows users in the group to delete any content in any
  extension.
- **Edit** Allows users in the group to edit any content in any
  extension.
- **Edit State** Allows users in the group to edit the state of any
  content in any extension.
- **Edit Own** Allows users in the group to edit any content they own
  in any extension.
- **Edit Custom Field Value** Allows users in the group to edit any
  value of custom fields submitted in any extension.
- **LFT** The left and right values in the nesting hierarchy. 
- **ID** This is a unique identification number for this item assigned
  automatically by Joomla. It is used to identify the item internally,
  and you cannot change this number. When creating a new item, this
  field displays "0" until you save the new entry, at which point a new
  ID is assigned to it.
