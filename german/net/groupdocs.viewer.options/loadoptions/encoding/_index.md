---
title: Encoding
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Die Codierung die beim Öffnen textbasierter Dateien oder EMailNachrichten wie verwendet wird.CSVgroupdocs.viewer/filetype/csv  TXTgroupdocs.viewer/filetype/txt  undMSGgroupdocs.viewer/filetype/msg . Standardwert istUTF8 .
type: docs
weight: 30
url: /de/net/groupdocs.viewer.options/loadoptions/encoding/
---
## LoadOptions.Encoding property

Die Codierung, die beim Öffnen textbasierter Dateien oder E-Mail-Nachrichten wie verwendet wird.[`CSV`](../../../groupdocs.viewer/filetype/csv) , [`TXT`](../../../groupdocs.viewer/filetype/txt) , und[`MSG`](../../../groupdocs.viewer/filetype/msg) . Standardwert istUTF8 .

```csharp
public Encoding Encoding { get; set; }
```

### Bemerkungen

**Erfahren Sie mehr**

* [Rendern Sie Excel- und Apple Numbers-Tabellen als HTML-, PDF- und Bilddateien](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/)
* [Rendern Sie Textdokumente als HTML-, PDF- und Bilddateien](https://docs.groupdocs.com/viewer/net/render-text-files)
* [Rendern Sie E-Mail-Nachrichten als HTML-, PDF-, PNG- und JPEG-Dateien](https://docs.groupdocs.com/viewer/net/render-email-messages/)

### Beispiele

Das Beispiel zeigt eine typische Verwendung dieser Option.

```csharp
LoadOptions loadOptions = new LoadOptions();
loadOptions.Encoding = Encoding.ASCII; // Codierung festlegen

using (Viewer viewer = new Viewer("message.txt", loadOptions))
{
    HtmlViewOptions viewOptions = 
        HtmlViewOptions.ForEmbeddedResources();

    viewer.View(viewOptions);
}
```

### Siehe auch

* class [LoadOptions](../../loadoptions)
* namensraum [GroupDocs.Viewer.Options](../../loadoptions)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
