<!-- Filename: Help4.x:Redirects:_Links / Display title: Redirects: Links -->

## Description

The *Redirects: Links* page shows a list of current web site redirects.

The redirect component is used to redirect URLs for web pages that no longer
exist on your website to web pages that are working. The URL you want to
redirect from must not be working and actually loading a web page. It can 
be the URL to a web page which you have disabled. 

The *Expired URL* you specify when you create the redirect
should be the full URL as you would type it in your web browser. The
component will only display the last portion of the source URL in the
redirect listing. 

The *New URL* you specify when you create a redirect
must be the full URL as well. You must have the *Use URL Rewriting*
option enabled in your Joomla! installation *Global Configuration*
options in order for the redirects you create to function.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [List Filters](jdocmanual?article=help/common-elements/list-filters).
* [List Column Headers](jdocmanual?article=help/common-elements/list-column-headers).
* [List Pagination](jdocmanual?article=help/common-elements/list-pagination).

## How to access

- Select **System → Manage panel → Redirects** from the Administrator menu.

## Screenshot

![Redirects links](../../../en/images/redirects/redirects-links.png)

## Column Headers

- **Expired URL** The URL which is being redirected on your website.
  Only the web page portion of the URL is displayed in this listing.
- **New URL** The destination URL for the redirect.
- **Referring Page** The referring web page for the redirect.
- **Created Date** Date the item (Article, Category, etcetera) was
  created.
- **404 Hits** Number of 404 Hits there have been on this URL.
- **Status Code** The Status Code of the page.

## Tips

- In order for your redirects to work, you must enable the option 
  **Use URL Rewriting** in the **Global Configuration** options of your
  Joomla! installation. Note also that just enabling the *Use URL
  Rewriting* option is not enough. You must take the additional step of
  renaming the `htaccess.txt` file in the web site directory where you
  installed Joomla! to `.htaccess` or to whatever file name your Apache
  web server requires for additional configuration directives. In the
  Apache configuration file this setting is named `AccessFileName` and
  by default this is set to `.htaccess`. 
