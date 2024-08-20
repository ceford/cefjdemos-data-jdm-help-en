<!-- Filename: Help4.x:Multilingual_Associations / Display title: Multilingual Associations -->

## Description

In multilingual sites it is possible to create an item in one language and
have it linked to an equivalent item in one or more other languages. The link
is known as an **Association**. It must be made manually.

Associations can be created for Articles and their Categories, Contacts and
their Categories, Menu items and News Feeds and their Categories. Third party
extensions may also support Associations. 

The Multilingual Associations component allows side-by-side editing of
associated items without the need to go back and forth.

There is more explanation following the screenshot below.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Item Ordering](jdocmanual?article=help/common-elements/list-ordering).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to Access

* Select **Components → Multilingual Associations** From the Administrator Menu.
* Select an item from the **- Select Item Type -** dropdown list. 
* Select a language from the **- Select Languag -e** dropdown list.

## Screenshot

![Multilingual associations lis](../../../en/images/multilingual-associations/multilingual-associations-list.png)

In this screenshot an article named **Article (en-GB)** has been associated
with articles in 6 other languages. An article named **Lorem Ipsum (en-GB)**
has been associated with an article on one other language.

The articles do not have to have a language code in the title. The usually 
don't! There may be other *Lorem Ipsum* articles translated from English into
other languages but not yet associated.

The list only contains items where the language has been set. Any articles
with the language set to *All* will not be present.

## Reference Articles

The items in the **Title** column are the reference items for the selected
language. If you view the list with German selected you will see the same items
because all of the associated items are available in both languages.

If you view the list with other languages selected you are likely to see 
different items. For example, Dutch may show nothing in the Associations 
column because the translation exists but is has not been associated with 
English or German. And if you select Spanish the number of items in the list 
may change because the Lorem Ipsum article has not been translated into Spanish.

If you select an item from the **Title** column the reference item will appear
in the edit form but no target is selected. That is useful if you wish to edit
the reference item in the selected language. It is also required if you
wish to create a new associated item.

## Associations

If you wish to edit an existing association in side by side mode you select one
of the buttons in the **Associations** column. This loads the *Reference* and
*Target* items side by side.

## Not Associated

Select a button in the *Not Associated* column to create a new article 
associated with the reference article. It loads an edit form with the reference 
item alongside a new empty associated item. The language is pre-filled and
cannot be changed. 

## Quick Tips

- A menu-item in English can be more easily translated into French with
  the original and translation side by side. And then select Persian to
  translate from English to Persian too.
