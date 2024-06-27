<!-- Filename: Help6.x:List_Batch_Process / Display title: List Batch Process -->

## Purpose

Many of the Joomla Administrator pages are lists of items. Most familiar are
lists of Articles, Users and Menu Items. Typically, one or more items in a
list may be selected for a batch operation. For example, you may wish to add
a tag to 10 different articles or move a group of articles to a different
category.

The operations that can be performed vary with the list. The following
screenshot shows the batch dialog for Articles:

![Articles list batch screenshot](../../../en/images/common-elements/articles-list-batch.png "")

## Example: How to Batch Process a group of articles:

1.  Check checkboxes for one or more articles in the articles list.
2.  Select the Batch item from the Actions button in the Toolbar.
3.  Set one or more of the following values:
    - To change the **Language**, select the desired new language from
      the Set Language list box. This option is only present in multilingual
	  sites.
    - To change the **Access Level**, select the desired new access
      level from the Set Access Level list box.
    - To change the **Category**, select a category. To leave the
      category unchanged, use the default value of 'Select'.
      - To **copy** the articles to a different category, select the
        desired category from the category list box and check the Copy
        option. In this case, the original articles are unchanged and
        the copies are assigned to the new category and, if selected,
        the new language, access level, and tag.
      - To **move** the articles to a different category, select the
        desired category from the category list box and check the Move
        option. In this case, the original articles will be moved to a
        new category and, if selected, be assigned the new language,
        access level, and tag.
    - To add **Tags**, select the desired Tags from the dropdown or
      choose to keep the tags currently added to the original articles.
4.  When all of the settings are entered, click on Process to perform
    the changes. A message **Batch process completed successfully.**
    will show.
