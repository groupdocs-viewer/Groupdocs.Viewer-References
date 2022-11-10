---
title: ViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for generic document.
type: docs
weight: 25
url: /java/com.groupdocs.viewer.results/viewinfo/
---```
public interface ViewInfo
```

Represents view information for generic document. Default implementation is ViewInfoImpl
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | The type of the file. |
| [getPages()](#getPages--) | The list of pages to view. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


The type of the file.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### getPages() {#getPages--}
```
public abstract List<Page> getPages()
```


The list of pages to view.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Page>
