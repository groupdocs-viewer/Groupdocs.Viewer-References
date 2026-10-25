---
title: "Permissions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Определяет разрешения PDF‑документа."
type: docs
weight: 24
url: /ru/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Определяет разрешения PDF‑документа.


Класс Permissions предоставляет константы, представляющие различные разрешения
которые могут быть применены к PDF‑документу в компоненте GroupDocs.Viewer.
Эти разрешения контролируют действия, которые могут быть выполнены с PDF‑документом,
например, печать, копирование текста, изменение аннотаций и многое другое.


Пример использования:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Поля

| Поле | Описание |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Разрешить печать, изменение и извлечение данных. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Запретить печать. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Запретить изменение содержимого, заполнение форм, добавление или изменение аннотаций. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Запретить извлечение текста и графики. |
|
|  | [DENY_ALL](#DENY-ALL) | Запретить печать, изменение и извлечение данных. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Разрешить печать, изменение и извлечение данных.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Запретить печать.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Запретить изменение содержимого, заполнение форм, добавление или изменение аннотаций.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Запретить извлечение текста и графики.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Запретить печать, изменение и извлечение данных.


