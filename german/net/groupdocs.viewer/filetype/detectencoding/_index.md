---
title: "DetectEncoding"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Versucht, die Kodierung von Text‑TXTgroupdocs.viewer/filetype/txt‑TSVgroupdocs.viewer/filetype/tsv‑ und CSVgroupdocs.viewer/filetype/csv‑Dateien anhand des Pfads zu erkennen."
type: docs
weight: 2060
url: /de/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

Versucht, die Kodierung von Text‑[`TXT`](../txt), [`TSV`](../tsv) und [`CSV`](../csv)‑Dateien anhand des Pfads zu erkennen.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateiname oder der Dateipfad. |

### Rückgabewert

Kodierung oder null, wenn die Erkennung einer Dateikodierung fehlschlägt.

### Beispiele

Das Beispiel zeigt, wie die Kodierung einer Textdatei erkannt wird.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### Siehe auch

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

Versuche, die Textkodierung von [`TXT`](../txt), [`TSV`](../tsv) und [`CSV`](../csv) Dateien per Stream zu erkennen.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |

### Rückgabewert

Kodierung oder null, wenn die Erkennung einer Dateikodierung fehlschlägt.

### Beispiele

Das Beispiel zeigt, wie die Kodierung einer Textdatei erkannt wird.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### Siehe auch

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
