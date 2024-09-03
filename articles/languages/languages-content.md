<!-- Filename: Help4.x:Languages:_Content / Display title: Languages: Content -->

## Description

The Languages: Content page displays information on installed languages.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to Access

- Select **System → Manage Panel → Content Languages** from the
  Administrator menu.

## Screenshot

![Languages Content list](../../../en/images/languages/languages-content.png)

## Column Headers

Selected information:

- **Title** The names of the installed Languages on this web site.
- **Native Title** Language title in the native language.
- **Language Tag** The language tag - example: en-GB for English (UK).
  This should be the exact prefix used for the language installed or to
  be installed.
- **URL Language Code** The language code used in multilingual site URLs.
- **Image** Name of the image file for this language when using the
  *Use Image Flags* Language Switcher basic option. Example: If *en* is
  chosen, then the image shall be *en.gif*. Images and CSS for this module
  are in media/mod_languages/
- **Home** Whether there is a default page set for this language or not.

## Tips

- Users can use any Language from the list of installed Languages,
  either by having it assigned in the Users list or
  by filling out a Menu Items - New/Edit - User Form Layout
  at the Front end. This will cause the Joomla! system prompts to be
  generated in this Language just for this User. For example, if a User
  chooses Spanish as their language, then the Search Module will show
  with prompts in Spanish.
- This User's choice is not affected by the Default Language set for the
  Front-end.
- Changing a User's Language or the Default Language does not affect the
  web site's Articles and other content.
- **Important**: Do not delete the default language files (for example,
  with FTP). This will create errors on both the Front-end and Back-end.
- Additional Languages can be added using the Install Languages page.
- If desired, you can show the Front-end site in one Language and show
  the Back-end administration pages in a different Language. Also,
  individual articles can be configured to use a different language in
  the Advanced Parameter pane when editing the Article.
