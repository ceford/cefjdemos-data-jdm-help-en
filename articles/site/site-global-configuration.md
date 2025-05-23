<!-- Filename: Help4.x:Site_Global_Configuration / Display title: Global Configuration -->

## Description

The Global Configuration screen allows you to configure the Joomla site
with your personal settings. Settings made in this screen apply to the
whole site.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to access

- Select **System Panel → Global Configuration** from the Home Dashboard. Or...
- Select **System → Setup Panel → Global Configuration** from the Administrator
menu.

## Screenshot

![global configuration site tab](../../../en/images/site/global-configuration-site-tab.png)

## Form Fields

### Site tab

#### Site panel

- **Site Name** Enter the name of the website. This will be used in
  various locations (for example the Backend browser title bar and Site
  Offline pages).
- **Site Offline** Select whether access to the Frontend is available.
- **Offline Message**
    - *Hide*
    - *Use Custom Message* The message uses the value defined in the
      *Custom Message* field.
    - *Use Site Language Default Message* The message uses the value
      defined in the site language ini file.
- **Offline Image** Select an image to be displayed on the offline
    page. Make sure the image is less than 400px wide.
- **Frontend Editing** Select editing for modules and menu items.
- **Default Editor** Select the default text editor. Registered Users
  will be able to change their preference in their personal details.
- **Default Captcha** Select the default captcha for your site. You may
  need to enter required information in the captcha plugin.
- **Default Access Level** Select the default access level for new
  items.
- **Default List Limit** Sets the default length of lists in the
  Backend for all users.
- **Default Feed Limit** Select the number of content items to show in
  the feeds.
- **Feed Email Address** The RSS and Atom newsfeeds include the
  author's email address.
  - *Author Email* Include the article author's email from the User Profile
    in the news feed.
  - *Site Email* Include the site *From Email* address for each article.

#### Metadata panel

- **Site Meta Description** Enter a description of the overall website
  that is to be used by search engines.
- **Robots** Robots instructions.
  - *index, follow* Index this page and follow the links on this page.
  - *noindex, follow* Do not index this page, but still follow the links
    on the page. For example, you might do this for a site map page
    where you want the links to be indexed but you don't want this page
    to show in search engines.
  - *index, nofollow* Index this page, but do not follow any links on the
    page. For example, you might want to do this for an events calendar,
    where you want the page to show in search engines but you do not
    want to index each event.
  - *noindex, nofollow* Do not index this page or follow any links on the
    page.
- **Content Rights** Describe what rights others have to use this
  content. This is conveyed to search engines using the `rights` meta
  tag in the HTML head.
- **Author Meta Tag** Show the author meta tag when viewing articles.
- **Joomla Version** Controls whether the `generator` meta tag in the
  HTML document's header in the Frontend and in Atom feeds includes the
  exact version of the Joomla site. It is recommended to hide it for
  security reasons.

#### SEO panel

- **Search Engine Friendly URLs** Select if the URLs are optimised for
  Search Engines.
- **Use URL Rewriting**
  - *Apache and Litespeed* Rename `htaccess.txt` to `.htaccess`.
  - *IIS* Rename `web.config.txt` to `web.config`.
  - *NginX* you must configure your server.
  - *Other* If unsure, please consult your hosting company
- **Add Suffix to URL** If yes, the system will add a suffix to the URL
  based on the document type.
- **Unicode Aliases** Choose between transliteration and unicode
  aliases. Transliteration is the default.
- **Site Name in Page Titles** Begin or end all Page Titles with the
  site name (for example, *My Site Name - My Article Name*).

#### Cookie panel

- **Cookie Domain** Domain to use when setting session cookies. Precede
  domain with '.' if cookie should be valid for all subdomains.
- **Cookie Path** Path the cookie should be valid for.

### System tab

![global configuration system tab](../../../en/images/site/global-configuration-system-tab.png)

#### Debug panel

- **Debug System** If enabled, diagnostic information, language
  translation, and SQL errors (if present) will be displayed. The
  information will be displayed at the foot of every page you view
  within the Joomla Backend and Frontend. It is not advisable to leave
  the debug mode activated when running a live website.
- **Debug Language** Enable to see the debugging indicators `**...**`
  or `??...??` in page output where Joomla Language files are used to translate
  string keys to their translated values. The first format indicates the string
  has been successfully translated. The second indicates the text has been
  entered in plain language and cannot be translated.
  - **Language Display** Select if you should display the language
  constant or the language value when debugging the language strings.

#### Cache panel

