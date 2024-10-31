---
title: OutlookViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for an Outlook Data file.
type: docs
weight: 20
url: /java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Represents view information for an Outlook Data file.

The OutlookViewInfo interface defines the contract for accessing and manipulating view information for an Outlook Data file in the GroupDocs.Viewer component. It provides methods to retrieve information such as a list of folders, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getFolders()](#getFolders--) | Retrieves the list of folders contained in the Outlook Data file. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Sets the list of folders contained in the Outlook Data file. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Retrieves the list of folders contained in the Outlook Data file.

**Returns:**
java.util.List<java.lang.String> - the list of folders.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Sets the list of folders contained in the Outlook Data file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| list | java.util.List<java.lang.String> | the list of folders. |

