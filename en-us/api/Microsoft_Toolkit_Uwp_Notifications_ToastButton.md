---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Notifications_ToastButton.htm
title: Microsoft.Toolkit.Uwp.Notifications.ToastButton API 
description: API page for Microsoft.Toolkit.Uwp.Notifications.ToastButton
keywords: windows, app, toolkit, UWP, API
layout: default
search.product: eADQiWindows 10XVcnh
---


# ToastButton class

A button that the user can click on a Toast notification.

## Members

The **ToastButton** class has this types of members

* [constructors](#constructors)

* [properties](#properties)

### constructors

#### contructor

Initializes a Toast button with the required properties.

##### parameters



| name | description | type |
### properties

#### Content

Required. The text to display on the button.

#### Arguments

Required. App-defined string of arguments that the app can later retrieve once it is activated when the user clicks the button.

#### ActivationType

Controls what type of activation this button will use when clicked. Defaults to Foreground.

#### ImageUri

An optional image icon for the button to display (required for buttons adjacent to inputs like quick reply).

#### TextBoxId

Specify the ID of an existing [ToastTextBox](Microsoft_Toolkit_Uwp_Notifications_ToastTextBox.htm) in order to have this button display to the right of the input, achieving a quick reply scenario.