<!-- Filename: Help4.x:Smart_Search:_Options / Display title: Smart Search: Options -->

## Description

The * Smart Search: Options* page allows setting of parameters used
globally for Smart Search.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **Components → Smart Search → Index** from the
  Administrator menu. Then...
  - Select the Options button from the Toolbar.

## Screenshot

![Smart search options smart search tab](../../../en/images/smart-search/smart-search-options-smart-search-tab.png)

## Form Fields

### Smart Search Tab

- **Word Match** Method for matching words.
- **Result Taxonomy** Show or hide ...
- **Result Description** Show or hide the description with search results.
- **Description Length** Number of characters of the description in
  search results. The default is 255.
- **Result Date** Show or hide the start and end date filters in
  the advanced search.
- **Result URL** Show or hide the result item's URL in search
  results. The URL is located under the description.
- **Gather Search Statistics** Record the search phrases
  submitted by visitors.
- **Allow Empty Search** If a filter is selected, allows an empty
  search string to initiate a search with the filter constraints.
- **Search Suggestions** Show or hide automatic search suggestions.
- **Did You Mean** Show or hide whether to suggest alternative search 
  terms when a search produces no result.
- **Query Explanation** Show or hide a detailed explanation of the
  search requested.
- **Advanced Search** Show or hide whether users should be able to see
  advanced search options.
- **Advanced Tips** Show or hide whether users should be able to see
  advanced search tips.
- **Expand Advanced Search** Show or hide whether the advanced search
  options should be expanded by default.
- **Sort Field** Field to sort the search results.
- **Sort Direction** Direction to sort search results.
- **Highlight Search Terms** Toggle whether search terms should be
  highlighted in search results.
- **Enable OpenSearch** (Yes/No)
- **OpenSearch Name** Name displayed for this site as a search provider.
- **OpenSearch Description** Description displayed for this site as a
  search provider.

### Index Tab

![Smart search options index tab](../../../en/images/smart-search/smart-search-options-index-tab.png)

- **Search for Phrases** Disabled to improve performance or enable to
  improve quality of results.
- **Indexer Batch Size** The batch size controls how many items are
  processed per batch. Large batch sizes require lots of memory whereas
  small batch sizes require less memory but execute more requests which
  tends to take longer.
- **Title Text Weight Multiplier** The multiplier is used to control
  how much influence matching text has on the overall relevance score of
  a search result. A multiplier is considered in relationship to the
  other multipliers. The title text comes from the title of the content
- **Body Text Weight Multiplier** The multiplier is used to control how
  much influence matching text has on the overall relevance score of a
  search result. A multiplier is considered in relationship to the other
  multipliers. The body title text comes from the summary and/or body of
  the content.
- **Metadata Weight Multiplier** The multiplier is used to control how
  much influence matching text has on the overall relevance score of a
  search result. A multiplier is considered in relationship to the other
  multipliers. The metadata comes from a number of sources including the
  meta keywords and meta description, author names, etc.
- **Path Text Weight Multiplier** The multiplier is used to control how
  much influence matching text has on the overall relevance score of a
  search result. A multiplier is considered in relationship to the other
  multipliers. The path text comes from the SEF URL of the content.
- **Misc. Text Weight Multiplier** The multiplier is used to control
  how much influence matching text has on the overall relevance score of
  a search result. A multiplier is considered in relationship to the
  other multipliers. The miscellaneous text comes from a number of
  sources including comments and other associated data.
- **Enable Logging** Enable this option to create a log file in your
  site's logs folder during the index process. This file is useful for
  troubleshooting issues with the index process. It is recommended that
  logging be disabled unless necessary.
- **Default Language** (Default Site Language/None/English (United Kingdom))
- **Filter Common Words** (Yes/No)
- **Filter Numeric Terms** (Yes/No)
