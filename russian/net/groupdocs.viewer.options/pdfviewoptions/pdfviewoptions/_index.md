---
title: "PdfViewOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

Инициализирует экземпляр класса [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createFileStream | CreateFileStream | Метод, который создает поток, используемый для записи данных выходного файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createFileStream* равен null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### См. также

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Инициализирует экземпляр класса [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createFileStream | CreateFileStream | Метод, который создает поток, используемый для записи данных выходного файла. |
| releaseFileStream | ReleaseFileStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному параметру *createFileStream*. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createFileStream* равен null. |
| ArgumentNullException | Выбрасывается, когда *releaseFileStream* равен null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### См. также

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Инициализирует экземпляр класса [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | Фабрика, реализующая методы создания и освобождения выходного файлового потока. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *fileStreamFactory* имеет значение null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### См. также

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Инициализирует экземпляр класса [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions()
```

### Примечания

Этот конструктор инициализирует экземпляр [`PdfViewOptions`](../../pdfviewoptions) с "output.pdf" в качестве формата пути к выходному файлу. Выходной файл будет помещён в текущий рабочий каталог приложения.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### См. также

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Инициализирует экземпляр класса [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(string outputFilePath)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| outputFilePath | String | Путь к выходному PDF‑файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *outputFilePath* имеет значение null или пустой. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### См. также

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
