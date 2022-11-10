---
title: OutlookOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering Outlook data files.
type: docs
weight: 19
url: /java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Provides options for rendering Outlook data files.
## Constructors

| Constructor | Description |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFolder()](#getFolder--) | The name of the folder (e.g. |
| [setFolder(String value)](#setFolder-java.lang.String-) | The name of the folder (e.g. |
| [getTextFilter()](#getTextFilter--) | The keywords used to filter messages. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | The keywords used to filter messages. |
| [getAddressFilter()](#getAddressFilter--) | The email-address used to filter messages by sender or recipient. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | The email-address used to filter messages by sender or recipient. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | The maximum number of messages or items, that can be rendered from one folder. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | The maximum number of messages or items, that can be rendered from one folder. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


The name of the folder (e.g. Inbox, Sent Item or Deleted Items) to render.

**Returns:**
java.lang.String
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


The name of the folder (e.g. Inbox, Sent Item or Deleted Items) to render.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


The keywords used to filter messages.

**Returns:**
java.lang.String
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


The keywords used to filter messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


The email-address used to filter messages by sender or recipient.

**Returns:**
java.lang.String
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


The email-address used to filter messages by sender or recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


The maximum number of messages or items, that can be rendered from one folder.

--------------------

Outlook data files can be large and retrieving all messages can take significant time. This setting limits maximum number of messages or items (like contacts and tasks) that are rendered. Default value is 50. In order to render all messages, set the value to 0.

**Returns:**
int
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


The maximum number of messages or items, that can be rendered from one folder.

--------------------

Outlook data files can be large and retrieving all messages can take significant time. This setting limits maximum number of messages or items (like contacts and tasks) that are rendered. Default value is 50. In order to render all messages, set the value to 0.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

