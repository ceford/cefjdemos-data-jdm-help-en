<!-- Filename: Help4.x:Edit_Permissions / Display title: Edit Permissions -->

## Purpose

Many extensions have edit screens with a Permissions tab that is used to change
the permissions allocated to User Groups. The number of User Groups may vary
as custom User Groups can be added to use for special purposes. The
number of Actions that can be altered also varies by extension. This article
is a brief description of the permissions screens for such special
purposes.

Imagine there is a user who looks after Media (images and files) but
is not allowed any other responsibilities. A group named Oddjob has been
created and assigned to the Special access level. A user also named Oddjob has
been created and assigned to the Oddjob group.

For more detailed information on User Groups, Access Levels and Permissions
there is a separate tutorial on [Access Control](jdocmanual?article=user/users/access-control "").

## Global Configuration Permissions

In this example, users in the Oddjob group have been assigned Global
permission to login to the Administrator interface but nothing else.

![Permissions Screenshot](../../../en/images/common-elements/global-configuration-permissions-tab.png "")

## Component Configuration Permissions

To access a specific component permissions must be set in the component options.
In this example the Media component options.

![Media Screenshot](../../../en/images/common-elements/media-options-permissions-tab.png "")

You will notice that this component has fewer Actions available and the Oddjob
group is allowed just enough permissions to do the job.

To change the permissions for this component:

* Select the Group by clicking its title located on the left.<br>
    Find the desired Action.
    * Delete. Users can delete this article.
    * Edit. Users can edit this article.
    * Edit State. User can change the published state and related information for this article.
* Select the desired permission for the action you wish to change.
    * Inherited. Inherited for users in this Group from the Global Configuration, Articles Options, or Articles Category.
    * Allowed. Allowed for users in this Group.Note: If this action is Denied at one of the higher levels, the Allowed permission here will not take effect. A Denied setting cannot be overridden.
    * Denied. Denied for users in this Group.
* Click Save in Toolbar at top. When the screen refreshes, the Calculated Setting column will show the effective permission for this Group and Action.

## The User Experience

After login, a user in the Oddjob group will see whatever Home Dashboard
modules have **Special** access set and a Menu item link to the Media component.

![Home Dashboard for Oddjob](../../../en/images/common-elements/home-dashboard-for-oddjob.png "")

And the Media screen for user Oddjob is as expected:

![Media screen for Oddjob](../../../en/images/common-elements/media-screen-for-oddjob.png "")
