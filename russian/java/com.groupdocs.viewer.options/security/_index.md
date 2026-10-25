---
title: "Security"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры безопасности PDF‑документа."
type: docs
weight: 29
url: /ru/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Предоставляет параметры безопасности PDF‑документа.


Класс Security инкапсулирует различные настройки и параметры, которые могут использоваться для применения мер безопасности
к PDF‑документу в компоненте GroupDocs.Viewer. Эти параметры включают защиту паролем,
разрешения и многое другое.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Пример использования:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

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
|  | [Security()](#Security--) | Инициализирует новый экземпляр |
Security
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Получает пароль, необходимый для открытия PDF‑документа. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Устанавливает пароль, необходимый для открытия PDF‑документа. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Получает пароль, необходимый для изменения настроек разрешений. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Устанавливает пароль, необходимый для изменения настроек разрешений. |
|
|  | [getPermissions()](#getPermissions--) | Получает разрешения PDF‑документа, такие как печать, изменение и извлечение данных. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Устанавливает разрешения PDF‑документа, такие как печать, изменение и извлечение данных. |
|
### Security() {#Security--}
```
public Security()
```


Инициализирует новый экземпляр
Security
класса.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Получает пароль, необходимый для открытия PDF‑документа.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - пароль для открытия документа.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Устанавливает пароль, необходимый для открытия PDF‑документа.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | java.lang.String | Пароль для открытия документа. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Получает пароль, необходимый для изменения настроек разрешений.


Используя пароль разрешений, вы можете ограничить печать, изменение и извлечение данных.
Используйте пароль разрешений, чтобы ограничить печать, изменение и извлечение данных. Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - пароль разрешений.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Устанавливает пароль, необходимый для изменения настроек разрешений.


Используя пароль разрешений, вы можете ограничить печать, изменение и извлечение данных.
Используйте пароль разрешений, чтобы ограничить печать, изменение и извлечение данных. Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | java.lang.String | Пароль разрешений. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Получает разрешения PDF‑документа, такие как печать, изменение и извлечение данных.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - разрешения PDF‑документа.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Устанавливает разрешения PDF‑документа, такие как печать, изменение и извлечение данных.


Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | int | Разрешения PDF‑документа. |
|

