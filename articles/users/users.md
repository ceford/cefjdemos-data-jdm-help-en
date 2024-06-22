<!-- Filename: Help4.x:Users / Display title: Users -->

## Description

The Users list is used to find, add, and edit users.

## How to access

* Select **Site → Users** from the *Home Dashboard*. Or...
* Select **Users → Manage** from the Administrator menu.

To add a User:

- Select the **New** toolbar button

To edit a User:

- Select a **Name** from the list

## Screenshot

<img
src="https://docs.joomla.org/images/thumb/0/06/Help-4x-Users-screen-en.png/800px-Help-4x-Users-screen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/06/Help-4x-Users-screen-en.png/1200px-Help-4x-Users-screen-en.png 1.5x, https://docs.joomla.org/images/thumb/0/06/Help-4x-Users-screen-en.png/1600px-Help-4x-Users-screen-en.png 2x"
data-file-width="2556" data-file-height="1500" width="800" height="469"
alt="Users list screen" />

## Column Headers

- **Checkbox**. Check this box to select users. To select all users,
  check the box in the column heading. After boxes are checked the
  toolbar button 'Actions' get active.
- **Name**. The full name of the user.
  - **Add a Note**. Create a Note for the user.
    - **Show notes list**. Show the User
      Notes
      for the user as a list.
    - **Display note**. Show the User Notes for the user in a window and
      stays in the current screen.
- **Username**. The name the user will log in as.
- **Enabled**. Whether or not the user is enabled.
- **Activated**. Whether or not the user is activated. Normally when a
  user registers from the Frontend, some type of activation is required.
  This is controlled by the 'New User Account Activation' parameter in
  the Users: Options.
- **User Groups**. The list of groups that the user belongs to. Note
  that a user may belong to more than one group.
- **Email**. The email address from the user is displayed here.
- **Last visit**. Here you can see the date on which the user last
  logged in.
- **Registered**. The date the user was registered.
- **ID**. A unique identification number for this user, you cannot
  change this number.

## List Filters

### Search bar

Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Filter Options**. Click to display the additional filters.
- **Clear**. Click to clear the Filter field and restore the list to its
  unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- **Number to Display**. Shows the number of users in a list. Select
  from the dropdown list to change the number displayed.The default for
  a site is '20' but this may be changed in the Global Configuration.

### Filter Options

- **Select State**. Select from Enabled / Disabled.
- **Select Active State**. Select from Activated / Unactivated.
- **Select Group**. Select from the list box to list only users who are
  members of that group.
- **Select Last Vist Date**. Select from a list to show only users who
  visited in a selected time frame.
- **Select Registration Date**. Select from a list to show only users
  who registered in a selected time frame.

### Pagination

When the number of articles is more than one page,
you will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **New**. Opens the editing screen to create a new user.
- **Actions**. Reveals a list of actions for selected users. Check one
  or more users checkboxes to activate the list.
  - **Activate**. Activates multiple users. Select all the users
    required using their checkboxes then click this button. An email
    will be sent to the user notifying that their account has been
    activated
  - **Block**. Blocks one or more users. Select the users to be blocked
    using their checkboxes then click this button.
  - **Unblock**. Unblocks one or more users. Select the users to be
    unblocked using their checkboxes then click this button.
  - **Batch**. Batch processes the selected users.
  - **Delete**. Deletes the selected users.
- **Options**. Opens Users: Options.
- **Help**. Opens this help screen.

## Batch Process

The Batch Process allows a change in settings for a group of selected
users.

<img
src="https://docs.joomla.org/images/thumb/2/21/Help-4x-Users-batch-subscreen-en.png/600px-Help-4x-Users-batch-subscreen-en.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/21/Help-4x-Users-batch-subscreen-en.png/900px-Help-4x-Users-batch-subscreen-en.png 1.5x, https://docs.joomla.org/images/thumb/2/21/Help-4x-Users-batch-subscreen-en.png/1200px-Help-4x-Users-batch-subscreen-en.png 2x"
data-file-width="1598" data-file-height="717" width="600" height="269"
alt="Users batch process dialog" />

**How to Batch Process** a group of users:

1.  Select one or more users on the list by checking the desired
    checkboxes.
2.  Click the Batch Toolbar button.
3.  Set one or more of the following values:
    - To change the **User Group**, select the desired new user group
      from the Select Group list box.
    - Choose to do the desired action.
      - Add To Group
      - Delete From Group
      - Move To Group
    - Decide if a **Password Reset** is wanted.
4.  When all of the settings are entered, click on Process to perform
    the changes. A message **"Batch process completed successfully."**
    will show.

## Quick Tips

- Click on the name of a user to edit the user's properties.
- Click on the icon in the Enabled column to toggle between Enabled and
  Disabled status.
