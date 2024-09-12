<!-- Filename: Help4.x:Glossary / Display title: Glossary -->

The Joomla! Glossary is helpful for explaining common terms used in
Joomla! tutorials, help screens and advanced documentation.

## Access Control List

## Alias

## Anchor

An anchor is created using the `<a>` tag in HTML. An anchor allows you
to place a bookmark inside an HTML page. In Joomla!, you can place an
anchor inside an article (for example, using the TinyMCE editor). This lets 
you create a link that will go directly to that point in the article.

The HTML source code for an anchor looks like the following:

    <a name="my_anchor" title="My Anchor"></a>

You can link to an anchor from within the same page using the HTML code

    <a href="#my_anchor" ></a>

Clicking that link will take you directly to the location of the anchor tag.

You can link to an anchor in a different page by appending "#" plus the
anchor name to the end of the URL. In the example above, if the URL for
the article was `http://www.mysite.com/my_article.html`, then you could
link directly to the anchor in that page with the URL
`http://www.mysite.com/my_article.html#my_anchor`.

## Article

## Cascading Style Sheet (CSS)

A Cascading Style Sheet or CSS is used to control the presentation of an
XHTML page. For example, a CSS file will often control the font,
margins, color, background graphics, and other aspects of a web page's
appearance. CSS allows you to separate the content of an XHTML page from
it's appearance. In Joomla!, CSS files (for example, template.css) are
normally part of the template.

**See also:** Template, Page Class Suffix, Module Class Suffix

## Category

Every part of Joomla! powered web site or any CMS type of web site needs
a method to display and store its content logically. The usual method is
by categories and subcategories. Joomla! allows for multiple ways to
display and use content controlled by categorisation. Some of the
content types which have categorisation are Articles (the main content of
web pages), Banners and Contacts.

A category named *Uncategorised* is the default category assigned to most 
content types. The *Uncategorised* category is not descriptive and should be 
used on as needed basis for content types which do not fall under a specific 
category.

When creating and assigning categories, you should have a planned structure. 
As an example, this is one way to categorise several articles on birds: 

- Create two top level article categories named *Animals* and *Plants*.
- Under the *Animals* category, create sub categories named *Birds* and 
  *Mammals*. 
- Under the *Birds sub category, create categories entitled *Hawks*, *Parrots* 
  and *Sparrows. This is the resulting category structure

```
- Animals
  - Birds
    - Hawks
    - Parrots
    - Sparrows
  - Mammals
```

Now you can create multiple articles in the Hawk, Parrot and Sparrow sub
categories using the different genus or common names of the specific
types of these birds.

## Chrome

The visible graphical interface features of an application are sometimes
referred to as *chrome*.

## Component

## Core

The word *core* in Joomla! pertains to the distributed files which are
needed to create and administrate a Joomla CMS powered web site. The
Joomla core contains all of the necessary functionality to create and manage
a new web site quickly and easily. 

## Database Table Prefix

The database table prefix is a string (a few characters long) prepended
to the name of Joomla! tables. Using a prefix enables you to run multiple 
installations of Joomla! using a single database.

The database table prefix can be set during installation. Changing it
later is possible, but requires access to the database through a
non-Joomla medium or a Joomla Extension such as Akeeba Admin Tools and
will cause some downtime.

Extension developers need to use the string `#__` to represent the prefix.
This will be replaced by the real prefix at runtime.

## Extension

## LDAP

## Language

Languages are perhaps the most basic and critical extension type. Languages 
are packaged as either a core language pack or an extension language pack. 
These packages consist of INI files which contain key/value pairs to provide 
the translation of static text strings within Joomla! source code. This 
allows both the Joomla! core and third party components and modules to be 
internationalised. Core language packs also include an XML meta file 
describing the language and providing information about the fonts to use for 
PDF content generation.

## Menu

In Joomla!, a **Menu** is a modules containing a set of **menu items** used for 
navigation. Each menu item defines a URL to a page on the site. It holds 
settings that control the display of page content and style.

## Model-View-Controller

Joomla makes extensive use of the
<a href="http://en.wikipedia.org/wiki/Model-view-controller"
class="external text" target="_blank"
rel="nofollow noreferrer noopener">Model-View-Controller</a> design
pattern.

When Joomla is started to process a request from a user, such as a GET
for a particular page, or a POST containing form data, one of the first
things that Joomla does is to analyse the URL to determine which
component will be responsible for processing the request, and hand
control over to that component.