- **System Cache** Enable caching and set caching level.
  - *Conservative level* smaller system cache.
  - *Progressive level* faster, bigger system cache, includes module
    renderers cache. Not appropriate for extremely large sites.
  - **Cache Handler**
    - *File* Native caching mechanism is file-based. Please make sure the
      cache folders are writable.
  - **Platform Specific Caching** Enable when HTML output on mobile
    differs from other devices.
  - **Cache Time (minutes)** The maximum length of time in minutes for
    a cache file to be stored before it is refreshed.
  - **Path to Cache Folder** Specify a writable folder to store cache
    files if you do not wish to use the default folder.

#### Session panel

- **Session Handler** The mechanism by which Joomla identifies a User
  once they are connected to the website using non-persistent cookies.
  - *Database* The database session handler is the default handler
    because it is the only one that Joomla can fully configure and
    control on its own.
  - *Filesystem* The filesystem handler will be slightly more performant
    than the database handler, but it requires PHP to be configured
    properly otherwise it will crash and Joomla will be totally unusable.
    - *Session Save Path* Enter a full filesystem path. Ensure the
      path has appropriate permissions for PHP to read and write files,
      and if `session garbage collection` is enabled to delete files
      from it. If this path is not set, Joomla will rely on the PHP
      `session.save_path INI` configuration or fallback to the system
      temporary directory (as defined by the sys_get_temp_dir() PHP
      function). If neither of those paths are configured or the
      permissions are wrong then it's game over. To recover, edit the
      configuration.php file and set `$session_handler = 'database'`.
  - *Other handlers* APCu, Memcached, Redis, and WinCache all rely on
    optional PHP extensions and may be available if your system supports
    them. APCu or WinCache may be no better than the *plain* filesystem
    option. The Memcached and Redis handlers are overkill for Joomla in
    a typical shared hosting environment. Those types of handlers
    succeed if you are deploying Joomla in a load balanced environment
    where multiple servers are involved and you need the session data
    for the application to be available across all servers.
- **Session Lifetime (minutes)** Auto log out a User after they have
  been inactive for the entered number of minutes. Do not set too high.
- **Shared Sessions** When enabled, a user's session is shared between
  the Frontend and Backend sections of the site. Note that changing this
  value will invalidate all existing sessions on the site.This is not
  available when the *Force HTTPS* option is set to *Administrator Only*.
- **Track Session Metadata**
  - *Yes* Additional metadata about a user's session (including their
    username, user ID, and which application they are logged into) will
    be logged to the session database table.
  - *No* Features dependent on this data will be unavailable.

### Server tab

![global configuration server tab](../../../en/images/site/global-configuration-server-tab.png)

#### Server panel

- **Path to Temp Folder** Please specify a writable folder to store
  temporary files.
- **Gzip Page Compression**
  - *Yes* Automatically compress the generated HTML pages with Gzip,
    making them smaller and increasing your site's speed score.
  - *No* If your server is already doing that for you or if it conflicts
    with third party extensions.
- **Error Reporting** This parameter sets the level of error reporting
  to be used by PHP on the Joomla site.
  - *System Default* Leaves the level of error reporting to that set up
    in the server.
  - *None* Switches off error reporting.
  - *Simple* Override the server setting to give a basic level of reporting.
  - *Maximum* Override the server setting to allow reporting of all
    errors. Should your Joomla site fail to the extent that it is not
    possible to use the administrator page to activate error reporting,
    you can switch on full error reporting by editing the
    `configuration.php` file. Setting `$error_reporting = 'maximum'` is the 
    equivalent to setting *Error Reporting* to *Maximum*.
- **Force HTTPS** Force site access in the selected areas to occur only
  with HTTPS (encrypted HTTP connections with the https:// protocol
  prefix) and also force the use of secure cookies. Note, you must have
  HTTPS enabled on your server to utilise this option.

#### Location panel

- **Website Time Zone** Choose a city in the list to configure the date
  and time for display.

#### Web Services panel

- **Enable CORS** Cross-Origin Resource Sharing or
  [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) 
  enables scripts running in a browser to interact with resources from a 
  different origin.
  - **Access-Control-Allow-Origin** Specifies the origin allowed to
    access Web services on this site, sent back in response to a
    preflight request. Default: `*` (=all).
  - **Access-Control-Allow-Headers** Specifies the header(s) sent back
    in response to a preflight request. Default: `Content-Type,X-Joomla-Token`.
  - **Access-Control-Allow-Methods** Specifies the Web service
    method(s) allowed to access on this site, sent back in response to a
    preflight request. Default: all methods available for the requested route.

