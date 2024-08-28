<!-- Filename: Help4.x:Help_screens_styleguide / Display title: Help Screens Styleguide -->

<div class="alert alert-warning">
This style guide is for the Joomla MediaWiki installtion (docs.joomla.org).
</div>

This is a work in progress and should be used as a guideline for
creating Help screens for **Joomla 3.x**. The help screens which exist
on the Joomla! Docs Wiki are being accessed by every Joomla!
installation using the default help system. By following this
styleguide, the Joomla! Project can offer consistency throughout the
help screens to allow for easier navigation.

If you have a question, please post in on the associated talk page of
the help screen by clicking the ***Discussion*** tab at the top of the
help screen page.

## Help Screen Page Layout

### Description

Each and every help screen should have a "**Description**" section. This
goes into more detail about what the screen does and is used in help
screen tables throughout this wiki. <a
href="https://docs.joomla.org/Menu_Management#Menu_Management_Help_Screens"
class="mw-redirect" title="Menu Management">Here is an use example</a>.

There is no specific format to this section because the description
should be in direct correlation with the purpose and functionality of
the screen. There may be subsections to the description that describe
more specific details. Try to keep the description short and to the
point, if the description is long then consider using bullet points to
summarise it.

## How to Access

Each and every help screen should have a **How to Access** section
that gives the steps required to reach the screen that is being
described. This might be redundant because a user must be on the
administrator screen in order to have retrieved the help screen.
Remember, the help screens can be retrieved in a number of different
ways. For example, someone using a search engine to find out how to do
something might come across a help screen on the wiki without ever
having accessed the help system.

#### Notes:

- If the way to reach the screen is from another screen then the name of
  that screen should be a link to its help screen.
- You "click" on buttons, including toolbar buttons, but you "select"
  menu items. Consistent use of this terminology should help users.
- For ease of rendering the right arrow( → ), **This
  pointing → at that**.

### Screenshot

Screenshot showing the overall look of the screen.

#### Notes:

- Screenshot images can be any width, but larger images should have the
  \|800px added in the source.
- The filename should follow our
  <a href="https://docs.joomla.org/JDOC:Image_naming_convention"
  class="mw-redirect" title="JDOC:Image naming convention">standard naming
  conventions</a> for help screens.
  **Help-3x-***\<menu
  system-path-in-lowercase-separated-by-dashes\>***-screen-en.png**.
  For example, a screenshot of the Article Manager screen would be
  **\[\[File:Help-3x--content-article-manager-screen-en.png\]\]**.
- The filename should always include a language code at the end of the
  name, for English -en is added.
- You can use either .png or .jpg files.

## Form Fields (by Tab)

### Details Tab

This section should only be included on help screens that describe
screens which include a form. This includes all the add/edit screens,
but also includes screens like Site Global Configuration
and modal popups like <a
href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options"
title="Help4.x:Components Article Manager Options">Help4.x:Components
Article Manager Options</a>.

### Other Tab Types

If fields are grouped into fieldsets or tabs then group the fields under
sub-headings.

### Column Headers

This section should only be included on help screens that describe
back-end manager screens; that is, where you have a list of items being
shown. This section should describe each of the list columns.

### List Filters

This section should only be included on help screens that describe
back-end manager screens; that is, where you have a list of items being
shown. This section should describe how to use the list filters to
filter the contents of the screen. See
<a href="https://docs.joomla.org/Screen.content.15#List_Filters"
title="Screen.content.15">Screen.content.15#List_Filters</a> for example
from 1.5.

### Options

This section should only be included on help screens where the screen
has an Options toolbar button which opens a modal options sub-screen. If
there are many options and the help screen would become excessively long
if they were to be described here, then link to a separate help screen
with an "\_Options" suffix. For example, see <a
href="https://docs.joomla.org/Help4.x:Components_Article_Manager_Options"
title="Help4.x:Components Article Manager Options">Components Article
Manager Options</a>.

Since the Options modal screen is usually tabbed you should add a
sub-section under this section for each tab. For example, if there is a
tab labelled "Editing Layout" then you should add a third-level heading
of that name and within that sub-section you should describe each of the
available fields. You should start each sub-section with a screenshot of
the appropriate Options panel.

### Toolbar

Obviously, this section should only be included on help screens where a
toolbar is present.

Describes the available buttons and their associated functions. Use
**chunks** here because many will be the same for different screens.
Best to provide a picture of the toolbar.

The first word should always be a verb and, unless it is an irregular
verb, it should also end in the letter "s". This means you should
structure the description as if you are using the word "this" as the
subject, but leave the subject out of the sentence. This will make the
sentence actually a sentence fragment. For instance:

- Instead of "To find buried treasures, click this button."
  - Say, "Finds buried treasures."
- Instead of "You can click this button to insert a picture of John
  Stamos into the current document."
  - Say, "Inserts a picture of John Stamos."
- Instead of "Inform yourself that a picture of John Stamos is the same
  thing as a buried treasure."
  - Say, "Informs you that a picture of John Stamos is the same thing as
    buried treasure."

Since many toolbars are the same across multiple screens, the image
filenaming convention for toolbars is aimed at making it easy to re-use
toolbar images wherever possible. Toolbar images should follow this
naming convention: Help\<version\>-Toolbar-\<iconslist\>.png where
\<iconslist\> is a '-' separated list of the toolbar legends. Each word
should be capitalised, spaces and '&' removed. For example:
Help30-Toolbar-New-Edit-Delete-Options-Help.png

### Batch Process

This section should only be included on help screens where the screen
has a batch process feature. For example, see
<a href="https://docs.joomla.org/Help4.x:Components_Banners_Categories"
title="Help4.x:Components Banners Categories">Help4.x:Components Banners
Categories</a>.

### Tips

As the name suggests, this section should include tips, hints,
suggestions that can assist a user in performing tasks involving the
screen.
