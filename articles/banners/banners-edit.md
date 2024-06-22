<!-- Filename: Help4.x:Banners:_Edit / Display title: Banners: Edit -->

## Description

Used to add or edit banners which can be displayed on your Joomla!
website. Remember to create at least one Banner Client and one Banner Category
before creating any Banners.

## How to Access

To '**add'** a new Banner or '**edit'** an existing Banner, navigate to
the Banners list:

- Select **Components → Banners → New** to create a new Banner.
- Select **Components → Banners** and click on a Banner name to
  '**Edit'** an existing Banner.

## Screenshot

A banner may be a clickable image or some custom code. The Image Type is
shown in the screenshot below. The custom type has the image selection
box replaced with a code text area.

<img
src="https://docs.joomla.org/images/thumb/d/da/Help-4x-Components-Banners-Banners-Edit-screen-en.png/800px-Help-4x-Components-Banners-Banners-Edit-screen-en.png.jpeg"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/da/Help-4x-Components-Banners-Banners-Edit-screen-en.png/1200px-Help-4x-Components-Banners-Banners-Edit-screen-en.png.jpeg 1.5x, https://docs.joomla.org/images/d/da/Help-4x-Components-Banners-Banners-Edit-screen-en.png 2x"
data-file-width="1440" data-file-height="1208" width="800" height="671"
alt="Banners edit details tab" />

## Form Fields

- **Name** The name of the Banner. This is the name that will display
  in the *Name* column of the Banners list.
- **Alias** The internal name of the item. Normally, you can leave this
  blank and Joomla will fill in a default value Title in lower case and
  with dashes instead of spaces.

## Details Tab

### Left Panel

- **Type**. The type of banner to display. Options are an image file or
  custom HTML code.
  - **Image**. Image file to display for the banner. Click the *Select*
    button to browse and select the image file to use. Use the Media
    page to upload Banner image files to your site. Images for Banners
    have to be in the https://docs.joomla.org/images/banners/ directory.
    - **Width**. The fixed width to resize the banner image to. Leave
      this blank if you want to use the actual width of the banner image
      file.
    - **Height**. The fixed height to resize the banner image to. Leave
      this blank if you want to use the actual height of the banner
      image file.
    - **Alternative Text**. Text to display in place of the banner image
      in the event the image cannot be displayed.
    - **Alternative Text**. Alternative text for the Banner's image.
  - **Custom**. Select Custom if you want to enter a custom code for
    your banner.
    - **Custom Code**. Use {CLICKURL} and {NAME} to merge 'Click URL'
      and 'Name' values respectively into your custom code. For example:
      `<a href="{CLICKURL}"><img src="enter url to image" alt="{NAME}" title="{NAME}"></a>`.
      Another option is to enter an HTML custom code. For example:
      `<div class="yourclass"><a href="https://yourdomain.com"><img src="pathofyourimage"></a></div>`
- **Click URL**. The URL to navigate to when the User clicks on the
  Banner.
- **Description**. Enter a description for the Banner.

### Right Panel

- **Status**. The published status of the item.
- **Pinned**. *(Yes or No)* Whether or not the Banner is "pinned". If
  one or more Banners in a Category are designated "sticky," they will
  take priority over Banners that are not sticky.
    - For example, if two Banners in a Category are pinned and a third Banner
    is not pinned, the third Banner will not display if the Banner display
    module setting is "Pinned, Randomise" or "Pinned, Ordering." Only the
    two pinned Banners will display. If the pinned banners have a fixed
    number of impressions, once those impressions are used up, the pinned
    banners will no longer display, and the non-pinned banners will begin
    displaying automatically.
- **Language**. Item language.
- **Version Note**. Optional field to identify this version of the item
  in the item's Version History
  window.

### Banner Details tab

<img
src="https://docs.joomla.org/images/0/09/Help-4x-Components-Banners-Banners-Edit-Banners-Details-Tab-en.png"
decoding="async" data-file-width="600" data-file-height="411"
width="800" height="548"
alt="Banners edit banner details tab" />

- **Max. Impressions.** The number of Impressions purchased for this
  Banner. Impressions are the number of times a Banner will be displayed
  on a page. Check the 'Unlimited' checkbox if an unlimited number of
  Impressions is allowed.
- **Total Impressions.** The number of times this Banner has been
  displayed on a web page to a user. No entry is allowed. You can reset
  this number to 0 by pressing the 'Reset impressions' button.
- **Total Clicks.** The number of times this Banner has been clicked. No
  entry is allowed. You can reset this number to 0 by pressing the
  'Reset clicks' button.
- **Client.** The Client for this Banner. Select one from the drop-down list
box of existing Clients.
- **Purchase Type:** The purchase type of the banner. This is used to
  indicate how the banner client purchased the display time for the
  banner.

The following options are: (*-Use Client Default-, Unlimited, Yearly,
Monthly, Weekly, Daily*).

- **Track Impressions** Whether or not to track the number of times the
  banner is displayed to web site visitors.
- **Track Clicks** Whether or not to track the number of times the
  banner is clicked by web site visitors.

### Publishing Tab

<img
src="https://docs.joomla.org/images/9/90/Help-4x-Components-Banners-Banners-Edit-Publishing-Options-Tab-en.png"
decoding="async" data-file-width="600" data-file-height="680"
width="800" height="907"
alt="Banners edit banner publishing tab" />

- **Start Publishing**. Date the Banner will publish and be available
  for website. Enter the date (time optional) in format
  *year-month-date hrs:min:sec* as '2013-01-07 14:10:00' or alternatively,
  use the modal 'pop up' window and select a date from the calendar.
- **Finish Publishing**. Date the Banner will stop being published and
  will no longer be available for website. Enter the date (time optional) in f
  ormat *year-month-date hrs:min:sec* as '2013-01-07 14:10:00' or
  alternatively, use the modal 'pop up' window and select a date from the
  calendar.
- **Created Date**. Date the item(Article, Category, Weblink, etc.) was
  created.
- **Created By**. Name of the Joomla User who created this item. This
  will default to the currently logged-in user. If you want to change
  this to a different user, click the Select User button to select a
  different user.
- **Created by Alias**. This optional field allows you to enter in an
  alias for this Author for this Article. This allows you to display a
  different Author name for this Article.
- **Modified Date**. Date of last modification.
- **Modified By**. Username who performed the last modification.
- **Revision**. Number of revisions to this item.
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
- **Use Own Prefix.** Whether or not to use the banner's prefix or that
  of the client. Select *No* if you want to use the prefix of the banner
  client.
- **Meta Keyword Prefix:** When matching meta keywords, only search for
  meta keywords with these optional prefixes. This improves performance.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.
- **Save as Copy**. Saves your changes to a copy of the current item.
  Does not affect the current item. This toolbar icon is not shown if
  you are creating a new item.
- **Cancel**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. Or
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Versions**. Opens the Item Version History window to show any prior
  versions of this item. This allows you to view older versions of this
  item and, if desired, restore from an older version. See Version History
  for more information.
- **Help**. Opens this help screen.

## Quick Tips

- Banners are placed on specific pages by adding Modules of type
  'Banners' using the Modules list.
- If you have a series of Banners that you would like to display on one
  or more pages in random order:
  1.  Create the Banners you wish to include, making sure they have the
      same Client and Category.
  2.  Create a Banner Module for this Client and Category, and in the
      Menu Assignment pick the Menu Selections for the module to display
      on.
  3.  In the Banner Module, set the 'Randomise' value to 'Sticky,
      Randomise'.

With these settings, the different Banners for that Client and Category
will display on the selected pages in random order.
