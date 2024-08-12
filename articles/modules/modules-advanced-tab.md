<!-- Filename: Help6.x:Modules_Menu_Assignment_Tab / Display title: Modules: Advanced Tab -->

## Description

The Module: Advanced tab is used with minor variations in all module edit forms.

## Screenshot

![Modules advanced tab](../../../en/images/modules/modules-custom-advanced-tab.png)

## Form Fields

### Advanced Tab

- **Layout** If you have defined one or more alternative layouts for a
  module either in the template or Joomla! Core, you can select the
  layout to use for this module.
- **Module Class** A suffix applied to the CSS class of the Module.
  This allows you to create customized CSS styles that will apply just
  to this module. You would then modify the "user.css" file of your
  template to apply styling to this new class. Enter this parameter with
  a leading space to create a new CSS class for this module. Enter the
  parameter without a leading space to change the CSS class name for
  this module.
- **Automatic Title** Present in some modules to ...
- **Caching** Use Global/No Caching. Whether or not to cache the
  content of this Module. A setting of "Use Global" will use the Cache
  Settings from the Global Configuration screen.
- **Cache Time** The number of seconds for which to cache the item
  locally. It can safely be left at the default.
- **Module Style** You can use this option to override the templates
  style for its position.
- **Module Tag** The HTML tag for the module to be placed in. By
  default this is a div tag but other HTML5 elements can also be used.
- **Bootstrap Size** (Values 0 to 12) This allows you to choose the
  width of the module via the span element built into bootstrap.
- **Header Tag** The HTML tag to use for the modules header or title.
  This can be an h1, h2, h3, h4, h5, h6 or a p tag. Note that you must
  use a module style (chrome) of html5 or add your custom module styles
  in \<mytemplate\>/html/modules.php.
- **Header Class** Here you can add optional CSS classes to add to the
  modules header or title element.
