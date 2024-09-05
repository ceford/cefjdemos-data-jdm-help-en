<!-- Filename: Help4.x:Information:_Database / Display title: Maintenance: Database -->

## Description

This page checks that the database table structure is up to date and tries to 
fix any problems that are found. In a normal Joomla version update, changes to 
the database table structure (also called a `schema`) are executed automatically
to keep the database version synchronized with the Joomla version. If an update 
is done manually, or if some part of an automatic update fails, the database 
schema might not be updated to match the version of the Joomla program files. 
In this case the page will list any database problems discovered. It is often
possible to fix any problems by selecting the *Update Structure* button.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to Access

- Select **System → Maintenance Panel → Database** from the Administrator menu.

## Screenshot

![Maintenance database](../../../en/images/maintenance/maintenance-database.png)

## Column Headers

- **Problems** Any problems will be mentioned here. A hover Tooltip
  provides more information.
- **Database Version** The version number of the Database.
- **Manifest Version** The version number of Joomla or Extension.
- **Folder** If the extension is a plug-in, the subdirectory of the
  Joomla! installation's plugins directory where the extension is located.

## Tips

- If problems occur during an update, use this Database check to see if the 
  database was updated correctly.
- It is strongly recommended that the Joomla Update component is used to for
  site update so that the database changes will be executed automatically.
