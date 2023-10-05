---
title: CacheableFactory
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.viewer/cacheablefactory/
---

## CacheableFactory class
This class helps customising  com.groupdocs.viewer.caching.Cache.
 You can implement your custom models for serialization and override methods in this class for return them instead of embedded ones.
 Just extend CacheableFactory and call:
  CacheableFactory.setInstance(new YourCustomCacheableFactory()) .
 More details in documentation
| [CacheableFactory](cacheablefactory)() |  |

## Functions

| Name | Description |
| --- | --- |
| [getInstance](getinstance)() | Gets instance of CacheableFactory |
| [newArchiveViewInfo](newarchiveviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results.Page>,  java.util.List<java.lang.String>) | Creates implementation of ArchiveViewInfo interface |
| [newAttachment](newattachment)(String, String) | Creates implementation of LotusNotesViewInfo interface |
| [newAttachment](newattachment)(String, String, String, long) | Creates implementation of LotusNotesViewInfo interface |
| [newAttachment](newattachment)(String, String, Path, long) | Creates implementation of LotusNotesViewInfo interface |
| [newAttachment](newattachment)(String, String, String, [FileType](../filetype), long) | Creates implementation of LotusNotesViewInfo interface |
| [newCadViewInfo](newcadviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results.Page>, java. util.List<com.groupdocs.viewer.results.Layer>, java.util.List<com.groupdocs. viewer.results.Layout>) | Creates implementation of LotusNotesViewInfo interface |
| [newCharacter](newcharacter)(char, double, double, double, double) | Creates implementation of LotusNotesViewInfo interface |
| [newFileInfo](newfileinfo)([FileType](../filetype)) | Creates implementation of LotusNotesViewInfo interface |
| [newLayer](newlayer)(String, boolean) | Creates implementation of LotusNotesViewInfo interface |
| [newLayer](newlayer)(String) | Creates implementation of LotusNotesViewInfo interface |
| [newLayout](newlayout)(String, double, double) | Creates implementation of LotusNotesViewInfo interface |
| [newLine](newline)(String, double, double, double, double, java.util.List<com.groupdocs. viewer.results.Word>) | Creates implementation of Line interface |
| [newLotusNotesViewInfo](newlotusnotesviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results. Page>, int) | Creates implementation of LotusNotesViewInfo interface |
| [newMboxViewInfo](newmboxviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results.Page>, int) | Creates implementation of TextElement interface |
| [newOutlookViewInfo](newoutlookviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results.Page>,  java.util.List<java.lang.String>) | Creates implementation of LotusNotesViewInfo interface |
| [newPage](newpage)(int, boolean) | Creates implementation of LotusNotesViewInfo interface |
| [newPage](newpage)(int, String, boolean) | Creates implementation of LotusNotesViewInfo interface |
| [newPage](newpage)(int, String, boolean, int, int) | Creates implementation of LotusNotesViewInfo interface |
| [newPage](newpage)(int, boolean, int, int) | Creates implementation of LotusNotesViewInfo interface |
| [newPage](newpage)(int, String, boolean, int, int, java.util.List<com.groupdocs.viewer. results.Line>) | Creates implementation of LotusNotesViewInfo interface |
| [newPage](newpage)(int, boolean, int, int, java.util.List<com.groupdocs.viewer.results.Line>) | Creates implementation of LotusNotesViewInfo interface |
| [newPdfViewInfo](newpdfviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results.Page>,  boolean) | Creates implementation of LotusNotesViewInfo interface |
| [newProjectManagementViewInfo](newprojectmanagementviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer. results.Page>, Date, Date) | Creates implementation of LotusNotesViewInfo interface |
| [newTextElement](newtextelement)(T, double, double, double, double) | Creates implementation of TextElement interface |
| [newViewInfo](newviewinfo)([FileType](../filetype), java.util.List<com.groupdocs.viewer.results.Page>) | Creates implementation of ViewInfo interface |
| [newWord](newword)(String, double, double, double, double, java.util.List<com.groupdocs. viewer.results.Character>) | Creates implementation of LotusNotesViewInfo interface |
| [setInstance](setinstance)([CacheableFactory](../cacheablefactory)) | Sets instance of CacheableFactory |
