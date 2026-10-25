---
title: "BaseViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Содержит базовые параметры рендеринга."
type: docs
weight: 12
url: /ru/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Содержит базовые параметры рендеринга.


Эта
BaseViewOptions
класс служит базой для параметров рендеринга в GroupDocs.Viewer.
Он позволяет настроить поведение рендеринга выходных файлов HTML, PDF, PNG и JPEG при рендеринге
конкретных форматов документов.


***Note:** For internal usage.*

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Получает параметры разбиения текстовых файлов на страницы. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Устанавливает параметры разбиения текстовых файлов на страницы. |
|
|  | [isRenderComments()](#isRenderComments--) | Включает рендеринг комментариев. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Включает рендеринг комментариев. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Отключает рендеринг комментариев, когда установлено в true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Отключает рендеринг комментариев, когда установлено в true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Включает рендеринг заметок. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Включает рендеринг заметок. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Включает рендеринг скрытых страниц. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Включает рендеринг скрытых страниц. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Шрифт по умолчанию, который будет использоваться, когда определенный шрифт, используемый в документе, не найден. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Шрифт по умолчанию, который будет использоваться, когда определенный шрифт, используемый в документе, не найден. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Получает параметры просмотра архивных файлов. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Устанавливает параметры просмотра архивных файлов. |
|
|  | [getCadOptions()](#getCadOptions--) | Получает параметры просмотра CAD‑чертежей. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Устанавливает параметры просмотра CAD‑чертежей. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Получает параметры просмотра электронных сообщений. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Устанавливает параметры просмотра электронных сообщений. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Получает параметры просмотра файлов данных MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Устанавливает параметры просмотра файлов данных MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Получает параметры просмотра PDF‑документов. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Получает параметры просмотра PDF‑документов. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Получает параметры просмотра файлов хранилища Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Устанавливает параметры просмотра файлов хранилища Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Получает параметры просмотра файлов управления проектами. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Устанавливает параметры просмотра файлов управления проектами. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Получает параметры просмотра файлов электронных таблиц. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Устанавливает параметры просмотра файлов электронных таблиц. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Параметры просмотра файлов обработки Word. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Параметры просмотра файлов обработки Word. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Получает параметры рендеринга для обработки файлов Visio при просмотре документов. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Устанавливает параметры рендеринга для обработки файлов Visio при просмотре документов. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Получает параметры просмотра для обработки презентационных документов. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Устанавливает параметры просмотра для обработки презентационных документов. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Получает параметры рендеринга, позволяющие настраивать внешний вид выходных файлов HTML/PDF/PNG/JPEG |
при рендеринге веб‑документов.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Устанавливает параметры рендеринга, позволяющие настраивать внешний вид выходных файлов HTML/PDF/PNG/JPEG |
при рендеринге веб‑документов.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Получает параметры разбиения текстовых файлов на страницы.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Устанавливает параметры разбиения текстовых файлов на страницы.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Параметры разбиения текстовых файлов. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Включает рендеринг комментариев.


По умолчанию GroupDocs.Viewer не отображает комментарии. Чтобы включить их, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean —  true  если комментарии должны отображаться,  false  в противном случае.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Включает рендеринг комментариев.


По умолчанию GroupDocs.Viewer не отображает комментарии. Чтобы включить их, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  если комментарии должны отображаться,  false  в противном случае. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Отключает отображение комментариев, когда установлено в true. По умолчанию false \\u2014 все комментарии отображаются.


Некоторые форматы документов, такие как PDF и WordProcessing, могут содержать комментарии. По умолчанию GroupDocs.Viewer отображает их. При установке этой опции в true комментарии могут быть исключены из результирующего документа.
Эта опция заменяет устаревшее свойство 'RenderComments'.


**Returns:**
boolean —  true  если комментарии должны отображаться,  false  в противном случае.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Отключает отображение комментариев, когда установлено в true. По умолчанию false \\u2014 все комментарии отображаются.


Некоторые форматы документов, такие как PDF и WordProcessing, могут содержать комментарии. По умолчанию GroupDocs.Viewer отображает их. При установке этой опции в true комментарии могут быть исключены из результирующего документа.
Эта опция заменяет устаревшее свойство 'RenderComments'.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  если комментарии должны отображаться,  false  в противном случае. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Включает рендеринг заметок.


Некоторые файлы, такие как презентации или файлы Microsoft Project, могут содержать заметки. По умолчанию GroupDocs.Viewer не отображает заметки. Чтобы включить их, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean —  true  если заметки должны отображаться,  false  в противном случае.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Включает рендеринг заметок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  если заметки должны отображаться,  false  в противном случае. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Включает рендеринг скрытых страниц.


Некоторые файлы, такие как презентации или электронные таблицы, могут содержать скрытые страницы. По умолчанию GroupDocs.Viewer не отображает эти страницы. Чтобы включить их, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  если скрытые страницы должны быть отрисованы,  false  в противном случае.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Включает рендеринг скрытых страниц.


Некоторые файлы, такие как презентации или электронные таблицы, могут содержать скрытые страницы. По умолчанию GroupDocs.Viewer не отображает эти страницы. Чтобы включить их, установите это свойство в true.
Для примера кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  если скрытые страницы должны быть отрисованы,  false  в противном случае. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Шрифт по умолчанию, который будет использоваться, когда определенный шрифт, используемый в документе, не найден.


Используйте это свойство, чтобы задать шрифт по умолчанию для документа. GroupDocs.Viewer использует этот шрифт при отрисовке вместо любых неустановленных шрифтов.
Для примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - имя шрифта по умолчанию.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Шрифт по умолчанию, который будет использоваться, когда определенный шрифт, используемый в документе, не найден.


Используйте это свойство, чтобы задать шрифт по умолчанию для документа. GroupDocs.Viewer использует этот шрифт при отрисовке вместо любых неустановленных шрифтов.
Для примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | java.lang.String | Имя шрифта по умолчанию. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Получает параметры просмотра архивных файлов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Устанавливает параметры просмотра архивных файлов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Параметры просмотра архивных файлов. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Получает параметры просмотра CAD‑чертежей.


Для получения дополнительной информации и примеров кода см. [Отображение чертежей CAD и моделей в виде HTML, PDF и файлов изображений](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) и [Указание параметров отрисовки для файлов CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Устанавливает параметры просмотра CAD‑чертежей.


Для получения дополнительной информации и примеров кода см. [Отображение чертежей CAD и моделей в виде HTML, PDF и файлов изображений](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) и [Указание параметров отрисовки для файлов CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Параметры просмотра чертежей CAD. |
|

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


Получает параметры просмотра электронных сообщений.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Устанавливает параметры просмотра электронных сообщений.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Параметры просмотра электронных сообщений. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Получает параметры просмотра файлов данных MS Outlook.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Устанавливает параметры просмотра файлов данных MS Outlook.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Параметры просмотра файлов данных MS Outlook, которые следует установить. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Получает параметры просмотра PDF‑документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Получает параметры просмотра PDF‑документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Параметры просмотра PDF‑документов. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Получает параметры просмотра файлов хранилища Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Устанавливает параметры просмотра файлов хранилища Lotus Notes.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Параметры просмотра файлов хранилища Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Получает параметры просмотра файлов управления проектами.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Устанавливает параметры просмотра файлов управления проектами.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Параметры просмотра файлов управления проектами, которые необходимо установить. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Получает параметры просмотра файлов электронных таблиц.


Для получения дополнительной информации и примеров кода см. [Отображение электронных таблиц Excel и Apple Numbers в виде HTML, PDF и файлов изображений](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Разделить лист на страницы](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), и [Указание параметров отрисовки электронных таблиц](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Устанавливает параметры просмотра файлов электронных таблиц.


Для получения дополнительной информации и примеров кода см. [Отображение электронных таблиц Excel и Apple Numbers в виде HTML, PDF и файлов изображений](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Разделить лист на страницы](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), и [Указание параметров отрисовки электронных таблиц](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Параметры просмотра файлов электронных таблиц. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Параметры просмотра файлов обработки Word.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Параметры просмотра файлов обработки Word.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Параметры обработки Word для рендеринга документов Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Получает параметры рендеринга для обработки файлов Visio при просмотре документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Устанавливает параметры рендеринга для обработки файлов Visio при просмотре документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Параметры рендеринга Visio для обработки файлов Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Получает параметры просмотра для обработки презентационных документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions — параметры просмотра презентаций для обработки файлов презентаций.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Устанавливает параметры просмотра для обработки презентационных документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Параметры просмотра презентаций для обработки файлов презентаций. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Получает параметры рендеринга, позволяющие настраивать внешний вид выходных файлов HTML/PDF/PNG/JPEG
при рендеринге веб‑документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions — объект WebDocumentOptions для настройки параметров рендеринга.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Устанавливает параметры рендеринга, позволяющие настраивать внешний вид выходных файлов HTML/PDF/PNG/JPEG
при рендеринге веб‑документов.


Для получения дополнительной информации и примеров кода см. [документацию](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | Объект WebDocumentOptions для настройки параметров рендеринга. |
|

