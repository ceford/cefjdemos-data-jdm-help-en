<!-- Filename: Help4.x:Maintenance:_Global_Check-in / Display title: Global Check-in -->

## Description

A component record, an article for example, may be locked by a user who 
opened it for editing and never finished the editing session. In such cases, 
other users are not able to edit the record. Performing a Global Check-in 
releases all such records in selected extension tables.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to access

- Select **System → Maintenance Panel → Global Check-in** from
  the Administrator menu.

## Screenshot

![maintenance global check in](../../../en/images/maintenance/maintenance-global-check-in.png)

## Quick Tips

- Joomla articles are stored in the #__content table (#_ is a the table
  prefix placeholder).
- Make sure no one is busy editing any items before you perform a global
  check-in. When a Global Check-in is done, *all* items are checked in,
  including those currently being edited.
