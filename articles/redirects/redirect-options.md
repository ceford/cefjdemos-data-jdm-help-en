<!-- Filename: Help4.x:Redirect:_Options / Display title: Redirect: Options -->

## Description

Redirect Options configuration allows setting of parameters used
globally for Redirects.

### Common Elements

Some elements of this page are covered in separate Help articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Permissions Tab](jdocmanual?article=help/common-elements/edit-permissions).

## How to Access

- Select **System → Redirects in the Manage Panel** from the
  Administrator menu. Then...
  - Select the **Options** button in the Toolbar.

If you see this error message:

<div class="alert alert-danger">
The Redirect System Plugin is disabled. It needs to be enabled for this component to work.
</div>

Select the  **Rediret System Plugin** link and enable the plugin in the popup
dialog box.

## Screenshot

![Redirect options advanced tab](../../../en/images/redirects/redirect-options-advanced-tab.png)

## Form Fields

### Advanced Tab

- **Activate Advanced Mode** Enable more advanced functionality for the 
  component. When enabled the Redirects Edit form has a required 
  **Redirect Status Code** field that allows you to change the default value 
  from 301 to 302 or 303. Only enable Advanced Mode if you know how to use 
  Redirect Status codes.
- **Bulk Import Separator** The separator used for bulk import, by
  default it is a vertical bar symbol (|) but it can be comma (,) for a 
  copy/paste from a CSV file for instance.
- **Import State** When batch importing redirects, enable or disable by default.
