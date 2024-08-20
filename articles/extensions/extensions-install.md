<!-- Filename: Help4.x:Extensions:_Install / Display title: Extensions: Install -->

## Description

Extensions are used to add capabilities to Joomla! that do not exist in
the standard installation. Hundreds of extensions are available for Joomla!,
with more being developed all of the time.

Extensions are categorised into five types, as follows:

- A *Component* is a mini-application that renders the main body of the
  page. Examples of Components are Contacts, the Front Page, and News
  Feeds.
- A *Module* is a smaller Extension typically used for rendering a small
  element that displays across multiple pages. Examples of Modules
  include Menus and Related Items.
- A *Plugin* is a section of code that runs when a pre-defined event
  happens within Joomla!. For example, editors are Plugins that run when
  an edit session is opened.
- The *Language* Extension allows for the Front-end and Back-end of
  Joomla! to be presented in any language for which a language Extension
  exists. This way, Joomla! can be released in a new language with no
  changes to the core program.
- A *Template* controls the way the content of a web site is displayed,
  including the location and layout of elements, colors, fonts, and so
  on. Templates allow the appearance of the web site to be separated
  from its content.

### Common Elements

Some elements of this page are covered in separate Help 
articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to Access

- Select **System → Install Panel → Extensions** from the
  Administrator menu.

There are four installation methods available. If **Install from Web** has
been made first in the list or was the last method selected there will be a 
brief delay as Joomla downloads an initial selection of Extension data from 
the Joomla Extensions Directory. 

The normal Tab order for the installation methods is as follows:

* Upload Package File
* Install from Folder
* Install from URL
* Install from Web

Only one method is needed to install a given Extension. The normal procedure 
for installing a Joomla! Extension is as follows:

1.  Download one or more archive files (normally ".zip" or "tar.gz"
    format) from the Extension provider's web site to a local directory
    on your computer. Note that some Extensions are installed as one
    file (for example, one Component or Module) while other Extensions
    might have two or more files (for example, a Component and a
    Module). If there are two or more parts, each one may have its own
    archive file. Or the parts may be combined in a package file.
2.  Choose one of the described methods to install the extension.
3.  When it is finished, the screen will display a **Success** or **Fail** 
    message.
4.  Depending on the Extension, it may be necessary to enable the
    Extension (for example, in the Modules or Plugins lists).

## Upload Package File Tab

![Extension install upload package file tab](../../../en/images/extensions/install-upload-package-file.png)

- Drag and drop or browse to the location where you downloaded the
  Extension's archive file.

The upload begins automatically. Note the **Maximum upload size: 32.00MB** 
defined for your installation. If you cannot increase this value you can use 
*Install from Folder*.

## Install from Folder Tab

![Extension install from folder tab](../../../en/images/extensions/install-from-folder.png)

1.  Create a temporary directory on your local hard drive and unpack the
    Extension's archive file in this temporary directory.
2.  Using FTP, upload the contents of this directory (including files
    and subdirectories) to a directory on your server.
3.  In the *Install Directory* field specify the server directory where
    you uploaded the files and subdirectories of the package.
4.  Click on the *Check and Install* button and Joomla! will install the
    contents of the given directory.

Note that it is common practice to put the folder containing your
unpacked extension in the tmp folder of your Joomla site.

## Install from URL Tab

![Extension install from url tab](../../../en/images/extensions/install-from-url.png)

Instead of downloading the archive file to your local computer, just
specify the URL of the target archive file. Then click the "Check and
Install" button and Joomla! automatically installs it directly from this
URL. *Note that, with this method, you will not have a copy of the
archive file on your local computer.*

## Install from Web Tab

To install an extension direct from the Joomla Extension
Directory (JED). You can select extensions to list by Category or you
can search by partial name.

![Extension install from web tab](../../../en/images/extensions/install-from-web.png)

## Quick Tips

- Four alternate installation methods are available, as indicated above.
  The most common one is the "Upload Package File" method.
- If you want to install a third-party Module or Plugin that belongs to
  a Component, you will generally need to install the Component as well
  as the Module or Plugin in order to use the Module or Plugin. This is
  normally documented in the Extension's installation instructions on
  the author's web site.
- Similarly, if you uninstall a third-party Component that also has its
  own Modules or Plugins, these Modules and Plugins can no longer be
  used. So it is normally recommended to uninstall these dependent
  Modules and Plugins as well.
- Some Components developed by third party developers may have their own
  Modules or Plugins included in the installer. In this case, make sure
  these Module or Plugin directories are writable. Otherwise the
  Extension will not work properly.
- **SECURITY WARNING:** It is recommended that you use only those
  third-party Extensions on your site that you really need. Do not use
  your live site for testing purposes because it may compromise your
  site and server. Test new extensions on a local test site before
  deploying them on your live site.
- Do not install Joomla! Extensions downloaded from 
  [Warez](https://en.wikipedia.org/wiki/Warez) sites because
  they may be infected by a virus or malware that cause damage on the
  server and can contaminate the computer of your visitors!
- Installing from remote URL can be dangerous. For this reason, it is
  generally recommended that you use the "Install from Web", "Upload
  Package File" or "Install from Folder" options when installing new
  Extensions.
