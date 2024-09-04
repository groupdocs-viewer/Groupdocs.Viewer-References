---
title: OutlookOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering Outlook data files.
type: docs
weight: 20
url: /nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Provides options for rendering Outlook data files.

The OutlookOptions class encapsulates various settings and parameters that can be used to control the rendering of Outlook data files (such as PST or OST files) in the GroupDocs.Viewer component.

For details, see the [documentation][].

Example usage:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Constructors

| Constructor | Description |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFolder()](#getFolder--) | Gets the name of the folder to render. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Sets the name of the folder to render. |
| [getTextFilter()](#getTextFilter--) | Gets the keywords used to filter messages. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Gets the keywords used to filter messages. |
| [getAddressFilter()](#getAddressFilter--) | Gets the email address used to filter messages by sender or recipient. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Sets the email address used to filter messages by sender or recipient. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Gets the maximum number of messages or items that can be rendered from one folder. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Sets the maximum number of messages or items that can be rendered from one folder. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Gets the name of the folder to render. The name of the folder (e.g., Inbox, Sent Item, or Deleted Items) to render.

When rendering an Outlook data file, GroupDocs.Viewer renders messages from all folders contained in the file (including nested folders). Use this property to render items from a specific folder. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - the name of the folder to render.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Sets the name of the folder to render. The name of the folder (e.g., Inbox, Sent Item, or Deleted Items) to render.

When rendering an Outlook data file, GroupDocs.Viewer renders messages from all folders contained in the file (including nested folders). Use this property to render items from a specific folder. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the folder to render. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Gets the keywords used to filter messages.

Use this property to render all messages that contain specific text in the subject or body. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - the keywords.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Gets the keywords used to filter messages.

Use this property to render all messages that contain specific text in the subject or body. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The keywords. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Gets the email address used to filter messages by sender or recipient.

Use this property to render all messages that contain specific text in the sender\\ufffds or recipient\\ufffds address. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - the email address used to filter messages.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Sets the email address used to filter messages by sender or recipient.

Use this property to render all messages that contain specific text in the sender\\ufffds or recipient\\ufffds address. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The email address used to filter messages. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Gets the maximum number of messages or items that can be rendered from one folder.

Outlook data files can be large and retrieving all messages can take significant time. This setting limits the maximum number of messages or items (such as contacts and tasks) that are rendered. The default value is 50. Set the value to 0 to render all messages. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - the maximum number of messages or items that can be rendered from one folder.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Sets the maximum number of messages or items that can be rendered from one folder.

Outlook data files can be large and retrieving all messages can take significant time. This setting limits the maximum number of messages or items (such as contacts and tasks) that are rendered. The default value is 50. Set the value to 0 to render all messages. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The maximum number of messages or items that can be rendered from one folder. |

