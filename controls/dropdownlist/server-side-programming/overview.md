---
title: Overview
page_title: Server-side Programming Overview | RadDropDownList for ASP.NET AJAX Documentation
description: Telerik's ASP.NET RadDropDownList Server-side Programming Overview
slug: dropdownlist/server-side-programming/overview
tags: overview
published: True
position: 0
---

# Server-side Programming Overview



## 
EVENTS

**RadDropDownList** supports a number of server-side events that let you respond to events with complex actions that can't be performed in client-side code.

* [SelectedIndexChanged]({%slug dropdownlist/server-side-programming/events/selectedindexchanged%}) occurs when the SelectedIndex has just changed.

* [ItemSelected]({%slug dropdownlist/server-side-programming/events/itemselected%}) occurs when an item from the dropdownlist is selected.

* [ItemDataBound]({%slug dropdownlist/server-side-programming/events/itemdatabound%}) occurs for each item when it is being bound to a data value.

>note The **SelectedIndexChanged** and **ItemSelected** events do not fire unless you set the **AutoPostBack** property to **True** .
>

Properties for RadComboBoxItem

Public Property Checked As Boolean
  Summary: Gets or sets the checked state of the combobox item.
  Remarks: Use the Checked property to determine whether the item is checked or not.
  
Public ReadOnly Property ComboBoxParent As Telerik.Web.UI.RadComboBox
  Summary: Gets the Telerik.Web.UI.RadComboBox instance which contains the current item.

Public Property DisabledImageUrl As String
  Summary: Gets or sets the path to an image to display for the item when it is disabled.
  Remarks: Use the DisabledImageUrl property to specify the image for the item when it is disabled. If the DisabledImageUrl property is set to empty string no image will be rendered. Use "~" (tilde) when referring to images within the current ASP.NET application.

Public Property ImageUrl As String
  Summary: Gets or sets the path to an image to display for the item.
  Remarks: Use the ImageUrl property to specify the image for the item. If the ImageUrl property is set to empty string no image will be rendered. Use "~" (tilde) when referring to images within the current ASP.NET application.
  
Public Property IsSeparator As Boolean
  Summary:Sets or gets whether the item is separator. It also represents a logical state of the item. Might be used in some applications for keyboard navigation to omit processing items that are marked as separators.

Public Property Owner As Telerik.Web.UI.RadComboBox
  Summary: Gets the Telerik.Web.UI.RadComboBox instance which contains the current item.

Public Property Selected As Boolean
  Summary: Gets or sets the selected state of the combobox item.
  Remarks: Use the Selected property to determine whether the item is selected or not.

Protected Overrides ReadOnly Property TagKey As System.Web.UI.HtmlTextWriterTag

Public Overrides Property Text As String
  Summary: Gets or sets the text caption for the combobox item.
  Remarks: Use the Text property to specify the text to display for the item.
  
Public Overrides Property ToolTip As String
Summary: Gets or sets the tooltip of the combobox item.

Public Overrides Property Value As String
  Summary: Gets or sets the value for the combobox item.
  Remarks: Use the Value property to specify the value
