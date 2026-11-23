---
title: "FolderFontSource"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса FolderFontSourcegroupdocs.viewer.fonts/folderfontsource."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

Инициализирует новый экземпляр класса [`FolderFontSource`](../../folderfontsource).

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| folderPath | String | Путь к папке, содержащей шрифты TrueType. |
| searchOption | SearchOption | Указывает, следует ли искать в текущей папке или в текущей папке и всех вложенных папках. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *folderPath* имеет значение null. |
| DirectoryNotFoundException | Выбрасывается, когда путь, указанный в *folderPath*, не может быть найден. |

### См. также

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
