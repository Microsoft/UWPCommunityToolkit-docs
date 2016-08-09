---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_WeakEventListener`3.htm
title: Microsoft.Toolkit.Uwp.WeakEventListener`3 API 
description: API page for Microsoft.Toolkit.Uwp.WeakEventListener`3
keywords: windows, app, toolkit, UWP, API
layout: default
search.product: eADQiWindows 10XVcnh
---


# WeakEventListener<T1><T2><T3> class

Implements a weak event listener that allows the owner to be garbage collected if its only remaining link is an event handler.

## Members

The **WeakEventListener<T1><T2><T3>** class has this types of members

* [constructors](#constructors)

* [methods](#methods)

* [properties](#properties)

* [fields](#fields)

### constructors

#### contructor

Initializes a new instance of the [WeakEventListener<T1><T2><T3>](Microsoft_Toolkit_Uwp_WeakEventListener`3.htm) class.

##### parameters



| name | description | type |
### methods

#### OnEvent(T1 source,T2 eventArgs)

Handler for the subscribed event calls OnEventAction to handle it.

##### parameters



| name | description | type |
#### Detach()

Detaches from the subscribed event.

### properties

#### OnEventAction

Gets or sets the method to call when the event fires.

#### OnDetachAction

Gets or sets the method to call when detaching from the event.

### fields

#### weakInstance

WeakReference to the instance listening for the event.