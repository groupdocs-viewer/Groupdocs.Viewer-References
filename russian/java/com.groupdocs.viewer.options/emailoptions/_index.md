---
title: "EmailOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для рендеринга электронных сообщений."
type: docs
weight: 14
url: /ru/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Предоставляет параметры для рендеринга электронных сообщений.


Класс EmailOptions инкапсулирует различные настройки и параметры, которые могут быть использованы
для управления рендерингом электронных сообщений в компоненте GroupDocs.Viewer.


Для подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


Пример использования:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | Инициализирует новый экземпляр |
EmailOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | Получает формат времени для значений даты и времени. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Получает формат времени для значений даты и времени. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Получает смещение часового пояса для сообщения. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Получает смещение часового пояса в минутах для сообщения. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Получает смещение часового пояса для сообщения. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Получает смещение часового пояса в минутах для сообщения. |
|
|  | [getPageSize()](#getPageSize--) | Получает размер выходной страницы. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Получает размер выходной страницы. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Получает сопоставление между полями электронного сообщения и их текстовыми представлениями. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Устанавливает сопоставление между полями электронного сообщения и их текстовыми представлениями. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Переопределяет метод equals() класса Object. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Переопределяет метод toString() класса Object. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Инициализирует новый экземпляр
EmailOptions
класса.
Этот конструктор используется для создания нового экземпляра
EmailOptions
класса с настройками по умолчанию.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Получает формат времени для значений даты и времени.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Если формат времени не установлен, будет использован текущий системный формат.
Для подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - формат времени для значений даты и времени.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Получает формат времени для значений даты и времени.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Если формат времени не установлен, будет использован текущий системный формат.
Для подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | Формат времени для значений даты и времени. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Получает смещение часового пояса для сообщения.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
Для подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - смещение часового пояса.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Получает смещение часового пояса в минутах для сообщения.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
Для подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - смещение часового пояса.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Получает смещение часового пояса для сообщения.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | Смещение часового пояса. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Получает смещение часового пояса в минутах для сообщения.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | offsetMinutes | int | Смещение часового пояса. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Получает размер выходной страницы.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Получает размер выходной страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Размер страницы. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Получает сопоставление между полями электронного сообщения и их текстовыми представлениями.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - сопоставление между полями электронного сообщения и их текстовыми представлениями.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Устанавливает сопоставление между полями электронного сообщения и их текстовыми представлениями.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | Сопоставление между полями электронного сообщения и их текстовыми представлениями. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Переопределяет метод equals() класса Object.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | o | java.lang.Object | Объект для сравнения. |
|

**Returns:**
boolean - true, если объекты равны, false в противном случае.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Вычисляет значение хеш‑кода для этого объекта. Хеш‑код основан на
внутреннем состоянии объекта и используется в структурах данных, основанных на хешах
таких как хеш‑карты и хеш‑множества.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - значение хеш‑кода для этого объекта.

### toString() {#toString--}
```
public String toString()
```


Переопределяет метод toString() класса Object.


**Returns:**
java.lang.String - строковое представление объекта.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Возвращает строковое представление этого объекта.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | стиль | org.apache.commons.lang3.builder.ToStringStyle | ToStringStyle, используемый для генерации строкового представления. |
|

**Returns:**
java.lang.String - строковое представление этого объекта с использованием указанного ToStringStyle.

