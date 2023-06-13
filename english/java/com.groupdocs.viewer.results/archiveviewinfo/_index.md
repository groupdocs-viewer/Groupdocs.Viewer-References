---
title: ArchiveViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for an archive file.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Represents view information for an archive file.

The ArchiveViewInfo interface defines the contract for retrieving view information specific to an archive file in the GroupDocs.Viewer component. It provides methods to access details such as page count, dimensions, and rendering options specific to archive files.

Example usage:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

Note: The default implementation of this interface is ArchiveViewInfoImpl.
## Methods

| Method | Description |
| --- | --- |
| [getFolders()](#getFolders--) | Retrieves the list of folders contained within the archive file. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Retrieves the list of folders contained within the archive file.

**Returns:**
java.util.List<java.lang.String> - the list of folders.