If the component has been designed according to the MVC pattern, it will
pass control to the controller. The controller is responsible for
analysing the request and determining which model(s) will be needed to
satisfy the request, and which view should be used to return the results
back to the user.

The model encapsulates the data used by the component. In most cases
this data will come from a database, either the Joomla database, or some
external database, but it is also possible for the model to obtain data
from other sources, such as via a web services API running on another
server. The model is also responsible for updating the database where
appropriate. The purpose of the model is to isolate the controller and
view from the details of how data is obtained or amended.

The view is responsible for generating the output that gets sent to the
browser by the component. It calls on the model for any information it
needs and formats it appropriately. For example, a list of data items
pulled from the model could be wrapped into an HTML table by the view.

Since Joomla is designed to be highly modular, the output from the
component is generally only part of the complete web page that the user
will ultimately see. Once the view has generated the output, the
component hands control back to the Joomla framework which then loads
and executes the template. The template combines the output from the
component, and any modules that are active on the current page, so that
it can be delivered to the browser as a single page.

To provide additional power and flexibility to web designers, who may
only be concerned with creating new designs rather than manipulating the
underlying code, Joomla splits the traditional view into a separate view
and layout. The view pulls data from the model, as in a traditional MVC
pattern, but then simply makes that data available to the layout, which
is responsible for formatting the data for presentation to the user. The
advantage of having this split is that the Joomla template system
provides a simple mechanism for layouts to be overridden in the
template. These layout overrides (often called "template overrides"
because they form part of the template, although actually it is the
layout that is being overridden) are bundled with the template and give
the template designer complete control over all the output from the
Joomla core and any installed third-party extensions that comply with
the MVC design pattern.

## Module

## Module Class Suffix

A Module Class Suffix is a parameter used in modules to add a new CSS 
class to a module. It is used in conjunction with styles defined in a user.css
file to change the standard appearance of a module.

The new class name may be used to add any desired styling to the module without 
needing to re-create all of the existing CSS code. Note that, if you create a 
new class name, make sure it has a unique name and doesn't conflict with any 
existing class names.

## Module Position

## Module chrome

## PHP

PHP is a computer scripting language designed for creating dynamic web
pages. PHP is widely-used for web development and can be embedded into
HTML. It generally runs on a web server, taking PHP code as its input and
creating web pages as output. Joomla! is primarily written using the PHP
language.

## Page Class Suffix

A Page Class Suffix is a parameter used in content menu items to add a new CSS 
class to the page layout. It is used in conjunction with styles defined in a 
user.css file to change the standard appearance of a module.

The new class name may be used to add any desired styling to the page without 
needing to re-create all of the existing CSS code. Note that, if you create a 
new class name, make sure it has a unique name and doesn't conflict with any 
existing class names.

## Patch

## Plugin

## Search Engine Friendly URLs

Search engine friendly URLs is a term commonly abbreviated as SEF URLs
or SEF for short. Normal Joomla! URLs look something like this:

    http://www.yoursite.org/index.php?option=com_content&view=section&id=3&Itemid=41

You can optionally have URLs display to look like static HTML pages like
this:

    http://www.yoursite.org/faq.html

There are built-in options for generating SEF URLs. These are enabled in the 
*SEO Settings* (Search Engine Optimisation) in the Site tab of the 
Global Configuration page. There are also third-party extensions that create 
SEF URLs for Joomla!.

## Split menus

A split menu is where different levels of a single menu are displayed in two 
or more locations on a single web page.

For example, a common requirement is for a menu of top-level items to
appear at the top of the page. When one of the items is clicked the user
is taken to a page where a secondary menu, say on the left of the page,
shows second-level items within the scope of the top-level item.

The menus appear in separate locations on the page, but are related
because one shows only top-level items while the other shows
second-level items. This idea can be extended to include menus for
third-level items and beyond.

This can be implemented in Joomla using a single multi-level menu then
creating more than one menu module each referring to a different level.

## Template

A template is a type of Joomla! extension that controls page appearance. 
- A Site template controls the public appearance of the site content. 
- An Administrator template controls the appearance of the site as for 
  administrative tasks such as: user, menu, article, category, module, 
  component, plugin and template management.

## Template style

## Upgrade Package

An Upgrade Package in Joomla! is a package of files that contain the
files that have changed between Joomla! versions. When this archive is
unpacked, it replaces the old version of the modified files with the new
version. For example, if fifty files were changed between version 5.1
and 5.2, the upgrade package would contain these fifty files and instructions
on how to execute the upgrade. Sometimes this includes database updates and
removal of files no longer used.
