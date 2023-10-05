---
title: FileCache
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/filecache/
---

## FileCache class

 Represents a local on-disk cache.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| CACHE_PATH | cachePath |  |


## Functions

| Name | Description |
| --- | --- |
| [FileCache](filecache)(String) | Creates new instance of FileCache class. |
| [FileCache](filecache)(Path) | Creates new instance of FileCache class. |
| [FileCache](filecache)(String, String) | Creates new instance of FileCache class. |
| [FileCache](filecache)(Path, String) | Creates new instance of FileCache class. |

## Functions

| Name | Description |
| --- | --- |
| [get](get)(String, java.lang.Class<T>) | Deserializes data associated with this key if present. |
| [getCachePath](getcachepath)() | The Relative or absolute path to the cache folder. |
| [getCacheSubFolder](getcachesubfolder)() | The sub-folder to append to the #getCachePath(). |
| [getKeys](getkeys)(String) | Returns all file names that contains filter in filename. |
| [getWaitTimeout](getwaittimeout)() |  |
| [set](set)(String, Object) | Serializes data to the local disk. |
| [setWaitTimeout](setwaittimeout)(TimeSpan) |  |
