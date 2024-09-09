<!-- Filename: Help6.x:Modules / Display title: Modules -->

## Description

Modules are lightweight and flexible extensions used to render snippets of information in boxes arranged around a component on a page. A well-known example is the *Login* module. Modules are assigned per menu item, so you can decide to show or hide a module depending on which page the user is currently viewing.

Some modules are linked to components. For example, the *Latest News* module links to the content component to display links to the newest articles. Modules do not need to be linked to components. They don't even need to be linked to anything and can be just static HTML or text.

There can be multiple instances of the same module. For example, you may use one instance of the *Random Image* module for some pages and another instance for other pages, each using a different image folder to select images from.

The *Modules (Site)* and *Modules (Administrator)* lists show the currently installed modules in each interface and provide access to add new modules or edit existing modules. 

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Item Ordering](jdocmanual?article=help/common-elements/list-ordering).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).
* [List Batch Process](jdocmanual?article=help/common-elements/list-batch-process).

To see lists of installed modules and available modules select one of the
following:

* [Site modules](jdocmanual?article=help/modules-site/site-modules-site)
* [Administrator modules](jdocmanual?article=help/modules-admin/admin-modules-administrator)

## How to access

- Select **Content → Site Modules** from the Administrator menu. Or...
- Select **Content → Administrator Modules** from the Administrator menu.

## List Filters

* **Site or Administrator** Selects either Site or Administrator modules.

## Column Headers

This is a short list of the headings unique to modules lists.

- **Position** The position on the page where this module is displayed.
- **Type** The system name of the Module.
- **Pages** The Menu Items where this Module will be displayed. This item is 
  not present in Administrator module lists.
  - *All* Displayed on all pages
  - *None* Displayed on no pages
  - *Selected* Displayed only on the pages selected
  - *All except selected* Displayed on all pages except those selected
- **Access** The viewing Access level  for this module.
- **Language** Modules language, default is *All*. This item is not present in
  Administrator module lists.

### Module Positions

To view module positions in a live site go to **System  → Templates** and select
the **Options** button in the Toolbar. Set *Preview Module Positions* to
enabled and *Save*. This setting is good for both site and administrator
templates. Then add `?tp=1` to the end of a url that does not already contain a
query string or `&tp=1` to the end of a url that does already contain a query
string. The page will show all available module positions, even those to which
no modules have been assigned. Positions are shown also in the Module edit form.

## Tips

- Joomla websites require at least one Menu module.
- Other Module Types (for example Banners) are optional.
- Some Modules are linked to components. For example, each Menu Module
  is related to one Menu.
- Other Modules (for example Breadcrumbs) do not depend on any other content.
- Multiple occurrences of a Module are allowed and common.
