---
title: MailStorageOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering Mail storage Lotus Notes MBox data files.
type: docs
weight: 18
url: /java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Provides options for rendering Mail storage (Lotus Notes, MBox) data files.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | The keywords used to filter messages. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Sets the keywords used to filter messages. |
| [getAddressFilter()](#getAddressFilter--) | The email-address used to filter messages by sender or recipient. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Sets email-address used to filter messages by sender or recipient. |
| [getMaxItems()](#getMaxItems--) | The maximum number of messages or items for render. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Sets maximum number of messages or items for render. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


The keywords used to filter messages.

**Returns:**
java.lang.String
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Sets the keywords used to filter messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFilter | java.lang.String | the keywords used to filter messages. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


The email-address used to filter messages by sender or recipient.

**Returns:**
java.lang.String - The email-address
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Sets email-address used to filter messages by sender or recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addressFilter | java.lang.String | the email-address used to filter messages |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


The maximum number of messages or items for render.

Lotus notes data files can be large and retrieving all messages can take significant time. This setting limits maximum number of messages or items that are rendered. Default value is 0 - all messages will be rendered

**Returns:**
int
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Sets maximum number of messages or items for render.

Lotus notes data files can be large and retrieving all messages can take significant time. This setting limits maximum number of messages or items that are rendered. Default value is 0 - all messages will be rendered

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxItems | int | Maximum number of messages |

