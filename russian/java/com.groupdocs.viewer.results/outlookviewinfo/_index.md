---
title: "OutlookViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет информацию о представлении файла данных Outlook."
type: docs
weight: 22
url: /ru/java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Представляет информацию о представлении файла данных Outlook.


Интерфейс OutlookViewInfo определяет контракт для доступа и изменения информации представления
для файла данных Outlook в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации
например, список папок и другие свойства.


Пример использования:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is OutlookViewInfoImpl.*

## Методы

| Метод | Описание |
| --- | --- |
|  | [getFolders()](#getFolders--) | Получает список папок, содержащихся в файле данных Outlook. |
|
|  | [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Устанавливает список папок, содержащихся в файле данных Outlook. |
|
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Получает список папок, содержащихся в файле данных Outlook.


**Returns:**
java.util.List<java.lang.String> - список папок.

### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Устанавливает список папок, содержащихся в файле данных Outlook.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | list | java.util.List<java.lang.String> | список папок. |
|

