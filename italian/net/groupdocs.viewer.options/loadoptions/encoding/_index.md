---
title: Encoding
second_title: Riferimento API GroupDocs.Viewer per .NET
description: La codifica utilizzata durante lapertura di file di testo o messaggi email come CSVgroupdocs.viewer/filetype/csv  TXTgroupdocs.viewer/filetype/txt  eMSGgroupdocs.viewer/filetype/msg . Il valore predefinito èUTF8 .
type: docs
weight: 30
url: /it/net/groupdocs.viewer.options/loadoptions/encoding/
---
## LoadOptions.Encoding property

La codifica utilizzata durante l'apertura di file di testo o messaggi e-mail come [`CSV`](../../../groupdocs.viewer/filetype/csv) , [`TXT`](../../../groupdocs.viewer/filetype/txt) , e[`MSG`](../../../groupdocs.viewer/filetype/msg) . Il valore predefinito èUTF8 .

```csharp
public Encoding Encoding { get; set; }
```

### Osservazioni

**Saperne di più**

* [Visualizza fogli di calcolo Excel e Apple Numbers come file HTML, PDF e immagine](https://docs.groupdocs.com/viewer/net/render-excel-and-apple-numbers-spreadsheets/)
* [Renderizza i documenti di testo come HTML, PDF e file immagine](https://docs.groupdocs.com/viewer/net/render-text-files)
* [Visualizza i messaggi e-mail come file HTML, PDF, PNG e JPEG](https://docs.groupdocs.com/viewer/net/render-email-messages/)

### Esempi

L'esempio mostra un utilizzo tipico di questa opzione.

```csharp
LoadOptions loadOptions = new LoadOptions();
loadOptions.Encoding = Encoding.ASCII; // Imposta la codifica

using (Viewer viewer = new Viewer("message.txt", loadOptions))
{
    HtmlViewOptions viewOptions = 
        HtmlViewOptions.ForEmbeddedResources();

    viewer.View(viewOptions);
}
```

### Guarda anche

* class [LoadOptions](../../loadoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../loadoptions)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
