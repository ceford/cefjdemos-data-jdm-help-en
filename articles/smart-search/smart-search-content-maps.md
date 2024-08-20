<!-- Filename: Help4.x:Smart_Search:_Content_Maps / Display title: Smart Search: Content Maps -->

## Description

This page shows the content maps currently in the Smart Search index.
Content maps allow you to cross-reference your indexed content
(articles, etc) to related meta information such as the category in
which it resides. Each content item that is indexed by Smart Search is
added to one or more content maps that can be used as filters when
searching the index.

Content maps are split into two parts:

- Map Group: These are super-containers for a particular type of
  information. For example, a Map Group could be "Type", "Category",
  "Event", "Language" or "Author".
- Content Map: Content maps are the actual values for the meta
  information in a particular Map Group. The Content Maps are, for
  example, the names of the categories or authors.

These Map Groups and Content Maps are what make up the advanced search
panel available on the front-end. For each Map Group there can be a
drop-down select list and the Content Maps are added as values to the
respective list. More advanced site builders can override the default
layouts and use multi-select lists or checkboxes instead.

It's important to note that Map Groups and Content Maps from different
content types are merged into the one list. A Joomla article in a
category called "News" and a news feed or contact in a category named
the same are mapped to the same Content Map in the same Map Group. This
is a little like tagging different types of content with the same label.
The effect is that your site visitor does not have to know how your
content is classified in order to set the correct filters to find it.

The content maps screen shows all the Map Groups within the Smart Search
index together with a number indicating the number of Content Maps
within that Map Group and the items within a Contrent Map. Clicking on a
Map Groups number allows you to see the Content Map within that Map
Group together with the number of content items that belong to that
Content Map. A content item can belong to multiple Content Maps within a
Map Group as well as to multiple Map Groups.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Item Ordering](jdocmanual?article=help/common-elements/list-ordering).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

### Tutorial

* If you are new to Smart Search then you should read the [Smart Search
  quickstart guide](https://docs.joomla.org/Smart_Search_quickstart_guide "Smart Search quickstart guide").

## How to access

- Select **Components → Smart Search → Content Maps** from the
  Administrator menu.

## Screenshot

![smart search content maps](../../../en/images/smart-search/smart-search-content-maps.png)

## Column Headers

- **Status** The status of the content item within Smart Search. Changing the 
  status only affects whether the content item is available in search results 
  and does not affect the content item itself.
- **Title** The title of the Map Group or Content Map.
- **Maps** The number of maps inside the Map Group. Selecting the
  number wil show the maps inside the Map Group.
- **Published Indexed Content** The number of published content items
  in the Map Group. Selecting the number will show the published content
  items inside the Map Group.
- **Unpublished Indexed Content** The number of unpublished content
  items in the Map Group. Selecting the number will show the unpublished
  content items inside the Map Group.

## Toolbar

- **Actions** Reveals a list of actions for selected Items. Check one
  or more Item checkboxes to activate the list.
  - **Publish**. Makes the selected Map Groups or Content Maps available
    to visitors to your website.
  - **Unpublish.** Makes the selected Map Groups or Content Maps
    unavailable to visitors to your website. An unpublished Map Group will
    not be displayed as a select list in the front-end. An unpublished
    Content Map will not appear in the select list for the Map Group in
    which it occurs. Re-indexing does not change the published state of
    Map Groups or Content Maps.
- **Delete** Deletes the selected Map Groups or Content Maps. Works
  with one or multiple Map Groups or Content Maps selected. You can
  recover deleted Map Groups or Content Maps by running the Smart Search
  indexer again.
- **Statistics** Shows some basic statistics on Smart Search.
