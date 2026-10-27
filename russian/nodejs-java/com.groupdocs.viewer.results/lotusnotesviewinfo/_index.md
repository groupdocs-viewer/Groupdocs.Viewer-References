---
title: "LotusNotesViewInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет информацию о представлении хранилища базы данных Lotus Notes."
type: docs
weight: 19
url: /ru/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Представляет информацию о представлении хранилища базы данных Lotus Notes.

Интерфейс LotusNotesViewInfo определяет контракт для доступа и управления информацией о представлении хранилища базы данных Lotus Notes в компоненте GroupDocs.Viewer. Он предоставляет методы для получения такой информации, как количество заметок и другие свойства.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Методы

| Метод | Описание |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Получает количество заметок в хранилище. |
| [setNotesCount(int count)](#setNotesCount-int-) | Устанавливает количество заметок в хранилище. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Получает количество заметок в хранилище.

**Returns:**
int — количество заметок в хранилище.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Устанавливает количество заметок в хранилище.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | количество заметок в хранилище. |

