<!-- Filename: Chunk4x:Extensions_Plugin_Manager_Edit_Content_Group / Display title: Content Group -->

## Group Description

### Content - Confirm Consent

![Content confirm consent plugin](../../../en/images/plugins/plugin-group-content-confirm-consent.png)

- **Short Privacy Policy** Brief notice of the text which will be displayed above the Privacy Consent Checkbox.
- **Privacy Article** If needed, select/create your Privacy Article to link to your form.

For more information, see Privacy Consent - Plugin Configuration

### Content - Contact

![Content contact plugin](../../../en/images/plugins/plugin-group-content-contact.png)

- **Redirection** You can link the author name to:
  - Associated contact page.
  - Webpage specified in the associated contact profile.
  - Email specified in the associated contact profile.
- **Apply link also to alias name** Link to the real user data even if an author alias is set in article options.

### Content - Email Cloaking

This plugin cloaks all e-mails in content using JavaScript to foil spambots. This helps prevent e-mails contained in articles from being added to spam e-mail lists. You can disable Email Cloaking inside an article by inserting {emailcloak=off} anywhere in the text of the article. In this case, no e-mail addresses in the article will be cloaked by this plugin.

![Content email cloaking plugin](../../../en/images/plugins/plugin-group-content-email-cloaking.png)

- **Mode** How the e-mails will be displayed. Options are *As linkable mailto address* or as *Non-linkable text*.

### Content - Fields

This plugin allows you to display a custom field which has been inserted with the *Button - Fields* plugin or using Syntax: `{field #}` directly into the editor area. Syntax:

- **`{field 1}`** will display the field with the ID 1.
- **`{field 1,foo}`** will display the selected field using the alternative layout `foo`.
- **`{fieldgroup 2}`** will display all fields within the fieldgroup with the ID 2.

### Content - Joomla

![Content Joomla plugin](../../../en/images/plugins/plugin-group-content-joomla.png)

- **Check Category Deletion** Check that categories are fully empty before they are deleted.
- **Email on New Site Article** Email users if *Send email* is *On* when there is a new article submitted via the Frontend.

### Content - Load Modules

This plugin allows you to place a Module inside an Article with the syntax: `{loadposition xx}`, where `xx` is a user-defined position code. For example, if you create a Module with the Position value of `myposition1`, then typing the text `{loadposition myposition1}` inside an Article will cause that Module to show at that point in the Article.

![Content load modules plugin](../../../en/images/plugins/plugin-group-content-load-modules.png)

- **Style** The Style for the loaded Module.

### Content - Page Break

This plugin adds table of contents functionality to a paginated Article. This is done automatically through the use of the Pagebreak button added to the lower part of the text panel in an Article. The HTML code is included here as a reference of what is available. The Pagebreak will itself display in the text window as a simple horizontal line.

![Content page break plugin](../../../en/images/plugins/plugin-group-content-page-break.png)

- **Show Site Title** Whether or not the title and heading attributes from the plug-in will be added to the Site Title tag.
- **Article Index Heading** Show or hide Article Index Heading. The Headig displays on top of the Table of Content.
- **Custom Article Index Heading** Enter a custom text for the Article Index Heading. If empty, standard will be used.
- **Table of Contents** Whether to Hide or Show a table of contents for multi-page Articles.
- **Show all** Whether or not to give Users the option to show all pages of an Article.
- **Presentation Style** Display the article with separate pages, tabs or sliders.

![Content page break description](../../../en/images/plugins/plugin-group-content-page-break-description.png)

### Content - Page Navigation

This plugin allows you to add Next & Previous navigation links to Articles, for example when using a blog or list layout. This feature can be controlled with the following Joomla! parameters:

- **Show Navigation** in the Article - Global Configuration screen
- **Show Navigation** in the Parameters - Component section of the Menu Item - New/Edit - Parameters - Component for Articles screen for Article layouts.

Note that, if the Page Navigation plug-in is disabled in this screen, no Page Navigation will show and the parameter settings above will have no effect.

![Content page break plugin](../../../en/images/plugins/plugin-group-content-page-navigation.png)

- **Position** Position of the navigation link. Options are *Above* the Article or *Below* the Article.
- **Relative To** Assigns the relative location for the Position parameters. Text will place it directly above or below the article content. Full Article will place it above or below the full display including title and readmore.
- **Link Text** Choose what to display as the link text.

### Content - Smart Search

Changes to content will not update the Smart Search index if you do not enable this plugin.

### Content - Vote

![Content vote plugin](../../../en/images/plugins/plugin-group-content-vote.png)

- **Position** Position of the voting.
