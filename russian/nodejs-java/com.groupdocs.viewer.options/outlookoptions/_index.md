---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга файлов данных Outlook."
type: docs
weight: 20
url: /ru/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Предоставляет параметры для рендеринга файлов данных Outlook.

Класс OutlookOptions инкапсулирует различные настройки и параметры, которые можно использовать для управления рендерингом файлов данных Outlook (например, файлов PST или OST) в компоненте GroupDocs.Viewer.

Для получения подробностей см. [документацию][].

Пример использования:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getFolder()](#getFolder--) | Получает имя папки для рендеринга. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Устанавливает имя папки для рендеринга. |
| [getTextFilter()](#getTextFilter--) | Получает ключевые слова, используемые для фильтрации сообщений. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Получает ключевые слова, используемые для фильтрации сообщений. |
| [getAddressFilter()](#getAddressFilter--) | Получает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Устанавливает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Получает максимальное количество сообщений или элементов, которые могут быть отрисованы из одной папки. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Устанавливает максимальное количество сообщений или элементов, которые могут быть отрисованы из одной папки. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Получает имя папки для рендеринга. Имя папки (например, Inbox, Sent Item или Deleted Items), которую нужно отрисовать.

При рендеринге файла данных Outlook GroupDocs.Viewer отображает сообщения из всех папок, содержащихся в файле (включая вложенные папки). Используйте это свойство для отображения элементов из конкретной папки. Для примера кода см. эту [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - имя папки для отображения.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Устанавливает имя папки для отображения. Имя папки (например, Inbox, Sent Item или Deleted Items), которую нужно отобразить.

При рендеринге файла данных Outlook GroupDocs.Viewer отображает сообщения из всех папок, содержащихся в файле (включая вложенные папки). Используйте это свойство для отображения элементов из конкретной папки. Для примера кода см. эту [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Имя папки для отображения. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Получает ключевые слова, используемые для фильтрации сообщений.

Используйте это свойство для визуализации всех сообщений, содержащих определённый текст в теме или теле. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - ключевые слова.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Получает ключевые слова, используемые для фильтрации сообщений.

Используйте это свойство для визуализации всех сообщений, содержащих определённый текст в теме или теле. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Ключевые слова. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Получает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю.

Используйте это свойство для отображения всех сообщений, содержащих определённый текст в адресе отправителя\\ufffds или получателя\\ufffds. Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - адрес электронной почты, используемый для фильтрации сообщений.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Устанавливает адрес электронной почты, используемый для фильтрации сообщений по отправителю или получателю.

Используйте это свойство для отображения всех сообщений, содержащих определённый текст в адресе отправителя\\ufffds или получателя\\ufffds. Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Адрес электронной почты, используемый для фильтрации сообщений. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Получает максимальное количество сообщений или элементов, которые могут быть отрисованы из одной папки.

Файлы данных Outlook могут быть большими, и получение всех сообщений может занять значительное время. Эта настройка ограничивает максимальное количество сообщений или элементов (например, контактов и задач), которые отображаются. Значение по умолчанию — 50. Установите значение 0, чтобы отобразить все сообщения. Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - максимальное количество сообщений или элементов, которые могут быть отображены из одной папки.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Устанавливает максимальное количество сообщений или элементов, которые могут быть отрисованы из одной папки.

Файлы данных Outlook могут быть большими, и получение всех сообщений может занять значительное время. Эта настройка ограничивает максимальное количество сообщений или элементов (например, контактов и задач), которые отображаются. Значение по умолчанию — 50. Установите значение 0, чтобы отобразить все сообщения. Для примера кода см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Максимальное количество сообщений или элементов, которые могут быть отображены из одной папки. |

