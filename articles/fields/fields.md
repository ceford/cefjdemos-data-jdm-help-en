<!-- Filename: Help4.x:Component:_Fields / Display title: Component: Fields -->

## Description

Fields are used to display additional attributes of Articles, Contacts or Users.
The data are entered in an Administrator Edit form and displayed in the Site. 
An example:

Suppose you write articles about aspects of nature, sometimes Flowers, sometimes
Animals. One field you might wish to record and display for both is the 
Latin Name, requiring a text field. Another might be Habitat: Woodland, Pond,
Meadow, and so on, requiring a drop-down list. For flowers you may wish to 
record Flowering Season using 4 checkboxes, one for each season, or 12 
checkboxes, one for each month.

Empty fields in the input form are not displayed in the Site output, so you 
could keep all fields in one long list. However it is usually better to use 
categories for your Articles, say Flowers and Animals. Fields can be assigned 
to more than one Category. So Latin Name and Habitat fields would be assigned 
to both but Flowering Season would only be assigned to the Flowers category.

If a field is not assigned to a group it will appear in the Edit form in a 
Fields tab. If a field is assigned to a group it will appear in a tab with 
that name. So for the Flowers group it seems appropriate to create a group 
named Flower Data (or just Flowers, although using the same name for different 
things gets confusing). And for the other common fields you could use a Nature 
group.

### Common Elements

Some elements of the Fields list page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars "").
* [List Filters](jdocmanual?article=help/common-elements/list-filters "").
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers "").
* [List Item Ordering](jdocmanual?article=help/common-elements/list-ordering "").
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination "").
* [List Batch Process](jdocmanual?article=help/common-elements/list-batch-process "").

### Related Article

* There is a longer example of the use of [Fields and Field Groups](jdocmanual?article=user/fields/fields-and-field-groups)
* There is a Community Magazine article that includes the use of custom fields 
in a category to [Create a banner from Joomla's category description](https://magazine.joomla.org/all-issues/july-2024/create-a-banner-from-joomla-s-category-description).

## How to Access

* Select **Content → Fields** from tha Administrator menu.
* Select **Articles** form the Articles/Categories dropdown list.
  * Select the **New** button in the *Toolbar* to add a new field. Or...
  * Select a **Title** from the list to edit an existing field.

**Note:** There is a dropdown list that allows creation of Fields for a
Category, and Mail in the Contact component. They require some coding 
experience to prepare suitable template overrides.

## Screenshot

![Articles fields list](../../../en/images/fields/articles-fields-list.png)

There are 16 field types available, each implemented as a plugin. More are 
likely to become available in the future.

