<!-- Filename: Help4.x:Smart_Search:_Indexed_Content / Display title: Smart Search: Indexed Content -->

## Description

This screen shows a list of all the content items that have been indexed
in Smart Search. 

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

- Select **Components → Smart Search → Index** from the Administrator menu.

## Screenshot

![smart search indexed content](../../../en/images/smart-search/smart-search-indexed-content.png)

## Create an Index

Click on the **Index** button in the Toolbar. This will open a window to show 
the progress of the indexing operation. The indexing operation may take some
time depending on the number of content items on your site and the
number of search words and phrases contained in each content item. A
progress bar will indicate how much of the indexing process has been
completed so far. Do not close this window until indexing has been
completed. On sites with a large amount of content this may take a long
time (tens of minutes).

## Toolbar

- **Index** Runs the Smart Search indexer. A small popup window will
  appear with a progress bar which advances as the indexing process
  works through the content on your site. Do not close this popup window
  until the process is finished. On sites with a large amount of content
  this may take a long time (tens of minutes). You should run the
  indexer after new content has been introduced to your website that the
  Smart Search function is not automatically aware of. For example,
  batch importing new content where the importer does not automatically
  trigger Smart Search to index each new content item. NOTE: The Smart
  Search indexer can also be run from the command-line interface (CLI)
  if required. See Setting up automatic Smart Search indexing.
- **Actions** Select a checkbox to activate the dropdown list.
  - **Publish** Makes the selected items available to visitors to your website.
  - **Unpublish** Makes the selected items unavailable to visitors to
    your website.
- **Delete** Deletes the selected content items. Works with one or
  multiple content items selected. Deleting a content item from Smart
  Search only deletes it from the index and does not affect the content
  item itself.
- **Maintenance**
  - **Optimise**
  - **Clear Index** Purges the Smart Search index by emptying all index
    tables. To continue using Smart Search you must click on the Index
    toolbar icon after purging. WARNING: Purging the index also empties
    the content filters. You must manually re-enter the content filter
    settings after a Purge-Index cycle.
- **Statistics** Shows some basic statistics on Smart Search.

## Quick Tips

- If you run the indexer and get an "undefined null" error, then check
  the permissions on the Joomla `/logs` directory. The web server needs
  to have write permission to that directory for the indexer to work.
- If the list is empty then make sure that the Smart Search plug-in has 
  been enabled.
