<!-- Filename: Help6.x:List_Filters / Display title: List Filters -->

## Purpose¶

Most components have list views that display items from the database. There
may be hundreds of items, thousands perhaps, or even millions. So List Filters
are used to reduce the displayed list to those likely to contain the one you
need to work on.

For example, trashed items are not usually displayed by default. If you wish
to see your trashed items you need to set the **- Select Status -** filter to
**Trashed**. The following screenshot shows the Filters for the Articles page.

## Articles List Filter Options¶

![Articles list](../../../en/images/common-elements/articles-list-filter-options.png)

To **show** or **hide** the Options select the **Filter Options** button. Note
that the Options are always displayed on return to any page in which an Option
has been selected.

The number of Options displayed varies with the component. Even the Content
component, which displays the Articles list, may have additional filters. For
example, a **- Select Stage -** filter is displayed if the Content component
has **Workflows** enabled.

## The Search Bar

### Search by Text

*Hover* or *Select* the *Search* field to see a *Tooltip* or hear an *Audio*
equivalent indicating which fields will be searched. The default behaviour
is to search for the entered text within the title text.

The content component allows a prefix to search within the ID, Author or
Content. Each of those terms needs a colon but may be in any *Case*, For
example *ID:19* or *Author:John* or *content:lorem ipsum*.

To perform a search, enter part of the search term and select the **Search**
icon (<span class="filter-search-bar__button-icon icon-search" aria-hidden="true"></span>).

### Filter Options and Clear

The **Filter Options** button is used to toggle view of the various filters. If
there are no Filters for a component this button will be absent.

The **Clear** button is used to clear all filters and restore the list to its
unfiltered state. If there are no filters for a component this button will be
absent.

### Result Order

The order in which results are presented is user selectable. For articles, the
default order is *ID Descending*, which puts the most recent articles at the
top of the list. But you may wish to search for articles by most hits,
*Hits descending*, or articles that will soon disappear,
*Finish Publishing ascending*.

The result order my be changed by selecting an order icon in the list
column headings. The default *ID Descending* icon is represented by a
down caret (<span class="ms-1 icon-caret-down" aria-hidden="true"></span>).
It changes to an up caret if the sort order is reversed, *ID Ascending*.

### Number of Results

The number of results in a list is set in the Global Configuration page, Site
tab, Default List Limit field. The default value for a new installation is 20.

There are occasions when this is not convenient. You may wish to see *50* or
*100*. Be careful if choosing *All*. It may take a long time to retrieve
results and render the page. The server my run of memory or time and trigger
a fatal error. And your browser my take a long time to display the page.

The default value for this documentation set has been set to 5 because that is
sufficient for illustrative screenshots.

## How to Use Filters

The purpose of each filter should be self evident from its unfiltered selector
label. For example, the Articles **- Select Status -** Filter offers five
choices: *Trashed*, *Unpublished*, *Published*, *Archived* and *All*. The last
is functionally equivalent to unfiltered (*- Select Status -*).

When a filter option is changed the page automatically reloads with the new
results filtered by the new filter option.

## Hide Columns

Some component lists have many columns and may be too wide for your screen. This
is especially true of some translations of the column heading text. The most
annoying result is that the Titles may wrap and be difficult to read.

To make more space for the Title you can open the Columns drop-down list and
select less important columns to hide. Then close the Columns list again. The
effect is immediate as it uses JavaScript to hide the selected columns in the
layout. They are still present in the page.

Your settings are saved by your browser so will be used until you change then
again, even if you logout and login again.
