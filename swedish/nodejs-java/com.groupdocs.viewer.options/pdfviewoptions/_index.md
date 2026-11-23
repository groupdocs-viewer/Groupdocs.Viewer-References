---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av dokument till PDF-format."
type: docs
weight: 23
url: /sv/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Tillhandahåller alternativ för rendering av dokument till PDF-format.

PdfViewOptions-klassen kapslar in ytterligare inställningar och parametrar som kan användas för att styra rendering av dokument till PDF-format i GroupDocs.Viewer-komponenten. För detaljer, se [dokumentation][].

Exempel på användning:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Initierar en ny instans av PdfViewOptions-klassen. |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Initierar en ny instans av PdfViewOptions-klassen. |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | Initierar en ny instans av PdfViewOptions-klassen. |
| [PdfViewOptions()](#PdfViewOptions--) | Initierar en ny instans av PdfViewOptions-klassen med standardinställningar. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Initierar en ny instans av PdfViewOptions-klassen. |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Initierar en ny instans av PdfViewOptions-klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Minska storleken på den genererade PDF-filen genom att tillämpa optimeringstekniker med olika alternativ. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Minska storleken på den genererade PDF-filen genom att tillämpa optimeringstekniker med olika alternativ. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Hämtar den maximala bredden på en utdata-bild i pixlar. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Ställer in den maximala bredden på en utdata-bild i pixlar. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Hämtar den maximala höjden på en utdata-bild i pixlar. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Ställer in den maximala höjden på en utdata-bild i pixlar. |
| [getImageWidth()](#getImageWidth--) | Hämtar bredden på utdata-bilden i pixlar. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Ställer in bredden på utdata-bilden i pixlar. |
| [getImageHeight()](#getImageHeight--) | Hämtar höjden på den utgående bilden i pixlar. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Ställer in höjden på den utgående bilden i pixlar. |
| [getSecurity()](#getSecurity--) | Hämtar säkerhetsalternativen för det utgående PDF-dokumentet. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Ställer in säkerhetsalternativen för det utgående PDF-dokumentet. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Hämtar återanropet som används för att uppskatta framsteg vid sparande av ett Words- eller e‑postdokument. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Ställer in återanropet som används för att uppskatta framsteg vid sparande av ett Words- eller e‑postdokument. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Initierar en ny instans av PdfViewOptions-klassen.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Initierar en ny instans av PdfViewOptions-klassen.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Metoden som används för att instansiera strömmen för att skriva utdatafilens data. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | Metoden som används för att frigöra strömmen som skapats av metoden  createFileStream . |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


Initierar en ny instans av PdfViewOptions-klassen.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Fabriken som implementerar metoder för att skapa och frigöra utdatafilströmmen. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


Initierar en ny instans av PdfViewOptions-klassen med standardinställningar.

Denna konstruktor skapar ett nytt  PdfViewOptions  -objekt med "output.pdf" som filvägsformat för utdatafilen. Utdatafilen kommer att placeras i applikationens aktuella arbetskatalog. För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Initierar en ny instans av PdfViewOptions-klassen.

Denna konstruktor skapar ett nytt  PdfViewOptions  -objekt med den angivna parametern  outputFilePath  som representerar sökvägen för utdata-PDF-filen. För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFilePath | java.lang.String | Sökvägen för utdata-PDF-filen. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Initierar en ny instans av PdfViewOptions-klassen.

För kodexemplet, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Sökvägen för utdata-PDF-filen. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Minska storleken på den genererade PDF-filen genom att tillämpa optimeringstekniker med olika alternativ.

Detta alternativ stöds för alla indatafilformat som stöds för konvertering till PDF: [Supported document formats][] För detaljer och kodexempel, se denna [page][] och dess underordnade.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Minska storleken på den genererade PDF-filen genom att tillämpa optimeringstekniker med olika alternativ.

Detta alternativ stöds för alla indatafilformat som stöds för konvertering till PDF: [Supported document formats][] För detaljer och kodexempel, se denna [page][] och dess underordnade.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions-objekt eller null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Hämtar den maximala bredden på en utgående bild i pixlar. Denna parameter gäller endast vid konvertering av en enskild bild till HTML.

Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap när en enskild bild renderas till PDF. För detaljer, se [documentation][]. Om du sätter  property, ignoreras denna egenskap.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int – den maximala bredden på utdatabilden i pixlar.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Ställer in den maximala bredden på en utgående bild i pixlar. Denna parameter gäller endast vid konvertering av en enskild bild till HTML.

Använd den här egenskapen för att ange den maximala bredden på utdatabilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap när en enskild bild renderas till PDF. För detaljer, se [documentation][]. Om du sätter  property, ignoreras denna egenskap.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageMaxWidth | int | Den maximala bredden på utdatabilden i pixlar. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Hämtar den maximala höjden på en utgående bild i pixlar. Denna parameter gäller endast vid konvertering av en enskild bild till HTML.

Använd den här egenskapen för att ange den maximala höjden på utdatabilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap när en enskild bild renderas till PDF. För detaljer, se [documentation][]. Om du sätter  property, ignoreras denna egenskap.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int – den maximala höjden på utdatabilden i pixlar.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Ställer in den maximala höjden för en utdata bild i pixlar. Denna parameter gäller endast vid konvertering av en enda bild till HTML.

Använd den här egenskapen för att ange den maximala höjden på utdata bilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap endast när en enda bild renderas till HTML. För detaljer, se [documentation][]. Om du anger  egenskapen, ignoreras denna egenskap.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageMaxHeight | int | Den maximala höjden på utdata bilden i pixlar. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Hämtar bredden på utdata bilden i pixlar. Denna parameter gäller endast vid konvertering av en enda bild till HTML.

Använd den här egenskapen för att ange bredden på utdata bilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap när en enda bild renderas till PDF. För detaljer, se [documentation][]. Om du anger denna egenskap, ignoreras  egenskapen.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - bredden på utdata bilden i pixlar.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Ställer in bredden på utdata bilden i pixlar. Denna parameter gäller endast vid konvertering av en enda bild till PDF.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageWidth | int | Bredden på utdata bilden i pixlar. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Hämtar höjden på utdata bilden i pixlar. Denna parameter gäller endast vid konvertering av en enda bild till HTML.

Använd den här egenskapen för att ange höjden på utdata bilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap endast när en enda bild renderas till HTML. För detaljer, se [documentation][]. Om du anger denna egenskap, ignoreras  egenskapen.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - höjden på utdata bilden i pixlar.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Ställer in höjden på utdata bilden i pixlar. Denna parameter gäller endast vid konvertering av en enda bild till HTML.

Använd den här egenskapen för att ange höjden på utdata bilden (i pixlar). GroupDocs.Viewer tillämpar denna egenskap endast när en enda bild renderas till HTML. För detaljer, se [documentation][]. Om du anger denna egenskap, ignoreras  egenskapen.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageHeight | int | Höjden på utdata bilden i pixlar. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Hämtar säkerhetsalternativen för det utgående PDF-dokumentet.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Ställer in säkerhetsalternativen för det utgående PDF-dokumentet.

För mer information, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Säkerhetsalternativen för utdata PDF-dokumentet. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Hämtar återanropet som används för att uppskatta framsteg vid sparande av ett Words- eller e‑postdokument.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - återanropet för att uppskatta dokumentets sparningsförlopp.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Ställer in återanropet som används för att uppskatta framsteg vid sparande av ett Words- eller e‑postdokument.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Återanropet för att uppskatta dokumentets sparningsförlopp. |

