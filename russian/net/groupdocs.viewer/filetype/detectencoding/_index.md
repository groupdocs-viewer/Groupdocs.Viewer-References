---
title: "DetectEncoding"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Пытается определить кодировку текстовых файлов TXTgroupdocs.viewer/filetype/txt, TSVgroupdocs.viewer/filetype/tsv и CSVgroupdocs.viewer/filetype/csv по пути."
type: docs
weight: 2060
url: /ru/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

Пытается определить кодировку текстовых файлов [`TXT`](../txt), [`TSV`](../tsv) и [`CSV`](../csv) по пути.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| filePath | String | Имя файла или путь к файлу. |

### Возвращаемое значение

Кодировка или null, если не удалось определить кодировку файла.

### Примеры

Пример демонстрирует, как определить кодировку текстового файла.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### См. также

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

Пытается определить кодировку текстового файла [`TXT`](../txt), [`TSV`](../tsv) и [`CSV`](../csv) по потоку.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| поток | Поток | Поток файла. |

### Возвращаемое значение

Кодировка или null, если не удалось определить кодировку файла.

### Примеры

Пример демонстрирует, как определить кодировку текстового файла.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### См. также

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
