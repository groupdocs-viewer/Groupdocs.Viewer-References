---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Temel işleme seçeneklerini içerir."
type: docs
weight: 12
url: /tr/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Temel işleme seçeneklerini içerir.


Bu
BaseViewOptions
class, GroupDocs.Viewer içinde renderleme seçenekleri için temel görevi görür.
Renderleme sırasında çıktı HTML, PDF, PNG ve JPEG dosyalarının renderleme davranışını özelleştirmenizi sağlar.
belirli belge formatları.


***Note:** For internal usage.*

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Metin dosyalarını sayfalara bölme seçeneklerini alır. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Metin dosyalarını sayfalara bölme seçeneklerini ayarlar. |
|
|  | [isRenderComments()](#isRenderComments--) | Yorumların render edilmesini etkinleştirir. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Yorumların render edilmesini etkinleştirir. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Doğru olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Doğru olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Notların render edilmesini etkinleştirir. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Notların render edilmesini etkinleştirir. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Gizli sayfaların render edilmesini etkinleştirir. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Gizli sayfaların render edilmesini etkinleştirir. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Arşiv dosyaları görüntüleme seçeneklerini alır. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Arşiv dosyaları görüntüleme seçeneklerini ayarlar. |
|
|  | [getCadOptions()](#getCadOptions--) | CAD çizim görüntüleme seçeneklerini alır. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | CAD çizim görüntüleme seçeneklerini ayarlar. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | E-posta mesajları görüntüleme seçeneklerini alır. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | E-posta mesajları görüntüleme seçeneklerini ayarlar. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | MS Outlook veri dosyaları görüntüleme seçeneklerini alır. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | MS Outlook veri dosyaları görüntüleme seçeneklerini ayarlar. |
|
|  | [getPdfOptions()](#getPdfOptions--) | PDF belgeleri görüntüleme seçeneklerini alır. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | PDF belgeleri görüntüleme seçeneklerini alır. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Lotus Notes depolama veri dosyaları görüntüleme seçeneklerini alır. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Lotus Notes depolama veri dosyaları görüntüleme seçeneklerini ayarlar. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Proje yönetimi dosyaları görüntüleme seçeneklerini alır. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Proje yönetimi dosyaları görüntüleme seçeneklerini ayarlar. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Elektronik tablo dosyaları görüntüleme seçeneklerini alır. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Elektronik tablo dosyaları görüntüleme seçeneklerini ayarlar. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Kelime işlem dosyaları görüntüleme seçenekleri. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Kelime işlem dosyaları görüntüleme seçenekleri. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Belgeleri görüntülerken Visio dosyalarını işlemek için render seçeneklerini alır. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Belgeleri görüntülerken Visio dosyalarını işlemek için render seçeneklerini ayarlar. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Sunum belgelerini işlemek için görüntüleme seçeneklerini alır. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Sunum belgelerini işlemek için görüntüleme seçeneklerini ayarlar. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Çıktı HTML/PDF/PNG/JPEG'in görünümünü özelleştirmeye izin veren render seçeneklerini alır |
Web belgeleri render edilirken.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Çıktı HTML/PDF/PNG/JPEG'in görünümünü özelleştirmeye izin veren render seçeneklerini ayarlar |
Web belgeleri render edilirken.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Metin dosyalarını sayfalara bölme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/) bakın.


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Metin dosyalarını sayfalara bölme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-text-files/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Metin dosyası bölme seçenekleri. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Yorumların render edilmesini etkinleştirir.


Varsayılan olarak, GroupDocs.Viewer yorumları render etmez. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments) bakın.


**Returns:**
boolean -  true  yorumların render edilmesi durumunda,  false  aksi takdirde.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Yorumların render edilmesini etkinleştirir.


Varsayılan olarak, GroupDocs.Viewer yorumları render etmez. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  yorumların render edilmesi durumunda,  false  aksi takdirde. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


true olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. Varsayılan olarak false \u2014 tüm yorumlar görüntülenir.


PDF ve WordProcessing gibi bazı belge formatları yorumlar içerebilir. Varsayılan olarak GroupDocs.Viewer bunları render eder. Bu seçenek true olarak ayarlandığında yorumlar sonuç belgeden çıkarılabilir.
Bu seçenek, eski 'RenderComments' özelliğinin yerini alır.


**Returns:**
boolean -  true  yorumların render edilmesi durumunda,  false  aksi takdirde.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


true olarak ayarlandığında yorumların render edilmesini devre dışı bırakır. Varsayılan olarak false \u2014 tüm yorumlar görüntülenir.


PDF ve WordProcessing gibi bazı belge formatları yorumlar içerebilir. Varsayılan olarak GroupDocs.Viewer bunları render eder. Bu seçenek true olarak ayarlandığında yorumlar sonuç belgeden çıkarılabilir.
Bu seçenek, eski 'RenderComments' özelliğinin yerini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  yorumların render edilmesi durumunda,  false  aksi takdirde. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Notların render edilmesini etkinleştirir.


Sunumlar veya Microsoft proje dosyaları gibi bazı dosyalar notlar içerebilir. Varsayılan olarak, GroupDocs.Viewer notları render etmez. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes) bakın.


