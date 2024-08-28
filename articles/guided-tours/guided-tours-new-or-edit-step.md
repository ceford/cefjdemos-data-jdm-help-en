<!-- Filename: Help4.x:Guided_Tours:_New_or_Edit_Step / Display title: Guided Tours: New or Edit Step -->

## Description

This page is used to add a new or edit an existing Step of a tour.

### Common Elements

Some aspects of this page are covered in separate Help
articles:

* [Toolbars](jdocmanual?article=help/common-elements/toolbars).
* [The Publishing Tab](jdocmanual?article=help/common-elements/edit-publishing).

## How to Access

- Select **System -> Manage -> Guided Tours** from the Administrator menu.
- Select the numbered **Steps** button for a tour to open the tour steps page.
- Select the **New** toolbar button to add a step.
- Select a **Title** from the list to edit a step.

## Screenshot

![Guided tours edit step](../../../en/images/guided-tours/guided-tours-edit-step.png)

## Form Fields

- **Title**. The Title for this step. Usually it is a call to action, for
example 'Enter a title' if the step demands user interaction. If the title
is a language key, an aditional field is shown, representing the translation
of that key for the user's locale.

### Edit Step tab

#### Left Panel

- **Description**. This is where you enter the description of the step, usually
  a detailed explanation or help for the step.
  The step description can be a language key. When this is the case, a
  secondary field presents the translated description of that key for the
  user's locale.

#### Right Panel

- **Position**. The position of the step relative to the information it points to.
  - **Bottom**: Step shows below the target.
  - **Center**: Step shows at the center of the screen. When a target is missing, this is
     the default position.
  - **Left**: Step shows at the left of the target.
  - **Right**: Step shows at the right of the target.
  - **Top**: Step shows above the target.
- **Target**. The element of the screen the step points to. It uses CSS syntax.

  For example, *.button-new* will target the button of the page having class
  *button-new*.

  If the target is not unique, the first target found is used. When creating
  interactive steps, make sure the target is focusable for accessibility. You
  may use several selectors, comma separated. The first valid one will become
  the target (a selector is valid if: found on the page, not disabled, not
  read only and not hidden). If a target has been set but it is not found or
  it is invalid, the tour won't break but show the step at the center of the screen.
- **Type**. The type of step.
  - **Next**: The user running the tour will walk through the next step.
  - **Redirect**: The step will be redirected to another page.
  - **Interactive**: The step requires user interaction, like entering data.
- **URL**. The url to redirect to for a step of type 'Redirect'.
  For example, *administrator/index.php?option=com_users&view=user&layout=edit*
  will redirect the step to the user edit screen.
- **Interactive Type**. The type of interaction for an interactive step.
  - **Form Submit**: The target is a button that submits a form.
  - **Text Field**: The target is an input text field. If the field is required, the person running the tour won't be able to continue to the next step until data is entered.
  - **Button**: The target is a button on the screen.
  - **Other**: The target is any other form element.

### Options Tab

![Guided tours edit step options tab](../../../en/images/guided-tours/guided-tours-edit-step-options-tab.png)

## Tips

- Use **GUIDEDTOUR** in language keys as a convention wherever language
   keys are used (for title and description).
