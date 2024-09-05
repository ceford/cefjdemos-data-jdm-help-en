<!-- Filename: Help4.x:Menus / Display title: Menus -->

## Description

Menus allow a user to navigate through the site. A menu is an object
which contains one or more menu items. Each menu item points to a
logical page on the site. A menu module is required to place the menu on
the page. One menu can have more than one module. For example, one
module might show only the first level menu items and a second module
might show the level 2 menu items.

The Menus list provides an overview of the menus available on a Joomla
site. This includes the details of each individual menu's number of
items published, unpublished and trashed, and the names of linked
modules.

The process for adding a menu to the site is normally as follows:

1.  Create a new menu (using this page).
2.  Create one or more new menu items for the menu. Each menu item will
    have a specific menu item type.
3.  Create one or more menu modules to display the menu on the site.
    - Select the menu items (pages) that will display the module.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Item Ordering](jdocmanual?article=help/common-elements/list-ordering).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to Access

- Select **Menus → Manage** from the Administrator menu.

## Screenshot

![menus list](../../../en/images/menus/menus-list.png)

## Column Headers

- **Title** The name of the menu.
- **Menu Items** A link to the menu items for the menu.
- **\# Published** Number of published menu items in this menu.
- **\# Unpublished** Number of unpublished menu items in this menu.
- **\# Trashed** Number of trashed menu items in this menu.
- **Linked Modules** A dropdown list shows the name, access level and template
  position of any menu modules associated with the menu.

## Tips
- The numbered buttons lead to a filtered list of the menu items for that menu.
- A menu should have a short descriptive title suitable for use in lists and
  dropdown lists. 
- The *Description* is a useful reminder of the purpose for which the menu
  was created.
- If a menu has no associated modules the *Linked Modules* column button is 
  a link to an *Add a module for this menu* modal dialogue.
- If you delete an existing menu, do not forget that all the menu items
  of the respective menu will be also deleted. There is a warning message:

  **Are you sure you want to delete these menus? Confirming will delete the 
  selected menu types, all their menu items and the associated menu modules.**
- The Main Menu has the site default menu item. It **should not be
  deleted**! The default menu item defines the page that is displayed on
  a visit to the site domain URL, such as `www.example.com`. The site will not 
  function if it is deleted. It is usually the *Home* menu item but it can be 
  set to any menu item including a menu item in a hidden menu. If the default 
  menu item is changed, make sure that that menu item is not deleted either! 
