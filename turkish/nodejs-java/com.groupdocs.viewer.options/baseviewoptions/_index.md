---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Temel renderleme seçeneklerini içerir."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Temel renderleme seçeneklerini içerir.

BaseViewOptions sınıfı, GroupDocs.Viewer içinde render seçenekleri için temel görevi görür. Belirli belge formatlarını render ederken çıktı HTML, PDF, PNG ve JPEG dosyalarının render davranışını özelleştirmenize olanak tanır.

***Note:** For internal usage.*
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextOptions()](#getTextOptions--) | Metin dosyalarını sayfalara bölme seçeneklerini alır. |
| [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Metin dosyalarını sayfalara bölme seçeneklerini ayarlar. |
| [isRenderComments()](#isRenderComments--) | Yorumların render edilmesini etkinleştirir. |
| [setRenderComments(boolean value)](#setRenderComments-boolean-) | Yorumların render edilmesini etkinleştirir. |
| [isRemoveComments()](#isRemoveComments--) | true olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. |
| [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | true olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. |
| [isRenderNotes()](#isRenderNotes--) | Notların render edilmesini etkinleştirir. |
| [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Notların render edilmesini etkinleştirir. |
| [isRenderHiddenPages()](#isRenderHiddenPages--) | Gizli sayfaların render edilmesini etkinleştirir. |
| [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Gizli sayfaların render edilmesini etkinleştirir. |
| [getDefaultFontName()](#getDefaultFontName--) | Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
| [getArchiveOptions()](#getArchiveOptions--) | Arşiv dosyalarının görüntüleme seçeneklerini alır. |
| [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Arşiv dosyalarının görüntüleme seçeneklerini ayarlar. |
| [getCadOptions()](#getCadOptions--) | CAD çiziminin görüntüleme seçeneklerini alır. |
| [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | CAD çiziminin görüntüleme seçeneklerini ayarlar. |
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
| [getEmailOptions()](#getEmailOptions--) | E-posta mesajlarının görüntüleme seçeneklerini alır. |
| [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | E-posta mesajlarının görüntüleme seçeneklerini ayarlar. |
| [getOutlookOptions()](#getOutlookOptions--) | MS Outlook veri dosyalarının görüntüleme seçeneklerini alır. |
| [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | MS Outlook veri dosyalarının görüntüleme seçeneklerini ayarlar. |
| [getPdfOptions()](#getPdfOptions--) | PDF belgelerinin görüntüleme seçeneklerini alır. |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | PDF belgelerinin görüntüleme seçeneklerini alır. |
| [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes depolama veri dosyalarının görüntüleme seçeneklerini alır. |
| [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes depolama veri dosyalarının görüntüleme seçeneklerini ayarlar. |
| [getProjectManagementOptions()](#getProjectManagementOptions--) | Proje yönetimi dosyalarının görüntüleme seçeneklerini alır. |
| [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Proje yönetimi dosyalarının görüntüleme seçeneklerini ayarlar. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Elektronik tablo dosyalarının görüntüleme seçeneklerini alır. |
| [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Elektronik tablo dosyalarının görüntüleme seçeneklerini ayarlar. |
| [getWordProcessingOptions()](#getWordProcessingOptions--) | Word işlem dosyalarının görüntüleme seçenekleri. |
| [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Word işlem dosyalarının görüntüleme seçenekleri. |
| [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Belge görüntülerken Visio dosyalarını işlemek için oluşturma seçeneklerini alır. |
| [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Belge görüntülerken Visio dosyalarını işlemek için oluşturma seçeneklerini ayarlar. |
| [getPresentationOptions()](#getPresentationOptions--) | Sunum belgelerini işlemek için görüntüleme seçeneklerini alır. |
| [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Sunum belgelerini işlemek için görüntüleme seçeneklerini ayarlar. |
| [getWebDocumentOptions()](#getWebDocumentOptions--) | Web belgelerini oluştururken çıktı HTML/PDF/PNG/JPEG görünümünün özelleştirilmesini sağlayan oluşturma seçeneklerini alır. |
| [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Web belgelerini oluştururken çıktı HTML/PDF/PNG/JPEG görünümünün özelleştirilmesini sağlayan oluşturma seçeneklerini ayarlar. |
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Metin dosyalarını sayfalara bölme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.
### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Metin dosyalarını sayfalara bölme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Metin dosyası bölme seçenekleri. |

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Yorumların render edilmesini etkinleştirir.

Varsayılan olarak, GroupDocs.Viewer yorumları oluşturmaz. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Returns:**
boolean -  true  yorumların oluşturulması gerekiyorsa,  false  aksi takdirde.
### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Yorumların render edilmesini etkinleştirir.

Varsayılan olarak, GroupDocs.Viewer yorumları oluşturmaz. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  yorumların oluşturulması gerekiyorsa,  false  aksi takdirde. |

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


true olarak ayarlandığında yorum oluşturmayı devre dışı bırakır. Varsayılan olarak false \\u2014 tüm yorumlar görüntülenir.

PDF ve WordProcessing gibi bazı belge formatları yorum içerebilir. Varsayılan olarak GroupDocs.Viewer bunları oluşturur. Bu seçenek true olarak ayarlandığında yorumlar sonuç belgede dışlanabilir. Bu seçenek eski 'RenderComments' özelliğinin yerini alır.

**Returns:**
boolean -  true  yorumların oluşturulması gerekiyorsa,  false  aksi takdirde.
### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


true olarak ayarlandığında yorum oluşturmayı devre dışı bırakır. Varsayılan olarak false \\u2014 tüm yorumlar görüntülenir.

PDF ve WordProcessing gibi bazı belge formatları yorum içerebilir. Varsayılan olarak GroupDocs.Viewer bunları oluşturur. Bu seçenek true olarak ayarlandığında yorumlar sonuç belgede dışlanabilir. Bu seçenek eski 'RenderComments' özelliğinin yerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  yorumların oluşturulması gerekiyorsa,  false  aksi takdirde. |

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Notların render edilmesini etkinleştirir.

Sunumlar veya Microsoft proje dosyaları gibi bazı dosyalar not içerebilir. Varsayılan olarak, GroupDocs.Viewer notları oluşturmaz. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes

**Returns:**
boolean -  true  notların oluşturulması gerekiyorsa,  false  aksi takdirde.
### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Notların render edilmesini etkinleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  notların oluşturulması gerekiyorsa,  false  aksi takdirde. |

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Gizli sayfaların render edilmesini etkinleştirir.

Sunumlar veya elektronik tablolar gibi bazı dosyalar gizli sayfalar içerebilir. Varsayılan olarak, GroupDocs.Viewer bu sayfaları oluşturmaz. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Returns:**
boolean -  true  gizli sayfalar render edilmeliyse,  false  aksi takdirde.
### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Gizli sayfaların render edilmesini etkinleştirir.

Sunumlar veya elektronik tablolar gibi bazı dosyalar gizli sayfalar içerebilir. Varsayılan olarak, GroupDocs.Viewer bu sayfaları oluşturmaz. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  gizli sayfalar render edilmeliyse,  false  aksi takdirde. |

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi.

Bu özelliği bir belge için varsayılan yazı tipini ayarlamak için kullanın. GroupDocs.Viewer, kurulu olmayan yazı tipleri yerine render sırasında bu yazı tipini kullanır. Kod örnekleri için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Returns:**
java.lang.String - varsayılan yazı tipinin adı.
### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi.

Bu özelliği bir belge için varsayılan yazı tipini ayarlamak için kullanın. GroupDocs.Viewer, kurulu olmayan yazı tipleri yerine render sırasında bu yazı tipini kullanır. Kod örnekleri için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/replace-missing-font/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Varsayılan yazı tipinin adı. |

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Arşiv dosyalarının görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.
### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Arşiv dosyalarının görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Arşiv dosyalarının görüntüleme seçenekleri. |

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


CAD çiziminin görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için, [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] ve [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.
### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


CAD çiziminin görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için, [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] ve [Specify rendering options for CAD files][].


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD çizimi görüntüleme seçenekleri. |

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


E-posta mesajlarının görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.
### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


E-posta mesajlarının görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | E-posta mesajları görüntüleme seçenekleri. |

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


MS Outlook veri dosyalarının görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.
### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


MS Outlook veri dosyalarının görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Ayarlanacak MS Outlook veri dosyaları görüntüleme seçenekleri. |

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF belgelerinin görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF belgelerinin görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF belgeleri görüntüleme seçenekleri. |

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes depolama veri dosyalarının görüntüleme seçeneklerini alır.

**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.
### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes depolama veri dosyalarının görüntüleme seçeneklerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes depolama veri dosyaları görüntüleme seçenekleri. |

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Proje yönetimi dosyalarının görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.
### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Proje yönetimi dosyalarının görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Ayarlanacak proje yönetimi dosyaları görüntüleme seçenekleri. |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Elektronik tablo dosyalarının görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için, [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Split a worksheet into pages][], ve [Specify spreadsheet rendering options][] bağlantılarına bakın.


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.
### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Elektronik tablo dosyalarının görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için, [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files], [Split a worksheet into pages][], ve [Specify spreadsheet rendering options][] bağlantılarına bakın.


[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Split a worksheet into pages]: https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/
[Specify spreadsheet rendering options]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Elektronik tablo dosyaları görüntüleme seçenekleri. |

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Word işlem dosyalarının görüntüleme seçenekleri.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.
### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Word işlem dosyalarının görüntüleme seçenekleri.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-word-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word belgelerini render etmek için Word işleme seçenekleri. |

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Belge görüntülerken Visio dosyalarını işlemek için oluşturma seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.
### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Belge görüntülerken Visio dosyalarını işlemek için oluşturma seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio dosyalarını işlemek için Visio render seçenekleri. |

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Sunum belgelerini işlemek için görüntüleme seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Returns:**
com.groupdocs.viewer.options.PresentationOptions - sunum belgelerini işlemek için sunum görüntüleme seçenekleri.
### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Sunum belgelerini işlemek için görüntüleme seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Sunum belgelerini işlemek için sunum görüntüleme seçenekleri. |

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Web belgelerini oluştururken çıktı HTML/PDF/PNG/JPEG görünümünün özelleştirilmesini sağlayan oluşturma seçeneklerini alır.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - WebDocumentOptions nesnesi render seçeneklerini özelleştirmek için.
### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Web belgelerini oluştururken çıktı HTML/PDF/PNG/JPEG görünümünün özelleştirilmesini sağlayan oluşturma seçeneklerini ayarlar.

Daha fazla bilgi ve kod örnekleri için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-web-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | Render seçeneklerini özelleştirmek için WebDocumentOptions nesnesi. |

