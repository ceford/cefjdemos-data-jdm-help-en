<!-- Filename: Help4.x:Weblinks:_Options / Display title: Web Links Options -->

## Description

Web Links Options configuration allows setting of parameters used
globally for all web link menu items.

## How to Access

- Select **Components -> Weblinks -> Links** from the Administrator menu. Then...
- Select the **Options** Toolbar button.

## Screenshot

ToDo

### Web Link Tab

These settings apply for single Web Links unless they are changed for a
specific menu item or Web Link.

- **Allow Captcha on Web Link.** Select the captcha pugin that will be
  used in the web link submit form. You may need to enter required
  information for your captcha plugin in the Plugin Manager. If 'Use
  Default' is selected, make sure a captcha plugin is selected in Global
  Configuration.
- **Target.** Target browser window when the link is selected.
- **Count Clicks.** (No/Yes) If Yes, the number of times the link has
  been clicked will be recorded.
- **Text/Icon/Web Link Only.** Shows a text, icon, or nothing with the
  Web Link. Default is Icon.
- **Select Icon.** This allows you to select an image file to use as the
  default icon for web links. When you click on the Select button, a
  modal window opens that allows you to browse through the image files
  on your site.
- **Image Float.** (Right/Left/None). Where to display the image on the
  page.
- **Show Tags.** (Hide/Show). Hide or Show the feed's tags.

### Category Tab

Category Options control how weblinks will show when you drill down to a
weblinks to view its links.

- **Choose a layout.** (Blog/List/user defined). This lets you select
  the default layout to show when you click on a Category link. If you
  create an alternative layout for a category layout, you may select
  that as the default.
- **Category Title.** (Hide/Show) Hide or Show the title of the
  category.
- **Category Description.** (Hide/Show) Hide or Show the description for
  the category.
- **Category Image.** (Hide/Show) Hide or Show the category image.
- **Subcategory Levels.** (None/All/1-5). Categories in Joomla can be
  created in a hierarchy. This lets you control how many levels of
  subcategories to show when showing a category view.
- **Empty Categories.** (Hide/Show) Hide or Show categories that don't
  contain any items or subcategories.
- **Subcategories Descriptions.** (Hide/Show) Hide or Show the
  descriptions for subcategories that are shown.
- **\# Web Links.** Show or Hide the number of web links in each
  category.
- **Show Tags.** Show or Hide the tags for a single category.

### Categories Tab

These settings apply for Web Links Categories Options unless they are
changed for a specific menu item.

- **Top Level Category Description.** (Hide/Show). Hide or Show the
  description of the top-level category.
- **Subcategory Levels.** (All/1-5). How many levels in the hierarchy to
  show.
- **Empty Categories.** (Hide/Show). Hide or Show categories that
  contain no items and no subcategories.
- **Subcategories Descriptions.** (Hide/Show). Hide or Show the
  description of each subcategory.
- **\# Web Links.** Show or Hide the number of web links in each
  category.

### List Layouts Tab

These settings apply for Weblinks List Options unless they are changed
for a specific menu item.

- **Filter Field.** The Filter Field creates a text field where a user
  can enter a field to be used to filter the weblinks shown in the list.
    - *Hide:* Don't show a filter field.
    - *Title:* Filter on weblink title.
    - *Author:* Filter on the author's name.
    - *Hits:* Filter on the number of weblinks hits.
- **Display Select.** (Hide/Show) Whether to hide or show the Display \#
  control that allows the user to select the number of items to show in
  the list.
    If there are more items than this number, you can use the page
    navigation buttons (Start, Prev, Next, End, and page numbers) to
    navigate between pages. Note that if you have a large number of items,
    it may be helpful to use the Filter options, located above the column
    headings, to limit which items display.
- **Table Headings.** (Hide/Show) Table Headings show a heading above
  the weblinks list. If set to *Show*, this heading will shown above the list.
  Otherwise the list will show with no headings.
- **Links description.** (Hide/Show) Whether to hide or show the
  description of the web link.
- **Hits.** (Hide/Show) Whether to hide or show the number of times this
  web link has been accessed.

### Integration Tab

These settings determine how the Weblinks Component will integrate with
other extensions.

**Show Feed Link.** (Hide or Show) Show or hide the feed links URLs. A
feed link will show up as a feed icon in the address bar of most
browsers.

### Permissions Tab

This section shows permissions for web links. The screen shows as
follows.

To change the permissions for this extension, do the following.

- Select the **Group** by clicking its title located on the left.
- Find the desired **Action**. Possible Actions are:
  - **Configure ACL & Options.** Users can edit the options and
    permissions of this extension.
  - **Configure Options Only.** Users can edit the options except the
    permissions of this extension.
  - **Access Administration Interface.** Users can access user
    administration interface of this extension.
  - **Create.** Users can create content of this extension.
  - **Delete.** Users can delete content of this extension.
  - **Edit.** Users can edit content of this extension.
  - **Edit State.** User can change the published state and related
    information for content of this extension.
  - **Edit Own.** Users can edit own created content of this extension.
- Select the desired permission for the action you wish to change.
  Possible settings are:
  - ***Inherited.*** Inherited for users in this Group from the Global
    Configuration permissions of this extension.
  - ***Allowed.*** Allowed for users in this Group. Note that, if this
    action is Denied at one of the higher levels, the Allowed permission
    here will not take effect. A Denied setting cannot be overridden.
  - ***Denied.*** Denied for users in this Group.
- Click **Save** in **Toolbar** at top. When the screen refreshes, the
  Calculated Setting column will show the effective permission for this
  Group and Action.

## Toolbar

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Help:** Opens this help screen.

## Quick Tips

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here. When you set up menu items and create web links,
  you will be able to accept the default values for most options.
- All values set here can be overridden at the menu item, category, or
  web link level.
