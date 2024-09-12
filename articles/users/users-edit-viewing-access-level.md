<!-- Filename: Help4.x:Users:_Edit_Viewing_Access_Level / Display title: Users: Edit Viewing Access Level -->

## Description

Access levels control which users can view which assets on a site.
Assets include menu items, modules, categories, and component items
(articles, contacts, and so on). Each asset in the site is assigned to
one access level. User groups are also assigned to each access level.

If a user is a member of a group that in turn has permission for an
access level, then that user can view all assets assigned to that
access level. It is important to understand that user groups can be
arranged in a parent-child hierarchy. If so, then a child group has
access to all access levels that the parent group has access to. So you
don't need to assign a child group access to levels that its parent
group already has access to.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to access

- Select **Users → Access Levels** from the Administrator menu.
  Then...
  - Select a link from the **Level Name** column to edit an existing level. Or...
  - Select the New button to create a new access level.

## Screenshot

![users viewing access levels](../../../en/images/users/users-edit-viewing-access-level-details-tab.png)

### Level Details tab

- **Level Title** Enter a Title for this Access level.
- **User Groups With Viewing Access** Check any Group to have this
  Access Level.

### User Groups With Viewing Access tab

![users viewing access levels](../../../en/images/users/users-edit-viewing-access-level-ugwva-tab.png)

Select a check box to add a user group to a viewing level. In the
example shown all Groups are children of Public so it not necessary to
check any of the child groups. They inherit the Public access
permissions. This feature should only be used for custom groups!

## Tips

- If you add a new group, you may need to edit any access levels that
  this group should have access to.
