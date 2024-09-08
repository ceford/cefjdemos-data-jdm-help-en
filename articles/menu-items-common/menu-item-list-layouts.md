<!-- Filename: Help6.x:Menu_Item_List_Layouts / Display title: Menu Item List Layouts -->

## Description

All menu items have a similar layout but some of the form fields and
some of the tabs change from type to type. This page describes the
**List Layouts** tab used for Category List layouts. 

## How to Access

* Select any **Site Menu** from the Administrator menu.
* Select the **New** button from the Toolbar.
* Select any Component menu item type that has an *List Layouts* tab.
* Select the **list Layouts** tab.

List layout parameters vary from component to component. The following examples
illustrate what to expect

### Articles Category List Layout

![Menu Item type Category List - list layouts tab](../../../en/images/menu-items/articles-category-list-list-layouts-tab.png)

- **Display Select** Show or hide the Display \# control that allows the user
  to select the number of articles to show.
- **Filter Field** Show or hide a text field in the Frontend where a user can
  filter the articles.
  - *Hide* Don't show a filter field.
  - *Title* Filter on article title.
  - *Author* Filter on the author's name.
  - *Hits* Filter on the number of article hits.
  - *Tags* Filter on the article tags.
  - *Month (published)* Filter on the month of published articles.
- **Table Headings** Show or hide a heading in the article list in the
  Frontend.
- **Date** Show a date in the list.
  - *Hide* Don't show any date.
  - *Created* Show the created date.
  - *Modified* Show the date of the last modification.
  - *Published* Show the start publishing date.
- **Date Format** Optional format string to control the format of the date.
- **Hits** Show or hide the number of hits for articles.
- **Author** Show or hide the name of the author.
- **Category Order**
  - *No Order* Articles are ordered only by the Article Order, without
	regard to Category.
  - *Title Alphabetical* Categories are displayed in alphabetical order
	(A to Z).
  - *Title Reverse Alphabetical* Categories are displayed in reverse
	alphabetical order (Z to A).
  - *Category Order* Categories are ordered according to the Order column
	entered in Articles: Categories.
- **Article Order**
  - *Featured Articles Order* Articles are ordered according to the Order
	column entered in Articles: Featured.
  - *Most Recent First* Articles are displayed starting with the most
	recent and ending with the oldest.
  - *Oldest First* Articles are displayed starting with the oldest and
	ending with the most recent.
  - *Title Alphabetical* Articles are displayed by Title in alphabetical
	order (A to Z).
  - *Title Reverse Alphabetical* Articles are displayed by Title in
	reverse alphabetical order (Z to A).
  - *Author Alphabetical* Articles are displayed by Author in
	alphabetical order (A to Z).
  - *Author Reverse Alphabetical* Articles are displayed by Author in
	reverse alphabetical order (Z to A).
  - *Most Hits* Articles are displayed by the number of hits, starting
	with the one with the most hits and ending with the one with the
	least hits.
  - *Least Hits* Articles are displayed by the number of hits, starting
	with the one with the least hits and ending with the one with the
	most hits.
  - *Random Order* Articles are displayed in random order.
  - *Article Order* Articles are ordered according to the Order column
	entered in Articles.
  - *Article Reverse Order* Articles are ordered reverse to the according
	of the Order column entered in Articles.
- **Date for Ordering** The date used when articles are sorted by date.
  - *Created* Use the article created date.
  - *Modified* Use the article modified date.
  - *Published* Use the article start publishing date.
- **Pagination** Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - *Hide* Pagination links not shown. *Note:* Users will not be able to
	navigate to additional pages.
  - *Show* Pagination links shown if needed.
  - *Auto* Pagination links shown if needed.
- **Pagination Summary** Show or hide the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.
- **\# Articles to List** Number of articles shown in the list.
- **Featured Articles**
  - *Show* Display featured articles and non-featured articles.
  - *Hide* Display only non-featured articles.
  - *Only* Display only featured articles.

