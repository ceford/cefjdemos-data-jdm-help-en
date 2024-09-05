<!-- Filename: Help4.x:Maintenance:_Clear_Cache / Display title: Maintenance: Clear Cache -->

## Description

Cache files are temporary files that are created to improve site performance 
when enabled in the Site Global Configuration settings. Cache files can become
out of date and cause rendering problems which can be corrected by deletion of 
*all* Cache files. After deletion the website may be a little slower until the 
cache files are recreated with use.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to Access

- Select **System → Maintenance Panel → Clear Cache** from the Administrator menu.

## Screenshot

![Maintenance Clear Cache](../../../en/images/maintenance/maintenance-clear-cache.png)

## Column Headers

- **Cache Group** The type of item being cached in this file. This is
  also the name of the subdirectory where this type of cache file is
  stored. The cache files are stored in the directory
  `\<path-to-Joomla!\>/cache/\<Cache Group Name\>`.
- **Number of Files** The number of files currently in this cache group.
- **Size** The total size of the cache files in this group.

## Tips

- Normally you want to delete all cache files. To do this, click the
  check box in the column heading to select all files and then click the
  Delete icon in the toolbar.
