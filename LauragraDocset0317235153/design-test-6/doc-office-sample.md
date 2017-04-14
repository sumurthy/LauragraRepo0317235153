# Buttons For Add-ins

## Overview

Buttons are best used to enable a user to commit a change or complete steps in a task. The text of a button should communicate the intent of the interaction. Therefore, as a guiding pattern for add-ins, buttons are placed at the bottom of the UI container of a task pane, dialogs, or content pane.

For example, use buttons at the end of a form to submit it; to close the end of a dialog, or move to the next settings screen to commit changes.
  
#### Task Pane Example

![Sample image displaying a primary and secondary button with the context of an Task Pane in an Office app.](../images/exampleButtonEdit@430.png)

## Best Practices

![Make sure the label conveys a clear purpose of the button to the user](../images/do1.png)
![Don’t place a button at the top of a table or inline.](../images/dont1.png)

![Use only a single line of text in the label of the button](../images/do2.png)
![Don’t place the default focus on a button that destroys data. Instead, place it on the button that performs the “safe act” and retains the content or cancels the action.](../images/dont2.png)

![Button label must descriptive of the intent action, concise, specific, self-explanatory, and usually a single word.](../images/do3.png)
![Don’t use a button to navigate to another place with exception of “Back” and “Next” buttons.](../images/dont3.png)

![Expose only one or two buttons to the user at a time. For example, “Accept” and “Cancel”.](../images/do4.png)
![Do not use buttons to toggle other UX in the same context.](../images/dont4.png)

![“Submit”, “OK”, and “Apply” buttons should always be styled as primary buttons. When “Reset” or “Cancel” buttons appear alongside one of the above, they should be styled as secondary buttons.](../images/do5.png)
![Don’t put too much text in a button – try keep text to a minimum.](../images/dont5.png)

![Default buttons should always perform safe operations in Add-in.](../images/do6.png)
![Don’t put anything other than text in a button](../images/dont6.png)

![Task buttons should be used to cause actions to complete a task or cause a transitional task.](../images/do7.png)

## Variants

#### Primary Button
![Primary Button Image.](../images/primary.png)
* Primary Button inherits theme color at rest state. Use this as the main call to action.

#### Default Button
![Default Button Image.](../images/default.png)
* Default Button should always perform safe operations and should never delete.

#### Compound Button
![Compound Button Image.](../images/compound.png)
* Compound Button is used to cause actions that complete a task or cause a transitional task.

## Additional Resources
* [Office UI Fabric Button](https://dev.office.com/fabric#/components/button)
* [UX Pattern Sample](https://office.visualstudio.com/DefaultCollection/OC/_git/GettingStarted-FabricReact)
* [GitHub Development Resources](https://github.com/OfficeDev/Office-Add-in-UX-Design-Patterns-Code)