### Featured Contacts List Layout

![Menu Item Featured Contacts list layouts tab](../../../en/images/menu-items/contacts-featured-contacts-list-layouts-tab.png)

- **Filter Field** Show or hide the list filter.
- **Display Select** Show or hide the number of items to show in the list.
  - If there are more items than this number, you can use the page
	navigation buttons (Start, Prev, Next, End, and page numbers) to
	navigate between pages. Note that if you have a large number of items,
	it may be helpful to use the Filter options, located above the column
	headings, to limit which items display.
- **Table Headings** Show or hide the list table Headings.
- **Position** Show or hide a Position column in the list of Contacts.
- **Email** Show or hide the Email display.
- **Phone** Show or hide the Phone display.
- **Mobile** Show or hide the Mobile display.
- **Fax** Show or hide the Fax display.
- **City or Suburb** Show or hide the City or Suburb display.
- **State or County** Show or hide the State or County display.
- **Country** Show or hide the Country display.
- **Pagination** Shoe or hide Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
	The following options are available.
	- *Use Global* Use the default value from the component options screen.
	- *Auto* Pagination links shown if needed.
	- *Show* Pagination links shown if needed.
	- *Hide* Pagination links not shown. Note: In this case, Users will not
	  be able to navigate to additional pages.
- **Pagination Summary** Show or hide the current page number and total
  pages (e.g., "Page 1 of 2") at the bottom of each page. Use Global
  will use the default value from the component options.

### News Feed List Layouts

![Menu Item list all News Feed Categories list layouts tab](../../../en/images/menu-items/news-feeds-list-all-categories-tree-list-layouts-tab.png)

- **Filter Field** Show or hide a Filter field for the list.
- **Display Select** Show or hide the Display \# control that allows the user 
  to select the number of items to show in the list.
- **Table Headings** Show or hide Table Headings above a list.
- **\# Articles** Show or hide the number of Articles in each News Feed. This
  value may be overridden in each individual News Feed.
- **Feed Links** Show or hide the feed link URLs.
- **Pagination** Hide or Show Pagination support. Pagination provides
  page links at the bottom of the page that allow the User to navigate
  to additional pages. These are needed if the listed items will not fit
  on one page.
	The following options are available.
	- *Use Global:* Use the default value from the component options screen.
	- *Auto:* Pagination links shown if needed.
	- *Show:* Pagination links shown if needed.
	- *Hide:* Pagination links not shown. Note: In this case, Users will not
	  be able to navigate to additional pages.
- **Pagination Results** Show or hide the current page number and total number
  of pages (for example *Page 1 of 2*) at the bottom of each page. Use Global
  will use the default value from the component options.

### Tags List Layouts

![Compact List of Tagged Items details tab](../../../en/images/menu-items/tags-compact-list-of-tagged-items-list-layouts-tab.png)

- **Item Image** Show or hide the image for each item.
- **Item Description** Show or hide the description for each item in the list. 
  The length may be limited using the Maximum Character option.
- **Maximum Characters** The maximum number of characters to display
  from the description in each tag.
- **Filter Field** Show or hide the Filter Field, a text field  where a user 
  can enter a field to be used to filter the articles shown in  the list.
- **Table Headings** Show or hide the Table Headings.
- **Display Select** Show or hide the control that allows the user to select 
  the number of items to show in the list. 
- **\# Items to List** The number of tagged items to list on a page.
- **Pagination** Show or hide the Pagination support at the bottom of the page 
  that allow the User to navigate to additional pages. 
- **Pagination Summary** Show or hide the current page number and total
  pages (for example, *Page 1 of 2*) at the bottom of each page. 
- **Date** Show or hide a date in the list. 
- **Date Format** Optional format string to control the format of the
  date (if shown). If left blank, the date will use the DATE_FORMAT_LC1
  format from the language file (for example, `D M Y` for *31 December
  2012* or `m-d-y` for *12-31-12*).
