---
title: FolderFontSource
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Инициализирует новый экземплярFolderFontSourcegroupdocs.viewer.fonts/folderfontsource класс.
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---
## FolderFontSource constructor

Инициализирует новый экземпляр[`FolderFontSource`](../../folderfontsource) класс.

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderPath | String | Путь к папке, содержащей шрифты TrueType. |
| searchOption | SearchOption | Указывает, следует ли выполнять поиск в текущей папке или в текущей папке и во всех вложенных папках. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*folderPath* нулевой. |
| DirectoryNotFoundException | Брошен, когда путь указан в*folderPath* не может быть расположен. |

### Смотрите также

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* пространство имен [GroupDocs.Viewer.Fonts](../../folderfontsource)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
