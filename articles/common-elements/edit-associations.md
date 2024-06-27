<!-- Filename: Help4.x:Edit_Associations / Display title: Edit Associations -->

## Purpose

In multilingual sites it is possible to create an item in one language and
have it linked to an equivalent item in one or more other languages. The link
is known as an **Association**. It must be made manually.

The Associations tab does this in the edit form of various components: article,
category, contact, menu item and news feed.

## Example: Articles: Edit Associations Tab

![Article edit associations tab](../../../en/images/common-elements/articles-edit-association-tab.png "")

In this illustration an article has been created in German. It is the one being
edited. The associations list shows the available language other than German.
An association with the same article in English has been made. It can be Edited
or Cleared. Associations with the same article in other languages can be made
by choosing an article from articles already available or by creating a new
article.

The **Select** button opens a modal dialog containing a list of articles in the
selected language to choose from.

The **Create** button opens a modal dialog containing a **New Article** form with the
Language already set.

The **Edit** button opens a modal dialog containing an **Edit Article** form.

The **Propagate** button is a little difficult to understand. Suppose you have
two articles named *Lorem Ipsum (fr-FR)* and *Lorem Ipsum (en-GB)* that are
already associated. You decide to add a third article and associate it with the
two already associated.

* Select the **New** button in the Articles list Toolbar.
* Enter a Title and select a **Language**. The default *All* does not work for
    Multilingual Associations.
* Select the **Associations** tab.
* For a **language** which you know has an existing association that you wish
    to associate with your new article:
    * Use the **Select** button to find and select it. For example,
    *Lorem Ipsum (fr-FR)*. The newly selected Association will have a
    *Propagate* button.
* Select the **Propagate** button.
* Any other items associated with *Lorem Ipsum (fr-FR)* will be associated with
    your new item, in this example *Lorem Ipsum (de-DE)* will also be selected
    and have a *Propagate* button.
* Select the **Save & Close** button.

