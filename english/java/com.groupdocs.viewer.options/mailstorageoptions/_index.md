---
title: MailStorageOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering Mail storage Lotus Notes MBox data files.
type: docs
weight: 19
url: /java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Provides options for rendering Mail storage (Lotus Notes, MBox) data files.

The MailStorageOptions class encapsulates various settings and parameters that can be used to control the rendering of Mail storage data files (such as Lotus Notes or MBox) in the GroupDocs.Viewer component.

Example usage:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Gets the keywords used to filter messages. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Sets the keywords used to filter messages. |
| [getAddressFilter()](#getAddressFilter--) | Gets the email address used to filter messages by sender or recipient. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Sets the email address used to filter messages by sender or recipient. |
| [getMaxItems()](#getMaxItems--) | Gets the maximum number of messages or items to render. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Sets the maximum number of messages or items to render. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Gets the keywords used to filter messages.

**Returns:**
java.lang.String - the keywords used for filtering messages.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Sets the keywords used to filter messages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| textFilter | java.lang.String | The keywords used for filtering messages. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Gets the email address used to filter messages by sender or recipient.

**Returns:**
java.lang.String - the email address used for filtering messages.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Sets the email address used to filter messages by sender or recipient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| addressFilter | java.lang.String | The email address used for filtering messages. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Gets the maximum number of messages or items to render.

Lotus Notes data files can be large, and retrieving all messages can take significant time. This setting limits the maximum number of messages or items that are rendered.

***Note:** The default value is 0, which means all messages will be rendered.*

**Returns:**
int - the maximum number of messages or items to render.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Sets the maximum number of messages or items to render.

Lotus Notes data files can be large, and retrieving all messages can take significant time. This setting limits the maximum number of messages or items that are rendered.

***Note:** The default value is 0, which means all messages will be rendered.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxItems | int | The maximum number of messages or items to render. |

