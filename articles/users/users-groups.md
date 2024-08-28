<!-- Filename: Help4.x:Users:_Groups / Display title: Users: Groups -->

## Description

User Groups control what actions a user can take on the site. Actions
include things like creating a new article, changing options for a
component, or logging in. The site administrator assigns permissions for
various actions to each group. Permissions for actions can be assigned
at different levels in the component hierarchy (Global Configuration,
component options, categories, and articles). If a user does not have
permission for a given action, the user cannot perform that action.

User groups also control which objects a user can view on the site.
Objects include categories, articles, modules, menu items, and others.
When you create an access level, one or more user groups are assigned to
it. Then, when you create an object (such as a menu item or module), the
object is assigned an access level. If a user is a member of a group
that is assigned to an access level, this user can view any object
assigned to that access level. If not, then that user cannot view that
object.

User groups can be arranged in a hierarchy. If so, then all child groups
inherit the action permissions and access levels of a parent group. If
used wisely, this feature can save a lot of time setting up your
security system, since it means that you don't have to enter duplicate
setup information.

User Groups control what actions a user may take on the site and which
objects a user can view. This page allows you to view, create, edit or
delete User Groups.

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
