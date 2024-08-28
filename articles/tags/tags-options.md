<!-- Filename: Help4.x:Tags:_Options / Display title: Tags: Options -->

## Description

Used to set global defaults for menu items that display tags. These
default values will be used when "Use Global" is selected for an option
in a Tags menu item. For example, to show the 'Tag Name' for a Tagged
Items List in your Tags menu items, then set that option to "Show" here
and it will be the default value. You do not need to set any of these
options. Your Joomla site will work with the default settings.

### Common Elements

Some aspects of this page are covered in separate Help
articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Components → Tags** from the Administrator menu. Then...
  - Select the **Options** button in the Toolbar.

## Screenshot

![tags options tagged items tab](../../../en/images/tags/tags-options-tagged-items-tab.png)

## Form Fields

### Tagged Items Tab

- **Default Tagged Items Layout** Choose a default layout to for tagged
  items. This layout will be used when a user clicks on a tag that
  doesn't have a menu item defined.
- **Enable Versions** (Yes/No). Whether or not to save version history
  for this component. If No, version history will not be saved for
  component items or for this component's categories.
- **Maximum Versions** The maximum number of versions to store for an
  item. If an item is saved and the maximum number of versions has been
  reached, the oldest version will be deleted automatically. If set to
  0, then versions will never be deleted automatically. Also, specific
  versions may be flagged as "Keep Forever" and will not be deleted
  automatically. Note that versions may be deleted manually using the
  Delete button in the Version History
  screen.
- **Show Tag Name** For a layout with one tag, show the tag name.
- **Tag Image** For a layout with one tag, show the image for the tag.
- **Tag Description** Show or hide a description for the tag (only used
  when a single tag is selected).
- **Image** Show the tag image (full image).
- **Order** Order items will be displayed in.
- **Direction** Sort order. Descending is highest to lowest. Ascending
  is lowest to highest.
- **Table Headings** Show or hide the headings in list layouts.
- **Show Date** Whether to show a date column in the list of articles.
  Select Hide to hide the date, or select which date you wish to show.
- **Item Images** Shows the first image for each item in the list.
- **Item Description** Whether to show or hide the description for each
  item in the list. The length may be limited using the Maximum
  Characters option.
- **Maximum Characters** The maximum number of characters to display
  from the description in each tag.

### Item Selection Tab

![tags options tagged items tab](../../../en/images/tags/tags-options-item-selection-tab.png)

- **Minimum Search Length** This setting controls the minimum character
  length for the search and adding tags using the tags field Ajax mode.
- **Match Type** All will return items that have all of the tags. Any
  will return items that have at least one of the tags.
- **Child Tags** Include or exclude child tags from the result list for
  a tag.
- **Maximum Items** The maximum number of results to return.
- **Language Filter** Optionally filter the list of tags based on
  language.

### List All Tags Tab

![tags options list all tags tab](../../../en/images/tags/tags-options-list-all-tags-tab.png)

- **Default List All Tags Layout** Choose a default layout for List of
  all tags.
- **Order** Order items will be displayed in.
- **Direction** Sort order. Descending is highest to lowest. Ascending
  is lowest to highest.
- **Item Images** Shows the first image for each item in the list.
- **Tag Description** Shows or hides the description for each tag
  listed.
- **Maximum Characters** The maximum number of characters to display
  from the description in each tag.
- **Hits** Display the number of hits.

### Shared Layout Tab

![tags options shared layout tab](../../../en/images/tags/tags-options-shared-layout-tab.png)

- **Filter Field** Whether to show a Filter field for the list. Select
  Hide to hide the filter field.
- **Display Select** Whether to show or hide the Display Select
  dropdown listbox.
- **Pagination** Show or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the Information will not fit
  on the page.
- **Pagination Results** Show or hide pagination results information,
  for example, "Page 1 of 4".

### Data Entry Tab

![tags options data entry tab](../../../en/images/tags/tags-options-data-entry-tab.png)

- **Tag Entry Mode** Ajax mode searches tag while typing and allows you
  on the fly tag creation. Nested tags show you a nested view with all
  the available tags.

### Integration Tab

![tags options tagged items tab](../../../en/images/tags/tags-options-integration-tab.png)

- **Show Feed Link** Show or hide an RSS Feed Link. (A Feed Link will
  show up as a feed icon in the address bar of most modern browsers).

## Tips

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here. When you set up menu items and create tags, you
  will be able to accept the default values for most options.
