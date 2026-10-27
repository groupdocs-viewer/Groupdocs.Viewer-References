---
title: "ArchiveViewInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет информацию о представлении архивного файла."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.results/archiveviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ArchiveViewInfo extends ViewInfo
```

Представляет информацию о представлении архивного файла.

Интерфейс ArchiveViewInfo определяет контракт для получения информации о представлении, специфичной для архивного файла, в компоненте GroupDocs.Viewer. Он предоставляет методы доступа к деталям, таким как количество страниц, размеры и параметры рендеринга, специфичные для архивных файлов.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.zip")) {
     ArchiveViewInfo viewInfo = (ArchiveViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ArchiveViewInfoImpl.*
## Методы

| Метод | Описание |
| --- | --- |
| [getFolders()](#getFolders--) | Получает список папок, содержащихся в архивном файле. |
| [setFolders(List<String> folders)](#setFolders-java.util.List-java.lang.String--) | Устанавливает список папок, содержащихся в архивном файле. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Получает список папок, содержащихся в архивном файле.

**Returns:**
java.util.List<java.lang.String> - список папок.
### setFolders(List<String> folders) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> folders)
```


Устанавливает список папок, содержащихся в архивном файле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| папки | java.util.List<java.lang.String> | список папок. |

