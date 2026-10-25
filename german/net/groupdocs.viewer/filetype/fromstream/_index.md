---
title: "FromStream"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Erkennt den Dateityp durch Lesen der Dateisignatur."
type: docs
weight: 2000
url: /de/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```csharp
public static FileType FromStream(Stream stream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |

### Siehe auch

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| Passwort | String | Das Passwort, um die Datei zu öffnen. |

### Siehe auch

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| Logger | ILogger | Der Logger. |

### Rückgabewert

Gibt den Dateityp zurück, falls er erfolgreich erkannt wurde, andernfalls wird der Standard‑[`Unknown`](../unknown) Dateityp zurückgegeben.

### Siehe auch

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| Passwort | String | Das Passwort, um die Datei zu öffnen. |
| Logger | ILogger | Der Logger. |

### Rückgabewert

Gibt den Dateityp zurück, falls er erfolgreich erkannt wurde, andernfalls wird der Standard‑[`Unknown`](../unknown) Dateityp zurückgegeben.

### Siehe auch

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
