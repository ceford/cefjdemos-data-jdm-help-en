<!-- Filename: Help4.x:Menu_Item:_Iframe_Wrapper / Display title: Iframe Wrapper -->

## Description

The *Iframe Wrapper* menu item type is used to create a page with embedded
content using an IFrame with control of iframe size, width and height.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Details Tab](jdocmanual?article=help/menu-items-common/menu-item-details).
* [The Link Type Tab](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [The Page Display Tab](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [The Metadata Tab](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [The Associations Tab](jdocmanual?article=help/common-elements/edit-associations).
* [The Module Assignment Tab](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## How To Access

To create a new IFrame Wrapper Menu Item:

- Select **Menus → \[name of the menu\]** from the Administrator
  menu (for example, **Menus → Main Menu**). Then...
  - Select the **New** button in the Toolbar. Then...
  - Select the Menu Item Type Select button.
  - In the modal dialogue select the Users item to open a list and then
    select the **Iframe Wrapper** menu item.

To edit an existing *IFrame Wrapper* menu item:

- Select its Title in the *Menu: Items* list.

## Screenshot

![Iframe wrapper details tab](../../../en/images/menu-items/wrapper-iframe-wrapper-details-tab.png)

## Form Fields

### Scroll Bar Parameters Tab

![Iframe wrapper scroll bar parameters tab](../../../en/images/menu-items/wrapper-scroll-bar-parameters-tab.png)

- **Width** Width of the IFrame Window. Enter a number of pixels or a 
  percentage. For example, *550* means 550 pixels; *75%* means 75% of the 
  `<main>` container width. An absolute number of pixels may be wider than
  the container and cause layout problems. If in doubt, try 100%.
- **Height** Height of the IFrame Window. Enter a number of pixels. For example,
  *550* means 550 pixels.

### Advanced Tab

![Iframe wrapper advanced tab](../../../en/images/menu-items/wrapper-advanced-tab.png)

- **Auto height** Automatically set height to the height of external page.
  *Note* - this will only work if the external page is on the **same
  domain**. For example, `http://www.example.com` the external html must
  be in the `example.com` root file structure. Sub domains will not
  work, as a sub domain is considered a separate domain.
- **Auto add** Automatically prefix web address with http://. This
  feature will automatically detect and not prefix a URL with http:// or
  https:// already used in the URL.
- **Lazy Loading** ...
