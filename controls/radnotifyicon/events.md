---
title: Events
page_title: Events
description: This article describes the RadNotifyIcon events.
slug: radnotifyicon-events
tags: events
position: 3
---

# Events

Here are the events exposed by the RadNotifyIcon control:

## Tooltip

* __PreviewTooltipOpened__: Occurs when a [styled tooltip]({%slug radnotifyicon-tooltip%}#tooltipcontent-and-tooltipcontenttemplate) is about to be opened. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.              

	* A __NotifyIconPopupOpeningEventArgs__ object. It exposes the following properties:

		* __Cancel__: Allows for preventing the opening of the tooltip.
		* __TaskbarEdge__: Gets the edge of the screen on which the taskbar is placed.
		* __NotifyIconBounds__: Gets the bounding rectangle of the icon in the notification area.
		* __Size__: Gets the size of the popup.
		* __Location__: Gets or sets the __absolute__ location where the popup will be opened. 
		* __PopupWindow__: Gets the window thат will be used to show the content of the popup.   
		* __AnchorPoint__: Gets the location of the mouse at the moment of interaction. If the mouse was not involved the value is null.

* __TooltipOpened__: Occurs when a [styled tooltip]({%slug radnotifyicon-tooltip%}#tooltipcontent-and-tooltipcontenttemplate) is opened. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type. 
	* An __EventArgs__ object.

## Popup

* __PopupOpening__: Occurs when a [popup]({%slug radnotifyicon-popup%}) is about to be opened. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __NotifyIconPopupOpeningEventArgs__ object. Its properties are listed in the __CustomTooltipOpening__ description.

* __PopupOpened__: Occurs when a [popup]({%slug radnotifyicon-popup%}) is opened. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type. 
	* An __EventArgs__ object.

## ContextMenu

* __TrayContextMenuOpening__: Occurs when a [context menu]({%slug radnotifyicon-contextmenu%}) is about to be opened. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __CancelEventArgs__ object. It allows for preventing the opening by setting the __Cancel__ property.

* __TrayContextMenuOpened__: Occurs when a [context menu]({%slug radnotifyicon-contextmenu%}) is opened. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* An __EventArgs__ object.

## Balloon 

* __BalloonTipShown__: Occurs when a [balloon notification]({%slug radnotifyicon-balloon-notifications%}) is shown. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* An __EventArgs__ object.

* __BalloonTipClicked__: Occurs when a [balloon notification]({%slug radnotifyicon-balloon-notifications%}) is clicked. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* An __EventArgs__ object.

* __BalloonTipClosed__: Occurs when a [balloon notification]({%slug radnotifyicon-balloon-notifications%}) is closed. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* An __EventArgs__ object.

## Tray Icon Events

* __TrayIconMouseClick__: Occurs when the user clicks on the notify icon. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __MouseButtonEventArgs__ object.

* __TrayIconMouseDoubleClick__: Occurs when the user double clicks on the notify icon. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __MouseButtonEventArgs__ object.

* __TrayIconMouseMove__: Occurs when the user moves the mouse over the notify icon. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __MouseButtonEventArgs__ object.

* __TrayIconMouseDown__: Occurs when the user presses a mouse button over the notify icon. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __MouseButtonEventArgs__ object.

* __TrayIconMouseUp__: Occurs when the user releases a mouse button over the notify icon. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __MouseButtonEventArgs__ object.

* __Selected__: Occurs when the user selects a RadNotifyIcon in the Windows notification area. The event handler receives two arguments:

	* The sender argument contains the __RadNotifyIcon__. This argument is of type object, but can be cast to the __RadNotifyIcon__ type.   
	* A __NotifyIconSelectedEventArgs__ object. It exposes the __IsKeyboardSelection__ property, which indicates whether the RadNotifyIcon was selected with the keyboard. If false, the selection was done with the mouse.

## See Also 

* [Getting Started]
