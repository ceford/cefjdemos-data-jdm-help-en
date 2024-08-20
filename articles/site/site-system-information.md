<!-- Filename: Help4.x:Site_System_Information / Display title: System Information -->

## Description

This page provides information about your host server environment,
including operating system, database and PHP settings, and directory
information. There are five different tab panels: System Information,
PHP Settings, Configuration File, Folder Permissions, and PHP
Information. Each panel provides detailed information about that aspect
of your Joomla! website. This information is very helpful when you are
troubleshooting setup problems.

- Note that none of these settings can be changed from these panels.
  This must be done in different locations throughout your Joomla!
  installation, depending on the specific setting.
- Some settings can be changed from the Global Configuration page. Others 
  depend on your host server configuration and cannot be changed from inside 
  Joomla!.

### Common Elements

Some aspects of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to access

- Select **System → Information Panel → System Information**
  from the Administrator menu.

## Screenshot

![home dashboard](../../../en/images/site/system-information-tab.png)

## Form Tabs

### System Information Tab

- **PHP Built on** Provides details of the principle operating system
  which the webserver that Joomla is running on.
- **Database Type** Provides the type of the database being used by the
  installation of Joomla.
- **Database Version** Provides the current version of the MySQL
  database being used by the installation of Joomla.
- **Database Collation** How the MySQL database is structured for the
  information used by Joomla!.
- **Database Connection Collation** The character set and collation of
  the database.
- **PHP Version** Provides the current version of PHP server side
  script that is being used for this installation of Joomla.
- **Web Server** Provides the current type and version of webserver
  which the installation of Joomla! is running on.
- **Web Server to PHP Interface** The script that permits interaction
  between the web server (in most cases, Apache) and the PHP scripting
  language.
- **Joomla! Version** Provides the current version of Joomla!. It is
  recommended that it is always up-to-date and using the current stable
  release.
- **User Agent**The summary of the current user's local machine's
  operating system and browser information which is used to create an
  unique session ID for access and functionality within the Joomla!
  website.

### PHP Settings Tab

![home dashboard](../../../en/images/site/php-settings-tab.png)

This screen shows PHP Settings information. If any of these
is highlighted as incorrect they should be corrected.

- **Safe Mode** Recommended setting: OFF
- **Open basedir** Recommended setting: Site dependent
- **Display Errors** Recommended setting: OFF
- **Short Open Tags** Recommended setting: ON
- **File Uploads** Recommended setting: ON
- **Magic Quotes** Recommended setting: OFF
- **Register Globals** Recommended setting: OFF
- **Output Buffering** Recommended setting: OFF
- **Session Save Path** Recommended setting: Site dependent
- **Session Auto Start** Recommended setting: 0
- **XML Enabled** Recommended setting: YES
- **Zlib Enabled** Recommended setting: YES
- **Native ZIP Enabled** Recommended setting: YES
- **Disabled Functions** Recommended setting: Site dependent
- **Multibyte String (mbstring) Enabled** Recommended setting: YES
- **Iconv Available** Recommended setting: YES
- **Maximum Input Variables** Recommended setting: 2500

### Configuration File Tab

![home dashboard](../../../en/images/site/configuration-file-tab.png)

This tab shows the contents of the current Joomla!
*configuration.php* file which is stored under the main **\<path to
joomla\>/joomla_root/** directory. This file is created for you
automatically when you first install Joomla! and where most changes of
the Global Configuration section of Joomla! are recorded. Please note
that none of the settings can be changed from this page. Use Global
Configuration
to see more information about these settings and to make changes.

### Folder Permissions Tab

![home dashboard](../../../en/images/site/folder-permissions-tab.png)

This tab shows a list of the directories that the webserver should
have write access to. Please note that all directories listed on this
page should say **Writable**. If not, you may need to change the
permissions to be able to install and use Joomla! successfully.

### PHP Information Tab

![home dashboard](../../../en/images/site/php-information-tab.png)

This tab displays the full configuration of the PHP server side
scripting language that Joomla! runs on, together with all the
associated system information that goes towards the creation of the web
server. It is the output of an integrated php.info script built into
Joomla!.

PHP is installed, and runs on the server (hence the server side above),
and therefore all the settings are made on the server. The visitor to
the web site does not need to have anything special running on their
local machine in order to view or use any of the extra functionality
that PHP gives to the web site.

All the settings that are ever likely to be needed are displayed here.
Any changes that are required would be made within the *php.ini* and
other configuration files on the web server.

How much control a web site owner has over this information depends on
whether they own the server or if the server host is flexible in their
customer approach.

It is a good practice to know the limitations of a particular server
installation. This screens output is used to find detailed information
about how PHP is implemented on the server.

For full details on the information contained within the PHP Info tab
visit: [http://php.net/phpinfo](http://php.net/phpinfo).

## Quick Tips

- If you are having problems installing extensions, uploading files, or
  changing configuration options, check the Directory Permissions tab
  to make sure you have permission to write to files on your web server.
  The "Status" of the directories should be "Writable". If not, you may
  be unable to upload or edit files in these directories.
- When you are seeking help with setup problems, for example in a
  Joomla! web forum, it is very helpful to post specific information
  about your Joomla! installation. This page is an easy way to find
  all of this information in one place.
