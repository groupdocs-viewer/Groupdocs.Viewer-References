---
title: FixedLayout
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Il PDF è un formato fisso quindi tutti gli elementi hanno una posizione specifica su una pagina. Per garantire che lHTML di output abbia lo stesso aspetto del PDF di origine i documenti vengono visualizzati in HTML con un layout fisso per impostazione predefinita. Quando si esegue il rendering con layout fisso lHTML di output ha dimensioni fisse in modo che gli elementi rimarranno nella stessa posizione indipendentemente dalle dimensioni della finestra. Per eseguire il rendering in HTML con layout fluido imposta questa proprietà sufalso .
type: docs
weight: 50
url: /it/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---
## PdfOptions.FixedLayout property

Il PDF è un formato fisso, quindi tutti gli elementi hanno una posizione specifica su una pagina. Per garantire che l'HTML di output abbia lo stesso aspetto del PDF di origine, i documenti vengono visualizzati in HTML con un layout fisso per impostazione predefinita. Quando si esegue il rendering con layout fisso l'HTML di output ha dimensioni fisse in modo che gli elementi rimarranno nella stessa posizione indipendentemente dalle dimensioni della finestra. Per eseguire il rendering in HTML con layout fluido imposta questa proprietà su`falso` .

```csharp
public bool FixedLayout { get; set; }
```

### Osservazioni

Il valore predefinito è`VERO` .

Questa opzione è supportata durante il rendering in HTML.

Quando si esegue il rendering su layout fluido, le immagini vengono saltate. Utilizzare il layout fluido durante il rendering di documenti PDF con contenuto testuale.

### Esempi

Questo esempio mostra come convertire un documento PDF in HTML con un layout fluido.

```csharp
using GroupDocs.Viewer;
using GroupDocs.Viewer.Options;
//..

using (var viewer = new Viewer("resume.pdf"))
{
   var viewOptions = HtmlViewOptions.ForEmbeddedResources("page_{0}.html");
   viewOptions.FixedLayout = false;
   viewer.View(viewOptions);
}        
```

### Guarda anche

* class [PdfOptions](../../pdfoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pdfoptions)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
