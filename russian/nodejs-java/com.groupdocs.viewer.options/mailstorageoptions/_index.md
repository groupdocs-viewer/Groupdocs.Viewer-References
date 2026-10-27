---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для визуализации файлов данных хранилища почты Lotus Notes MBox."
type: docs
weight: 19
url: /ru/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Предоставляет параметры для рендеринга файлов данных хранилища почты (Lotus Notes, MBox).

Класс MailStorageOptions инкапсулирует различные настройки и параметры, которые можно использовать для управления визуализацией файлов данных хранилища почты (например, Lotus Notes или MBox) в компоненте GroupDocs.Viewer.

Для получения подробностей см. [документацию][].

Пример использования:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Получает ключевые слова, используемые для фильтрации сообщений. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Устанавливает ключевые слова, используемые для фильтрации сообщений. |
| [getAddressFilter()](#getAddressFilter--) | Получает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Устанавливает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю. |
| [getMaxItems()](#getMaxItems--) | Получает максимальное количество сообщений или элементов для визуализации. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Устанавливает максимальное количество сообщений или элементов для визуализации. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Получает ключевые слова, используемые для фильтрации сообщений.

Используйте это свойство для визуализации всех сообщений, содержащих определённый текст в теме или теле. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - ключевые слова, используемые для фильтрации сообщений.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Устанавливает ключевые слова, используемые для фильтрации сообщений.

Используйте это свойство для визуализации всех сообщений, содержащих определённый текст в теме или теле. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| textFilter | java.lang.String | Ключевые слова, используемые для фильтрации сообщений. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Получает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю.

Используйте это свойство для визуализации всех сообщений, содержащих определённый текст в адресе отправителя или получателя. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - адрес электронной почты, используемый для фильтрации сообщений.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Устанавливает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю.

Используйте это свойство для визуализации всех сообщений, содержащих определённый текст в адресе отправителя или получателя. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| addressFilter | java.lang.String | Электронный адрес, используемый для фильтрации сообщений. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Получает максимальное количество сообщений или элементов для визуализации.

Файлы данных Lotus Notes могут быть большими, и получение всех сообщений может занять значительное время. Эта настройка ограничивает максимальное количество сообщений или элементов, которые отображаются.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int — максимальное количество сообщений или элементов для отображения.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Устанавливает максимальное количество сообщений или элементов для визуализации.

Файлы данных Lotus Notes могут быть большими, и получение всех сообщений может занять значительное время. Эта настройка ограничивает максимальное количество сообщений или элементов, которые отображаются.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxItems | int | Максимальное количество сообщений или элементов для отображения. |

