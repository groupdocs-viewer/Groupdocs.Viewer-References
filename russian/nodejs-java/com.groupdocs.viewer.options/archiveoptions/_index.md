---
title: "ArchiveOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет параметры для рендеринга архивных файлов."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Предоставляет параметры для рендеринга архивных файлов.

Класс ArchiveOptions представляет набор параметров, которые можно использовать для настройки рендеринга архивных файлов в модуле просмотра. Он позволяет настраивать различные аспекты процесса рендеринга, такие как количество элементов на каждой странице и т.д.

Пример использования:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Создает новый экземпляр класса ArchiveOptions с настройками по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFolder()](#getFolder--) | Получает папку внутри архива, которая будет использоваться для рендеринга. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Устанавливает папку внутри архива, которая будет использоваться для рендеринга. |
| [getFileName()](#getFileName--) | Получает имя файла, которое будет отображаться в заголовке. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Устанавливает имя файла, которое будет отображаться в заголовке. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Создает новый экземпляр класса ArchiveOptions с настройками по умолчанию.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Получает папку внутри архива, которая будет использоваться для рендеринга.

По умолчанию GroupDocs.Viewer отображает элементы из всех папок, содержащихся в архиве. Чтобы отображать элементы из конкретной папки, установите это свойство. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - папка для отображения.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Устанавливает папку внутри архива, которая будет использоваться для рендеринга.

По умолчанию GroupDocs.Viewer отображает элементы из всех папок, содержащихся в архиве. Чтобы отображать элементы из конкретной папки, установите это свойство. Для примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String | Папка для отображения. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Получает имя файла, которое будет отображаться в заголовке.

По умолчанию GroupDocs.Viewer отображает имя файла архива в заголовке каждой страницы. Чтобы изменить или скрыть это имя, установите это свойство. Для получения дополнительной информации и примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Устанавливает имя файла, которое будет отображаться в заголовке.

По умолчанию GroupDocs.Viewer отображает имя файла архива в заголовке каждой страницы. Чтобы изменить или скрыть это имя, установите это свойство. Для получения дополнительной информации и примера кода см. [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | Имя файла для отображения. |

