<!-- Filename: Help4.x:Users:_Groups / Display title: Users: Groups -->

## Description

User Groups control what actions a user can take on a site. Actions
include things such as viewing an article, creating an article, changing 
options for a component, or logging in. The site administrator assigns 
permissions for various actions to each group. Permissions for actions can 
be assigned at different locations in the component hierarchy, for example
in Global Configuration, component options or module options. If a user 
group does not have permission for a given action, the user in that group
cannot perform that action.

Viewing Access control is implemented through the use of **Access Levels**, 
which have one or more user groups assigned to them. Assets such as articles,
menu items or modules are assigned an access level. A user who is a member of 
a group that is assigned to a specific access level can view any asset 
assigned to that access level. 

User groups can be arranged in a hierarchy in which all child groups
inherit the action permissions and access levels of a parent group. If
used wisely, this feature can save a lot of time by avoiding duplication in
setting up a site security system.

The *Users: Groups* page lists the current User Groups in hierarchy. It can be
used to create new user groups and delete groups that are no longer required.
Do not delete any of the default user groups!

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to access

- Select **Users → Groups** from the Administrator menu.

## Screenshot

![users groups](../../../en/images/users/users-groups-list.png)

## Tips

- Select the name of a group to edit the group's properties.
- Select the Permission icon to review the group permissions to access each
  asset. This is often used to debug access permissions problems.
- Select an Enabled Users number to see a list of enabled users in that group.
- Select a Blocked Users number to see a list of blocked users in that group.