#### Proxy panel

- **Behind Load Balancer** If your site is behind a load balancer or
  reverse proxy, enable this setting so that IP addresses and other
  configurations within Joomla automatically take this into account.
- **Enable Outbound Proxy** Some hosts do not allow any network access
  from your site to the outside world by default and require you to
  manually configure an outbound proxy.
  - **Outbound Proxy Host** Host (domain) name or IP address.
  - **Outbound Proxy Port**
  - **Outbound Proxy Username** Leave blank if your outbound proxy does
    not require authentication.
  - **Outbound Proxy Password**

#### Database panel

- **Database Type** The type of database in use, selected during the
  installation process. Do not edit this field unless absolutely
  necessary (for example the transfer of the database to a new hosting
  provider).
- **Host** The hostname for your database entered during the
  installation process. Do not edit this field unless absolutely
  necessary (for example the transfer of the database to a new hosting
  provider).
- **Database Username** The username for access to your database
  entered during the installation process. Do not edit this field unless
  absolutely necessary (for example the transfer of the database to a
  new hosting provider).
- **Database Password** The password to be used to access the
  database. Do not edit this field unless absolutely necessary (for
  example the transfer of the database to a new hosting provider).
- **Database Name** The name for your database entered during the
  installation process. Do not edit this field unless absolutely
  necessary (for example the transfer of the database to a new hosting
  provider).
- **Database Tables Prefix** The prefix used for your database tables,
  created during the installation process. Do not edit this field unless
  absolutely necessary (for example the transfer of the database to a
  new hosting provider).
- **Connection Encryption**
  - Default (server controlled)
  - One-way authentication
    - **Verify Server Certificate**
      - **Path to CA File** File system path.
  - Two-way authentication
    - **Path to Private Key File** File system location.
    - **Path to Certificate File** File system location.
    - **Verify Server Certificate**
      - **Path to CA File** File system path.
    - **Supported Cipher Suite (optional)** No entry required (only
      recommended for experienced users). For more details, see the
      documentation of your database.

#### Mail panel

- **Send Mail**
  - *Yes* Turn on mail sending.
  - *No* Turn off mail sending. It is recommended to put the site offline
    when disabling the mail function.
- **Disable Mass Mail**
  - *Yes* Disable the Mass Mail Users function.
  - *No* Make the Mass Mail Users function active.
- **From Email** The email address that will be used to send site
  email.
- **From Name** Text displayed in the header *From:* field when sending
  a site email. Usually the site name.
- **Reply To Email** The email address that will be used to receive end
  user(s) reply.
- **Reply To Name** Text displayed in the header *To:* field when end
  user(s) reply to received email.
- **Mailer** Select which mailer for the delivery of site email.

### Logging tab

![global configuration logging tab](../../../en/images/site/global-configuration-logging-tab.png)

#### Logging panel

- **Path to Log Folder** Joomla can optionally keep a log file of its
  own and third party extension operations. Provide the absolute path
  to a folder that is writeable by PHP; if it's missing or is not
  writeable Joomla will not load at all. For security reasons you must
  not use a folder with system-wide access such as `/tmp`.
- **Log Almost Everything** Logs everything, except deprecated APIs.
- **Log Deprecated API** Logs deprecated APIs.

#### Custom logging panel

- **Log Priorities** Can be used to manage custom logging. Select the
  events you want to see in the log file. Default is *All*. The item(s)
  can be selected or deselected by clicking the dropdown list.
- **Log Categories** A comma separated list of log categories to
  include or exclude. Common log categories include but are not limited
  to: `database`, `databasequery`, `database-error`, `deprecated` and
  `jerror`. If empty, custom logging is disabled.
- **Log Category Mode** Sets the mode for the list of log categories above.

### Text Filters tab

![global configuration text filters tab](../../../en/images/site/global-configuration-text-filters-tab.png)

These text filter settings will be applied to all text editor fields
submitted by users in the selected groups.

These filtering options give more control over the HTML your content
providers submit. You can be as strict or as liberal as you require to
suit your site's needs. The filtering is opt-in and the default settings
provide good protection against markup commonly associated with website
attacks.

## Tips

- Most of these settings can be set once and then left alone.
- If major modifications need to be made, then consider taking the site
  offline to test it and to make sure everything is in working order.
- The settings are saved in the `configuration.php` file in the site root.
  This file's permissions are set to read-only (444) after making changes via
  the Global Configuration page and must be given owner write permission (644)
  before editing with a  text editor.
