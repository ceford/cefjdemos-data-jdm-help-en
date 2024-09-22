<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Editor_Group / Display title: Editors Group -->

## Group Description

Editor plugins help users enter text with markup or layouts for special purposes, such as fragments of HTML or code. To use an Editor the software developer marks the data entry field as type `Editor`. If no editor plugins are enabled that is displayed as a simple textarea field. With one or more editor plugins enabled the site default plugin is used, set in the Global Configuration, unless overridden by the user preferred plugin, set in the User Profile. Joomla has the three core editor plugins listed below. Additional third party editor plugins may be available. Some editors have a very large selection of options.

### Editor - CodeMirror

The CodeMirror editor is a code editor which provides an editor more suited for source code. It has code syntax highlighting for many programming languages. It can show mismatched tags and also helps maintain consistent code indenting.

![Code mirror options form](../../../en/images/plugins/plugin-group-editor-codemirror.png)

- **List numbers** Display line numbers in the editor.
- **Code Folding** Allow blocks of code to be folded.
- **Gutters** Code Marker and Code Folding.
- **Highlight Active Line** Adds a highlight to the line the cursor is on.
- **Highlight Selection Matches** Highlight instances of the selected word throughout the document.
- **Match Tags** Highlight matching tags.
- **Match Brackets** Highlight matching brackets.
- **Tag Completion** Automatic tag completion.
- **Bracket Completion** Automatic bracket completion.
- **Key Map** Make CodeMirror work like other popular editors.
- **Toggle Fullscreen** Select the functon key to use to toggle fullscreen mode.
- **Use Modifiers** Select any modifier keys to use with the fullscreen toggle key.

![Code mirror advanced options form](../../../en/images/plugins/plugin-group-editor-codemirror-advanced.png)

- **Theme** Sets the colours for the editor.
- **Active Line Colour** The colour to use for highlighting the active line. Will be displayed at 50% opacity.
- **Matching Tag Colour** The background colour to use for highlighting matching tags. Will be displayed at 50% opacity.
- **Font** The font to use in the editor. If not installed, will be loaded from https://www.google.com/fonts/.
- **Font Size (px)** The size of the font in the editor.
- **Line Height (em)** The height of one line of text. This is in ems, meaning that 1.0 is equal to the font size and 2.0 is equal to 2x the font size.
- **Scrollbar Style** Select the scrollbar style you'd like CodeMirror to use.
- **Preview** An example of what your CodeMirror editor fields will look like with the current settings (save to update).

### Editor - None

This plugin loads a basic text editor. This option can be used when you are pasting HTML code from another source and you don't want the HTML to be altered by a WYSIWYG editor. This plugin has no options.

### Editor - TinyMCE

The TinyMCE editor is a WYSIWYG editor and is the default editor for entry of HTML in Joomla!.

![The TinyMCE plugin options form](../../../en/images/plugins/plugin-group-editor-tinymce.png)

- **Set selection tab** Select *Set 2*, *Set 1* or *Set 0* functionality. With *Set 2* selected, you see the editor for *Public* use. *Set 1* selected, is default for Managers and Registered, *Set 0* selected, is default for Administrators, Editors and Super Users.

Each Tab has a long list of options that are not illustrated here. The following list is a selection.

- **Site Skin** Choose the skin which will be applied to the TinyMCE editor when displayed in your website.
- **Administrator Skin** Choose the skin which will be applied to the TinyMCE editor when displayed in your Administrator Backend.
- **Toolbar Mode** Controls how to display the toolbar buttons that are not on the first row.
- **Images Drag and Drop** Enable drag and drop for uploading images.
- **Images Directory** The directory with the images files to be listed relative to the default images folder (set in Media > Options).
- **Entity Encoding** Controls how HTML entities are encoded. Recommended setting is `raw`. `named` = used named entity encoding (for example, `<`). `numeric` = use numeric HTML encoding (for example, `%03c`). raw = Do not encode HTML entities. Note that searching content may not work properly if setting is not `raw`.
- **Automatic Language Selection** If Yes, editor language will automatically match selected UI language. If the tiny language does not exist, the editor language will default to English.
- **Text Direction** Whether the language reads *Left to Right* or *Right to Left* (for example, like Arabic). Default is *Left to Right*.
- **Template CSS Classes** Whether or not to load the *editor.css* file. If no such file is found for the default template, the *editor.css* file from the system template is used. Default is *Yes*.
- **Custom CSS Classes** Optional full URL path to a custom CSS file. If entered, this overrides the Template CSS classes setting.
- **URLs** Whether to use Relative or Absolute URLs for links. The default is *Relative*.
- **New Lines** Whether to interpret new lines as *P Elements* or *BR Elements*. Default is *P Elements*.
- **Use Joomla Text Filter** If on, the text filter from the Joomla Global Configuration for every user group is applied. If off, the filters as defined here are used for all user groups.
- **Prohibited Elements** The elements that will be cleaned from the text. Default is *applet*, which will remove applet elements from the text.
- **Valid Elements** Defines which elements will stay in the edited text when the editor saves (the default rule set for this option is a mixture of the full HTML5 and HTML4 specification).
- **Extended Valid Elements** Optional list of valid HTML elements to add to the existing rule set.
- **Resizing** Enable/disable the resizing of the editor area (vertically and also horizontally if *Horizontal Resizing* is enabled).
- **Horizontal Resizing** Enable/disable the horizontal resizing.
- **Element Path** If set to ON, it displays the set classes for the marked text.
- **Word Count** Turn on/off word count.
- **Markdown** Allows the use of Markdown style syntax to create links, lists and other styles. This special syntax is converted and saved as regular html. For example the user can type # text to produce a header or **text** to make text bold.
- **Advanced Image** Turn on/off a more advanced image dialog box.
- **Advanced List** Turn on/off the ability to set number formats and bullet types in ordered and unordered lists.
- **Context Menu** Turn on/off the context menu.
- **Custom Plugin** Add custom TinyMCE plug-ins to the editor by specifying them here.
- **Custom Button** Add custom TinyMCE buttons to the editor by specifying them here.

#### TinyMCE Advanced tab

![TinyMCE Advanced Options form](../../../en/images/plugins/plugin-group-editor-tinymce-advanced.png)

- **Number of Sets** Number of sets that can be created. Minimum 3.
- **HTML Height** The height, in pixels, of the HTML mode pop-up window.
- **HTML Width** The width, in pixels, of the HTML mode pop-up window.
