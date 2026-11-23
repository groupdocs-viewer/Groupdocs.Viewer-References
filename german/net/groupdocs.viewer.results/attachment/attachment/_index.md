---
title: "Attachment"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse Attachmentgroupdocs.viewer.results/attachment."
type: docs
weight: 10
url: /de/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

Initialisiert eine neue Instanz der Klasse [`Attachment`](../../attachment).

```csharp
public Attachment()
```

### Siehe auch

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`Attachment`](../../attachment).

```csharp
public Attachment(string fileName, string filePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| fileName | String | Dateiname des Anhangs. |
| filePath | String | Relativer Pfad des Anhangs, z. B. Ordner/Datei.docx oder Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder Datendatei liegt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *fileName* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Siehe auch

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

Initialisiert eine neue Instanz der Klasse [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| id | String | Eindeutiger (im Kontext einer einzelnen Datei) Bezeichner des Anhangs. |
| fileName | String | Dateiname des Anhangs. |
| filePath | String | Relativer Pfad des Anhangs, z. B. Ordner/Datei.docx oder Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder Datendatei liegt. |
| Größe | Int64 | Dateigröße des Anhangs in Bytes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *id* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *fileName* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Siehe auch

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

Initialisiert eine neue Instanz der Klasse [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| id | String | Eindeutiger (im Kontext einer einzelnen Datei) Bezeichner des Anhangs. |
| fileName | String | Dateiname des Anhangs. |
| filePath | String | Relativer Pfad des Anhangs, z. B. Ordner/Datei.docx oder Dateiname, wenn die Datei im Stammverzeichnis eines Archivs, in einer E‑Mail‑Nachricht oder Datendatei liegt. |
| fileType | FileType | Dateityp des Anhangs. |
| Größe | Int64 | Dateigröße des Anhangs in Bytes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *id* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *fileName* null oder leer ist. |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *fileType* null ist. |

### Siehe auch

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
