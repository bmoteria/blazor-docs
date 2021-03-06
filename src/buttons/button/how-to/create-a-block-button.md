---
title: "Create a Block Button"
component: "Button"
description: "Button how to section, block button, repeat button, tooltip for Button, customization of button appearance, input and anchor elements."
---

# Create a Block Button

You can customize a Button into a Block Button that will span the entire width of its parent element. To create a Block Button, set the [`CssClass`](https://help.syncfusion.com/cr/blazor/Syncfusion.Blazor~Syncfusion.Blazor.Buttons.SfButton~CssClass.html)
property to `e-block`.

```csharp
@using Syncfusion.Blazor.Buttons

<SfButton CssClass="e-block">BLOCKBUTTON</SfButton>
<SfButton CssClass="e-block" IsPrimary="true">BLOCKBUTTON</SfButton>
<SfButton CssClass="e-block e-success">BLOCKBUTTON</SfButton>

```

Output be like

![Button Sample](./../images/button-block.png)