**Returns:**
boolean -  true  notların render edilmesi durumunda,  false  aksi takdirde.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Notların render edilmesini etkinleştirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  notların render edilmesi durumunda,  false  aksi takdirde. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Gizli sayfaların render edilmesini etkinleştirir.


Sunumlar veya elektronik tablolar gibi bazı dosyalar gizli sayfalar içerebilir. Varsayılan olarak, GroupDocs.Viewer bu sayfaları render etmez. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides) bakın.


**Returns:**
boolean -  true  gizli sayfaların render edilmesi durumunda,  false  aksi takdirde.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Gizli sayfaların render edilmesini etkinleştirir.


Sunumlar veya elektronik tablolar gibi bazı dosyalar gizli sayfalar içerebilir. Varsayılan olarak, GroupDocs.Viewer bu sayfaları render etmez. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  gizli sayfaların render edilmesi durumunda,  false  aksi takdirde. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi.


Bu özelliği, bir belge için varsayılan yazı tipini ayarlamak için kullanın. GroupDocs.Viewer render sırasında yüklü olmayan yazı tipleri yerine bu yazı tipini kullanır.
Kod örnekleri için, [belgelere](../https://docs.groupdocs.com/viewer/java/replace-missing-font/) bakın.


**Returns:**
java.lang.String - varsayılan yazı tipinin adı.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Belgede kullanılan belirli bir yazı tipi bulunamadığında kullanılacak varsayılan yazı tipi.


Bu özelliği, bir belge için varsayılan yazı tipini ayarlamak için kullanın. GroupDocs.Viewer render sırasında yüklü olmayan yazı tipleri yerine bu yazı tipini kullanır.
Kod örnekleri için, [belgelere](../https://docs.groupdocs.com/viewer/java/replace-missing-font/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Varsayılan yazı tipinin adı. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Arşiv dosyaları görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-archive-files/) bakın.


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Arşiv dosyaları görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-archive-files/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Arşiv dosyaları görüntüleme seçenekleri. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


CAD çizim görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) ve [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/) adresine bakın.


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


CAD çizim görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) ve [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | CAD çizim görüntüleme seçenekleri. |
|

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


E-posta mesajları görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/) adresine bakın.


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


E-posta mesajları görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | E-posta mesajları görüntüleme seçenekleri. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


MS Outlook veri dosyaları görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/) adresine bakın.


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


MS Outlook veri dosyaları görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Ayarlanacak MS Outlook veri dosyaları görüntüleme seçenekleri. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


PDF belgeleri görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/) adresine bakın.


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


PDF belgeleri görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | PDF belgeleri görüntüleme seçenekleri. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Lotus Notes depolama veri dosyaları görüntüleme seçeneklerini alır.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Lotus Notes depolama veri dosyaları görüntüleme seçeneklerini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Lotus Notes depolama veri dosyaları görüntüleme seçenekleri. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Proje yönetimi dosyaları görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/) adresine bakın.


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Proje yönetimi dosyaları görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Ayarlanacak proje yönetimi dosyaları görüntüleme seçenekleri. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Elektronik tablo dosyaları görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), ve [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/) adreslerine bakın.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Elektronik tablo dosyaları görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), [Split a worksheet into pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), ve [Specify spreadsheet rendering options](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/) adreslerine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Elektronik tablo dosyaları görüntüleme seçenekleri. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Kelime işlem dosyaları görüntüleme seçenekleri.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/) adresine bakın.


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Kelime işlem dosyaları görüntüleme seçenekleri.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Word belgelerini işlemek için Word işleme seçenekleri. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Belgeleri görüntülerken Visio dosyalarını işlemek için render seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/) adresine bakın.


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Belgeleri görüntülerken Visio dosyalarını işlemek için render seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Visio dosyalarını işlemek için Visio işleme seçenekleri. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Sunum belgelerini işlemek için görüntüleme seçeneklerini alır.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/) adresine bakın.


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - sunum belgelerini işlemek için sunum görüntüleme seçenekleri.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Sunum belgelerini işlemek için görüntüleme seçeneklerini ayarlar.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Sunum belgelerini işlemek için sunum görüntüleme seçenekleri. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Çıktı HTML/PDF/PNG/JPEG'in görünümünü özelleştirmeye izin veren render seçeneklerini alır
Web belgeleri render edilirken.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-web-documents/) adresine bakın.


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - WebDocumentOptions nesnesi, işleme seçeneklerini özelleştirmek için.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Çıktı HTML/PDF/PNG/JPEG'in görünümünü özelleştirmeye izin veren render seçeneklerini ayarlar
Web belgeleri render edilirken.


Daha fazla bilgi ve kod örnekleri için, [documentation](../https://docs.groupdocs.com/viewer/java/render-web-documents/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | WebDocumentOptions nesnesi, renderleme seçeneklerini özelleştirmek için kullanılır. |
|

