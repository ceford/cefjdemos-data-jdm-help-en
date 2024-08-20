<!-- Filename: Help4.x:Templates:_Edit_Style / Display title: Templates: Edit Style -->

## Description

This page is used to edit template styles. When a template is first
installed, a default style is created for it. The default style for the
template will have the same name as the template with a *- Default*
suffix. To make a different variation of the default template style,
check the default style's checkbox and press the *Duplicate* icon in the
toolbar. Then edit the duplicate.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).

## How to Access

- Select **System → Templates Panel → Site Templates Styles**
  from the Administrator menu. Or...
- Select **System → Templates Panel → Administrator Templates
  Styles** from the Administrator menu. Then...
  - Select the name of the Template Style to edit in the Style column.

## Screenshot

![templates cassiopeia edit style editor tab](../../../en/images/templates/templates-site-edit-style-details-tab.png)

## Form Fields

- **Style Name** The name of the style. This is the name that will
  display in the Style column of the *Template: Styles* screen.

### Details Tab

- **Information** The name of the template, Site or Administrator
  indicator and a brief description.

### Advanced Tab

![templates cassiopeia edit style editor tab](../../../en/images/templates/templates-site-edit-style-advanced-tab.png)

This section may not be present for all styles. If a template from which
a style is derived from has configurable options they will be present
here. It is these additional configurable options which allow you to
have multiple different styles of templates with variations of these
options. The options available will vary based on what options the
template developer made available.

### Atum Colour Settings

The default Administrator template allows you to experiment with colour
variations. Save and see!

### Atum Image Settings

You may select an image to replace the **Login Logo** in the
Administrator login form, and the **Brand Logo** in the Administrator
Title bar in expanded mode and in compacted mode. The defaults are the
Joomla Brand logos. In the Title Bar, the word Joomla! is present in the
**Brand Large** version and omitted in the **Brand Small** version.
Select **Toggle Menu** to see the change.

If you provide your own Brand Small you also need to provide a width
style override. To do so, create a user.css file in the template root
and insert the following, but replace 3rem with a suitable width for
your image:

       .header .logo.small {
           width: 3rem;
       }

### Menu Assignment Tab

![templates cassiopeia edit style editor tab](../../../en/images/templates/templates-site-edit-style-menu-assignment-tab.png)

This section contains all the menu items configured in your Joomla!
website. To apply the current style to a menu item's corresponding web
page, check the box next to the menu item. You can press the *Toggle
Selection* button to invert the menu item selections.

**Note** If a checkbox is grayed out and cannot be checked then it
could be because the menu item is in use by another user. You can see if
this is the case by going to the menu manager screen for the menu
concerned. If there is a padlock symbol next to the menu item then it is
currently in use by another user.
