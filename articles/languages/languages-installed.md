<!-- Filename: Help4.x:Languages:_Installed / Display title: Languages: Installed -->

## Description

the *Languages: Installed* page is used to list installed languages and set
the default Languages independently for the Site and Administrator interfaces.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to Access

- Select **System → Manage Panel → Languages** from the Administrator menu.

## Screenshot

![Languages installed site list](../../../en/images/languages/languages-installed-site.png)

## List Filters

### Filter by Site or Administrator

- **Site** Shows the installed Languages for the site frontend. Select an
  item from the Default column to set it as the default frontend language.
- **Administrator** Shows the installed Languages for the administrator
  backend. Select an item from the Default column to set it as the default
  backend language.

## Tips

- Users can use any Language from the list of installed Languages,
  either by having Backend and Frontend languages assigned in the
  *Basic Settings* tab of the Administrator *Users: Edit* form or the Frontend
  *Edit Your Profile* form. This will cause the Joomla! system prompts to be
  generated in this Language just for this User. For example, if a User
  chooses Spanish as their language, then the Search Module will show
  with prompts in Spanish.
- Changing a User's Language or the Default Language does not affect the
  website's Articles and other content.
- **Important**: Do not delete the default language files (for example,
  with FTP). This will create errors on both the Frontend and Backend.
- Additional Languages can be added using the Install Languages Screen.
- If desired, you can show the Frontend site in one Language and show
  the Backend administration pages in a different Language. Also,
  individual articles can be configured to use a different language in
  the Advanced Parameter pane when editing the Article.
