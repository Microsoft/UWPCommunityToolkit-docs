---
permalink: /en-US/helpers/colors.htm
title: ColorsHelper utility from UWP Community Toolkit
description: Colors helper does commonly needed conversions of color formats
keywords: windows, app, toolkit, UWP, helpers, color, html color, hex color, hsv, hsl
layout: default
search.product: eADQiWindows 10XVcnh
---

# Colors Helper
The **Colors Helper** lets users convert colors from text names, html hex, hsv, or hsl to Windows UI Colors (and back again of course).

## Example

**NOTE:** There is no UI for this helper. It is a C# helper without a visual component.

```C#

	// Be sure to include the using at the top of the file:
	//using Microsoft.Toolkit.Uwp;

	// Given an HTML color, lets convert it to a Windows Color
	Windows.UI.Color color = ColorHelper.ToColor("#3a4ab0");

	// Also works with an Alpha code
    Windows.UI.Color myColor = ColorHelper.ToColor("#ff3a4ab0");

	// Given a color name, lets convert it to a Windows Color
	Windows.UI.Color redColor = "Red".ToColor();

```

## Platforms

Windows 10 SDK 10586 or higher

## API

[Color Helper Source](https://github.com/Microsoft/UWPCommunityToolkit/blob/master/Microsoft.Toolkit.Uwp/Helpers/ColorHelper.cs)
