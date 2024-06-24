<!-- Filename: Help6.x:Item_Ordering / Display title: Item Ordering -->

## Where Ordering Matters

The ordering of items in a list starts to matter when viewed from the Site
frontend. For example, suppose you have a number of featured articles that
you present in a Featured Article layout. The menu data entry form for that
layout offers a number of *Article Order* alternatives, one of which is
**Featured Articles Order**. The default order is the order in which the
articles are added. But what if you want one particular article to be first
in the list. If you have a Committee with articles on each member you may want
the Chairman to be in first position in the front page layout.

The same principle applies to Category Bolog layouts. You may have several
Committees, each in a different Category. In that case you filter the articles
list by Category and make the article on the Chairman first in the list.

## The Ordering Column

In a component list view the Ordering column is typically second from the left
(in left to right languages) immediately next to the Checkbox column. If the
list is not sorted by the ordering column it will be empty. In that case you
need to select the ordering column icon, a double chevron
(<span class="ms-1 icon-sort"></span>). Each time the icon
is selected the order toggles from ascending to descending. You need ascending
order (<span class="ms-1 icon-caret-up"></span>) to drag an
item upwards towards the top of the list. This is indicated in the sort order
field of the Search bar.

## Drag and Drop

With the ordering column set for use, each item will contain a vertical
ellipsis icon (<span class="icon-ellipsis-v"></span>). This icon can be
dragged upwards or downwards to change the list order. The new list order is
set in the database with a JavaScript call. There is no page reload.

It is tricky! You need to practice. And this is one of the occasions when
you may wish to set the list limit to *All*.
