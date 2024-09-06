---
title: FileCache
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 20
url: /python-net/groupdocs.viewer.caching/filecache/
---

## FileCache class

Represents a local on-disk cache.

The FileCache type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FileCache(cache_path)|Initializes a new instance of the FileCache class|
|FileCache(cache_path, cache_sub_folder)|Initializes a new instance of the FileCache class|
## Properties
| Name | Description |
| :- | :- |
|cache_path|The Relative or absolute path to the cache folder.|
|cache_sub_folder|The sub-folder to append to the [cache_path](/python-net/groupdocs.viewer.caching/filecache/).|
## Methods
| Name | Description |
| :- | :- |
|set(key, value)|Serializes data to the local disk.|
|get_keys(filter)|Returns all file names that contains filter in filename.|

### See Also

* namespace [groupdocs.viewer.caching](/python-net/groupdocs.viewer.caching/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

