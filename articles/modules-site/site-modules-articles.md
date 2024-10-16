<!-- Filename: Help5.x:Site_Modules:_Articles / Display title: Modules: Articles -->

## Description

The **Articles** module displays a list of articles. It is intended to replace
five other article modules: 

* [Modules: Articles - Archived](jdocmanual?article=help/modules/site-modules-articles-archived).
* [Modules: Articles - Category](jdocmanual?article=help/modules/site-modules-articles-category).
* [Modules: Articles - Latest](jdocmanual?article=help/modules/site-modules-articles-latest).
* [Modules: Articles - Most Read](jdocmanual?article=help/modules/site-modules-articles-most-read).
* [Modules: Articles - Newsflash](jdocmanual?article=help/modules/site-modules-articles-newsflash).

The **Articles** module options are configured primarily via four tabs: 

- The *Filtering Options Tab* is used to specify which articles are displayed.
- The *Display Options Tab* specifies how the articles are displayed in the module and which details are included.
- The *Ordering Options Tab* is used to configure article precedence.
- The *Grouping Options Tab* is used to configure article precedence. 

**Important:** The module only appears when there are one or more matching articles to display. If empty, the module will not appear.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Modules: Modules Tab](jdocmanual?article=help/modules/modules-module-tab).
* [The Modules: Menu Assignment Tab](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [The Modules: Advanced Tab](jdocmanual?article=help/modules/modules-advanced-tab).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Content → Site Modules** or **System → Manage Panel → Site Modules** 
  from the Administrator menu or **Site panel → Modules** from the Home Dashboard. 
  Then...
  - To create a new module: select the **New** button from the Toolbar in the
    *Modules* list. Then...
     - Select the **Articles** module.
  - To edit an existing module: find the module in the list of installed modules
    and select the title link in the **Title** column.

## Screenshot

![Articles module form module tab](../../../en/images/modules-site/modules-articles-module-tab.png)

## Form Fields

### Module Tab

#### Left Panel

- **Mode**
  - *Normal Mode* configures the module to display a static list of Articles. 
  - *Dynamic Mode* configures the module to detect whether or not it us using a Category view and will display the list of articles within that Category accordingly. When Dynamic Mode is chosen, it is best to leave the module set to display on all pages, as it will decide whether or not to display anything dynamically.
- **Articles to Display** The maximum number of articles to be displayed.
- **Category Filtering Type** Specifies how articles are filtered based on the categories provided in the *Category* field.
  - *Inclusive* Only articles with the specified categories are shown.
  - *Exclusive* Articles with the specified categories are excluded.
- **Category** Shows or excludes articles with the categories selected. This works in addition to other filtering parameters.
- **Child Category Articles** Only visible when the *Exclude or Include Articles* parameter is set to *Include*. Includes or excludes articles with categories that are subcategories of the categories provided in the *Category* field.
- **Category Depth** Only visible when the *Child Category Articles* parameter is set to *Include*. Specifies how many levels of subcategories are used.
- **Exclude or Include Articles** Includes or excludes specific articles.
- **Articles to Include** Only visible when the *Exclude or Include Articles* parameter is set to *Include*. If empty, all articles are included—otherwise only the articles selected are included.
- **Exclude Current Article** Only visible when the *Exclude or Include Articles* parameter is set to *Exclude*. Excludes or includes the current article. 
- **Articles to Exclude** Only visible when the *Exclude or Include Articles* parameter is set to *Exclude*. Specifies articles to be excluded from the list.

### Display Options Tab

![Articles module form module tab](../../../en/images/modules-site/modules-articles-display-options-tab.png)

- **Title Only (lists)** (*Yes/No*). If *Yes* the list of articles consists of only the article titles, linked to the article. All other options are hidden.
- **Layout**
  - *Vertical* Articles appear in a single vertical column.
  - *Horizontal* Articles appear in a maximum of 1-4 vertical columns, depending on the module width; module width is determined by module position, page layout, template, screen width, browser viewing width and other factors. 
- **Max. Number of Columns** This option appears only when Layout is set to Horizontal. It specifies the maximum number of columns in a horizontal layout (*2–4*).
- **Article Title** Shows or hides the article title.
- **Header Level** This option appears only when *Article Title* is set to *Show*. It specifies the HTML heading level of the article title (*h1–h5, none*). 
- **Title Link** This option appears only when *Article Title* is set to *Show*. 
  - *Yes* The title is a hyperlink to the article.
  - *No* The title is not a hyperlink to the article.
- **Author** Show or hide the article's author.
- **Category** Show or hide the article's category.
- **Category Link** Only appears if *Category* is shown.
  - *Show* Links the Category title to its Category page.
  - *Hide* Shows the Category title but does not link it.
- **Date** Shows or hides the article's date.
- **Date Field** This option appears only when *Date* is set to *Show*. It specifies which article date will appear: *Created Date/Modified Date/Start Publishing Date*.
- **Date Format** This option appears only when *Date* is set to *Show*. It specifies the date format, for example Y-m-d H-i-s. See the [PHP manual](https://www.php.net/manual/en/datetime.format.php) for formatting information.
- **Hits** Show or hide the number of times the article has been viewed.
- **Article Info Layout** Only appears if one of the metadata fields above (*Author, Category, Date, or Hits*) is shown. Specifies how article metadata is displayed:
  - *Multiline* Each parameter is displayed on its own line.
  - *Single Line* Parameters appear adjacent to each other in a single line, which may wrap depending on their size and module width.
- **Tags** Shows or hides an article's tags.
- **Trigger Plugin Events** Set to *Yes* to trigger additional plugin events to display additional content such as custom fields or voting information.
- **Introtext** Shows or hides the article's Intro text. The amount of text displayed is controlled by the *Introtext Limit (characters) parameter*.
- **Introtext Limit (characters)** This option appears only when *Introtext* is set to *Show*. It specifies the number of introductory characters displayed. If set to 0, the text of the entire article is displayed. 
- **Show Article Images** This option appears only when *Introtext* is set to *Show* and the *Introtext Limit (characters)* is set to zero (which displays the full article text). If set to *Show*, the article's images are displayed along with the text.
- **Show Intro/Full Image** Displays the article's intro image, full image, or no image above the article title and details.
- **"Read More" Link** Show or hide a "Read More" link below the article details.
- **Read More with Title** This option appears only when the *Read More* option is set to *Show*. It adds the title to the *Read More* link.
- **Read More Limit (characters)** This option appears only when the *Read More with Title* option is set to *Show*. It specifies the maximum number of characters in the title to appear in the *Read More* link. 

### Filtering Options Tab

![Articles module form module tab](../../../en/images/modules-site/modules-articles-filtering-options-tab.png)

- **Featured Articles**
  - *Show* Allows featured articles to appear in the list.
  - *Hide* Excludes featured articles from the list.
  - *Only* Shows only featured articles in the list.
- **Archived Articles** Specifies how archived articles appear in the list.
  - *None* Excludes archived articles from the list.
  - *Only* Shows only archived articles in the list.
- **Tags** If specified, restricts the list to only articles that have one or more of the tags specified.
- **Author Filtering Type** Filters the list by author.
  - *Inclusive* Restricts the list to articles from the specified authors only.
  - *Exclusive* Excludes articles by the specified author.
  - *Only from current user* Only displays articles authored by the current user.
- **Authors** List of authors to include or exclude. 
- **Author Alias Filtering Type** Filters the list by author alias.
  - *Inclusive* Restricts the list to articles from the specified author aliases only.
  - *Exclusive* Excludes articles by the specified author aliases.
- **Author Aliases** List of author aliases to include or exclude. 
- **Date Filtering** Specifies how articles are filtered by date.
  - *Off* No date filtering.
  - *Date Range* Restricts the list to articles with dates falling in the date range specified. 
  - *Relative Date* Restricts the list to articles that fall within a specified number of days of the current date.
- **Date Range Field** This option appears only when *Date Filtering* is set to *Date Range* or *Relative Date*. Specifies which article date to use when date filtering (*Created Date/Modified Date/Start Publishing Date*).
- **Start Date Range** This option appears only when *Date Filtering* is set to *Date Range*. It specifies the start date and time of the date range filter.
- **To Date** This option appears only when *Date Filtering* is set to *Date Range*. It specifies the end date and time of the date range filter.
- **Relative Date** This option appears only when *Date Filtering* is set to *Relative Date*. It specifies the number of days relative to the current date to include in the articles list.

### Ordering Options Tab

![Articles module form module tab](../../../en/images/modules-site/modules-articles-ordering-options-tab.png)

- **Article Field to Order By**
  - *Article Order* The order in which the articles are manually arranged in the administrator's *Content > Articles* screen.
  - *Featured Articles Order* The order in which featured articles are arranged in the administrator's *Content > Featured Articles* screen.
  - *Hits* Ordered by the number of page views (hits).
  - *Title* Ordered by the article title.
  - *ID* Ordered by the article ID number.
  - *Alias* The article navigational alias.
  - *Created Date/Modified Date/Start Publishing Date/Finish Publishing Date* Ordered by article date.
  - *Random* Random ordering each time the page is accessed or refreshed. *Ordering Direction* is ignored.

### Grouping Options Tab

![Articles module form module tab](../../../en/images/modules-site/modules-articles-grouping-options-tab.png)

The *Date Grouping Field* and *Month and Year Display Format* are only visible when a date related grouping is selected.

- **Article Grouping**
  - *None* No grouping.
  - *Year* Displays year as headings
  - *Month and Year* Displays month and year as headings.
  - *Author* Displays *Author Alias* or *Author* as headings. 
  - *Category* Categories appear as headings.
  - *Tags* Tags appear as headings. Articles with multiple tags appear under multiple headings.
- **Date Grouping Field** Displayed only when *Year* or *Month and Year* are selected. The article date on which to group (*Created Date/Modified Date/Start Publishing Date*).
- **Month and Year Display Format**  Displayed only when *Year* or *Month and Year* are selected. It specifies how to display the month and year heading. See the [PHP manual](https://www.php.net/manual/en/datetime.format.php) for formatting information.
- **Grouping Direction** Specifies how to order the group headings (*Ascending/Descending*).

## Front End Screenshot

*Example Front End Site images were obtained with the Cassiopeia Template.*

Articles module in the right sidebar showing titles only.

![Site screenshot of module with article titles only](../../../en/images/modules-site/modules-articles-site-titles.png)

Articles module in the right sidebar showing title, author, and date.

![Site screenshot of module with article titles author and date](../../../en/images/modules-site/modules-articles-site-title-author-date.png)

Articles module in the main top location showing introductory text and image, and a *Read More* button.

![Site screenshot of module top location and read more](../../../en/images/modules-site/modules-articles-site-top-text-image-readmore.png)

Articles module in the main top location configured for a horizontal layout with introductory text and image, and a *Read More* button.

![Site screenshot of module with article intro text, image and read more](../../../en/images/modules-site/modules-articles-site-text-image-readmore.png)

## Configuration Examples

The Articles module displays a list of articles in a variety of formats and layouts. It was designed with the goal of creating a single highly-configurable module capable of replacing the limited functionality of five separate articles modules. This section offers simple examples of how to configure the module for each of these roles.

## Articles - Archived

The *Articles - Archived* module displays a list of month/year headings for months which contain archived articles. The heading is a link to the archived articles view where the individual articles are displayed. The *Articles* module can be configured to achieve a similar result.

**Configuration Settings**

| Tab               | Parameter          | Setting |
|-------------------|--------------------|---------|
| Display Options   | Title Only (lists) | Yes     |
| Filtering Options | Archived Articles  | Only    |
| Grouping Options  | Article Grouping   | Month and Year |
| Grouping Options  | Month and Year Display Format | F, Y |


![Comparison of archived articles using each method](../../../en/images/modules-site/modules-articles-config-archived.png)

<big>*Notes*</big>

The *Articles - Archived* module displays a single link to a archived-articles page that displays the list of archived articles along with the ability to adjust the archive date. The *Articles* module displays the list of articles directly—grouping by month and year is optional. The list can be precisely filtered using the many different controls provided, and a wide range of display options are available to display additional article details. 

## Articles - Category

The *Articles - Category* module displays a list of links to articles within a specified category.

**Configuration Settings**

| Tab             | Parameter          | Setting |
|-----------------|--------------------|----|
| Module          | Category           | [specify the desired category and sub-categories]|
| Display Options | Title Only (lists) | Yes |

![Comparison of articles by category using each method](../../../en/images/modules-site/modules-articles-config-category.png)

## Articles - Latest

The *Articles - Latest* module displays a list of links to the most recent articles.

**Configuration Settings**

| Tab              | Parameter          | Setting |
|------------------|--------------------|----|
| Display Options  | Title Only (lists) | Yes |
| Ordering Options | Article Field to Order By | Start Publishing Date|
| Ordering Options | Ordering Direction | Descending |

![Comparison of articles latest using each method](../../../en/images/modules-site/modules-articles-config-latest.png)

<big>*Notes*</big>

The *Articles* module does not offer the *Touched* order found in the *Articles - Latest* module, but does have a number of ordering options not found in the *Articles - Latest* module. 

## Articles - Most Read

The *Articles - Most Read* module displays a list of links to articles with the most hits.

**Configuration Settings**

| Tab              | Parameter          | Setting |
|------------------|--------------------|----|
| Display Options  | Title Only (lists) | Yes |
| Ordering Options | Article Field to Order By | Hits |
| Ordering Options | Ordering Direction | Descending |

![Comparison of articles most read using each method](../../../en/images/modules-site/modules-articles-config-most-read.png)

## Articles - Newsflash

The *Articles - Newsflash* module displays the text of one or more articles. By default, only the article text is show; however, it can be configured to show the title, images, read-more links and more. Here it is configured to display the title title and text of multiple articles. In this example, the *Articles* module is configured to replicate this basic behavior.

**Configuration Settings**

| Tab              | Parameter          | Setting |
|------------------|--------------------|----|
| Ordering Options | Article Field to Order By | Start Publishing Date |
| Ordering Options | Ordering Direction | Descending |
| Display Options  | Title Only (lists) | No |
| Display Options  | Title Link         | No |
| Display Options  | Introtext          | Show |
| Display Options  | Introtext Limit (Characters) | 0 (for unlimited text) |

![Comparison of articles newsflash using each method](../../../en/images/modules-site/modules-articles-config-news-flash.png)
