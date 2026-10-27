---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет информацию о представлении документа MS Project."
type: docs
weight: 23
url: /ru/nodejs-java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

Представляет информацию о представлении документа MS Project.

Интерфейс ProjectManagementViewInfo определяет контракт для доступа и управления информацией представления документа MS Project в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации, такой как даты начала и окончания, а также другие свойства.

Пример использования:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*
## Методы

| Метод | Описание |
| --- | --- |
| [getStartDate()](#getStartDate--) | Получает дату и время начала проекта. |
| [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | Устанавливает дату и время начала проекта. |
| [getEndDate()](#getEndDate--) | Получает дату и время завершения проекта. |
| [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | Устанавливает дату и время окончания проекта. |
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


Получает дату и время начала проекта.

**Returns:**
java.util.Date — дата и время начала проекта.
### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


Устанавливает дату и время начала проекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startDate | java.util.Date | новая дата и время начала, которые необходимо установить. |

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


Получает дату и время завершения проекта.

**Returns:**
java.util.Date — дата и время окончания проекта.
### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


Устанавливает дату и время окончания проекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| endDate | java.util.Date | новая дата и время окончания, которые необходимо установить. |

