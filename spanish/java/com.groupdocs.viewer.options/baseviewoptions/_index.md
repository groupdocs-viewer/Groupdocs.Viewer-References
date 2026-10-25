---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Contiene las opciones básicas de renderizado."
type: docs
weight: 12
url: /es/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Contiene las opciones básicas de renderizado.


El
BaseViewOptions
La clase sirve como la base para las opciones de renderizado en GroupDocs.Viewer.
Permite personalizar el comportamiento de renderizado de los archivos de salida HTML, PDF, PNG y JPEG al renderizar
formatos de documento específicos.


***Note:** For internal usage.*

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Recupera las opciones para dividir archivos de texto en páginas. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Establece las opciones para dividir archivos de texto en páginas. |
|
|  | [isRenderComments()](#isRenderComments--) | Habilita la renderización de comentarios. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Habilita la renderización de comentarios. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Deshabilita la renderización de comentarios cuando se establece en true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Deshabilita la renderización de comentarios cuando se establece en true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Habilita la renderización de notas. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Habilita la renderización de notas. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Habilita la renderización de páginas ocultas. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Habilita la renderización de páginas ocultas. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Fuente predeterminada que se utilizará cuando no se pueda encontrar una fuente particular usada en el documento. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Fuente predeterminada que se utilizará cuando no se pueda encontrar una fuente particular usada en el documento. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Recupera las opciones de vista de archivos de archivo. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Establece las opciones de vista de archivos de archivo. |
|
|  | [getCadOptions()](#getCadOptions--) | Recupera las opciones de vista de dibujos CAD. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Establece las opciones de vista de dibujos CAD. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Recupera las opciones de vista de mensajes de correo electrónico. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Establece las opciones de vista de mensajes de correo electrónico. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Recupera las opciones de vista de archivos de datos de MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Establece las opciones de vista de archivos de datos de MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Recupera las opciones de vista de documentos PDF. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Recupera las opciones de vista de documentos PDF. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Recupera las opciones de vista de archivos de datos de almacenamiento de Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Establece las opciones de vista de archivos de datos de almacenamiento de Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Recupera las opciones de vista de archivos de gestión de proyectos. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Establece las opciones de vista de archivos de gestión de proyectos. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Recupera las opciones de vista de los archivos de hoja de cálculo. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Establece las opciones de vista de los archivos de hoja de cálculo. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Las opciones de vista de los archivos de procesamiento de Word. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Las opciones de vista de los archivos de procesamiento de Word. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Recupera las opciones de renderizado para procesar archivos Visio al visualizar documentos. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Establece las opciones de renderizado para procesar archivos Visio al visualizar documentos. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Recupera las opciones de vista para procesar documentos de presentación. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Establece las opciones de vista para procesar documentos de presentación. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Obtiene las opciones de renderizado que permiten personalizar la apariencia del HTML/PDF/PNG/JPEG de salida |
al renderizar documentos web.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Establece las opciones de renderizado que permiten personalizar la apariencia del HTML/PDF/PNG/JPEG de salida |
al renderizar documentos web.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Recupera las opciones para dividir archivos de texto en páginas.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Establece las opciones para dividir archivos de texto en páginas.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Las opciones de división de archivos de texto. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Habilita la renderización de comentarios.


De forma predeterminada, GroupDocs.Viewer no renderiza comentarios. Para hacerlo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
boolean -  true  si los comentarios deben renderizarse,  false  en caso contrario.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Habilita la renderización de comentarios.


De forma predeterminada, GroupDocs.Viewer no renderiza comentarios. Para hacerlo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  si los comentarios deben renderizarse,  false  en caso contrario. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Desactiva la renderización de comentarios cuando se establece en true. De forma predeterminada es false \\u2014 se muestran todos los comentarios.


Algunos formatos de documento como PDF y WordProcessing pueden contener comentarios. De forma predeterminada, GroupDocs.Viewer los renderiza. Con esta opción establecida en true, los comentarios pueden excluirse del documento resultante.
Esta opción reemplaza la propiedad obsoleta 'RenderComments'.


**Returns:**
boolean -  true  si los comentarios deben renderizarse,  false  en caso contrario.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Desactiva la renderización de comentarios cuando se establece en true. De forma predeterminada es false \\u2014 se muestran todos los comentarios.


Algunos formatos de documento como PDF y WordProcessing pueden contener comentarios. De forma predeterminada, GroupDocs.Viewer los renderiza. Con esta opción establecida en true, los comentarios pueden excluirse del documento resultante.
Esta opción reemplaza la propiedad obsoleta 'RenderComments'.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  si los comentarios deben renderizarse,  false  en caso contrario. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Habilita la renderización de notas.


Algunos archivos, como presentaciones o archivos de Microsoft Project, pueden contener notas. De forma predeterminada, GroupDocs.Viewer no renderiza notas. Para hacerlo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
boolean -  true  si las notas deben renderizarse,  false  en caso contrario.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Habilita la renderización de notas.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  si las notas deben renderizarse,  false  en caso contrario. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Habilita la renderización de páginas ocultas.


Algunos archivos, como presentaciones o hojas de cálculo, pueden contener páginas ocultas. De forma predeterminada, GroupDocs.Viewer no renderiza estas páginas. Para hacerlo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
boolean -  true  si las páginas ocultas deben renderizarse,  false  en caso contrario.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Habilita la renderización de páginas ocultas.


Algunos archivos, como presentaciones o hojas de cálculo, pueden contener páginas ocultas. De forma predeterminada, GroupDocs.Viewer no renderiza estas páginas. Para hacerlo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  si las páginas ocultas deben renderizarse,  false  en caso contrario. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Fuente predeterminada que se utilizará cuando no se pueda encontrar una fuente particular usada en el documento.


Utilice esta propiedad para establecer la fuente predeterminada para un documento. GroupDocs.Viewer usa esta fuente durante el renderizado en lugar de cualquier fuente no instalada.
Para ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - el nombre de la fuente predeterminada.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Fuente predeterminada que se utilizará cuando no se pueda encontrar una fuente particular usada en el documento.


Utilice esta propiedad para establecer la fuente predeterminada para un documento. GroupDocs.Viewer usa esta fuente durante el renderizado en lugar de cualquier fuente no instalada.
Para ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de la fuente predeterminada. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Recupera las opciones de vista de archivos de archivo.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Establece las opciones de vista de archivos de archivo.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Las opciones de visualización de archivos de archivo. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Recupera las opciones de vista de dibujos CAD.


Para obtener más información y ejemplos de código, consulte el [Renderizar dibujos CAD y modelos como archivos HTML, PDF e imágenes](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) y el [Especificar opciones de renderizado para archivos CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Establece las opciones de vista de dibujos CAD.


Para obtener más información y ejemplos de código, consulte el [Renderizar dibujos CAD y modelos como archivos HTML, PDF e imágenes](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) y el [Especificar opciones de renderizado para archivos CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Las opciones de vista de dibujo CAD. |
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


Recupera las opciones de vista de mensajes de correo electrónico.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Establece las opciones de vista de mensajes de correo electrónico.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Opciones de vista de mensajes de correo electrónico. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Recupera las opciones de vista de archivos de datos de MS Outlook.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Establece las opciones de vista de archivos de datos de MS Outlook.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Las opciones de vista de archivos de datos de MS Outlook a configurar. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Recupera las opciones de vista de documentos PDF.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Recupera las opciones de vista de documentos PDF.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Las opciones de vista de documentos PDF. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Recupera las opciones de vista de archivos de datos de almacenamiento de Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Establece las opciones de vista de archivos de datos de almacenamiento de Lotus Notes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Las opciones de vista de archivos de datos de almacenamiento de Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Recupera las opciones de vista de archivos de gestión de proyectos.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Establece las opciones de vista de archivos de gestión de proyectos.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Las opciones de vista de archivos de gestión de proyectos a establecer. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Recupera las opciones de vista de los archivos de hoja de cálculo.


Para obtener más información y ejemplos de código, consulte el [Renderizar hojas de cálculo de Excel y Apple Numbers como archivos HTML, PDF e imágenes](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), el [Dividir una hoja de cálculo en páginas](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), y el [Especificar opciones de renderizado de hojas de cálculo](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Establece las opciones de vista de los archivos de hoja de cálculo.


Para obtener más información y ejemplos de código, consulte el [Renderizar hojas de cálculo de Excel y Apple Numbers como archivos HTML, PDF e imágenes](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), el [Dividir una hoja de cálculo en páginas](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), y el [Especificar opciones de renderizado de hojas de cálculo](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Las opciones de vista de archivos de hoja de cálculo. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Las opciones de vista de los archivos de procesamiento de Word.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Las opciones de vista de los archivos de procesamiento de Word.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Las opciones de procesamiento de Word para renderizar documentos Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Recupera las opciones de renderizado para procesar archivos Visio al visualizar documentos.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Establece las opciones de renderizado para procesar archivos Visio al visualizar documentos.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Las opciones de renderizado de Visio para procesar archivos Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Recupera las opciones de vista para procesar documentos de presentación.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - las opciones de vista de presentación para procesar documentos de presentación.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Establece las opciones de vista para procesar documentos de presentación.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Las opciones de vista de presentación para procesar documentos de presentación. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Obtiene las opciones de renderizado que permiten personalizar la apariencia del HTML/PDF/PNG/JPEG de salida
al renderizar documentos web.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - El objeto WebDocumentOptions para personalizar las opciones de renderizado.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Establece las opciones de renderizado que permiten personalizar la apariencia del HTML/PDF/PNG/JPEG de salida
al renderizar documentos web.


Para obtener más información y ejemplos de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | El objeto WebDocumentOptions para personalizar las opciones de renderizado. |
|

