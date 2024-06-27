<!-- Filename: Help4.x:Banners:_New_or_Edit_Client / Display title: Banners: Edit Client -->

## Description

The Banners: Edit Client form is used to enter or change Banner Client data.
At least one Banner Client is required before a Banner can be created.

### Common Elements

Some aspects of the *Banners: Edit Client* page are covered in separate Help
articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars "").

## How to Access

- Select **Components → Banners → Clients** in the Administrator menu.
  - To create a new Client select the **New** button in the Toolbar.
  - To edit an existing Client select the **name** in the Client column.

## Screenshot

![Banners edit client](../../../en/images/banners/banners-edit-client-details-tab.png)

## Form Fields

- **Name:** The name of this client.

### Details Tab

- **Contact Name:** The name of the contact person for this client.
- **Contact E-mail:** The e-mail address of the banner client.
- **Purchase Type:** The purchase type of the banner. This is used to
  indicate how the banner client purchased the display time for the
  banner - monthly, yearly, etc...
- **Track Impressions:** Whether or not to track the number of times the
  banner is displayed to web site visitors.
- **Track Clicks:** Whether or not to track the number of times the
  banner is clicked by web site visitors.
- **Additional Information:** Enter any extra information you want to
  save for this client.
- **Status**: Published status of the item. Possible values are:
  - *Published*: The item is published. This is the only state that will
    allow regular website users to view this item.
  - *Unpublished*: The item is unpublished.
  - *Archived*: The item has been archived.
  - *Trashed*: The item has been sent to the Trash.
- **Version Note**. Optional field to identify this version of the item
  in the item's Version History
  window.

### Metadata Tab

![Banners edit client metadata tab](../../../en/images/banners/banners-edit-client-metadata-tab.png)

- **Keywords**. Optional entry for keywords. Must be entered separated
  by commas (for example, "cats, dogs, pets") and may be entered in
  upper or lower case. (For example, "CATS" will match "cats" or
  "Cats"). Keywords can be used in several ways:
  1.  To help Search Engines and other systems classify the content of
      the Article.
  2.  In combination with Banner tags, to display specific Banners based
      on the Article content. For example, say you have one Banner with
      an ad for dog products and another Banner for cat products. You
      can have your dog Banner display when a User is viewing a
      dog-related Article and your cat Banner display for a cat-related
      Article. To do this, you would:
      - Add the keywords "dog" and "cat" to the appropriate Articles.
      - Add the Tags "dog" and "cat" to the appropriate Banners in
        Banners: Edit.
      - Set the Banner module Parameter 'Search By Tags' to "Yes" in
        the Site Modules: Banners list.
  3.  For articles only, in combination with the Articles - Related module,
      to display Articles that share at least one keyword in common. For
      example, if the current Article displayed has the keywords "cats,
      dogs, monkeys", any other Articles with at least one of these
      keywords will show in the 'Articles - Related' module.
- **Use Own Prefix:** Whether or not to use the banner's prefix or that
  of the client. Select *No* if you want to use the prefix of the banner
  client.
- **Meta Keyword Prefix:** When matching meta keywords, only search for
  meta keywords with these optional prefixes. This improves performance.
