---
title: "BaseViewOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Contient les options de rendu de base."
type: docs
weight: 12
url: /fr/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

Contient les options de rendu de base.


Le
BaseViewOptions
La classe sert de base aux options de rendu dans GroupDocs.Viewer.
Il vous permet de personnaliser le comportement de rendu des fichiers de sortie HTML, PDF, PNG et JPEG lors du rendu
des formats de documents spécifiques.


***Note:** For internal usage.*

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | Récupère les options de division des fichiers texte en pages. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | Définit les options de division des fichiers texte en pages. |
|
|  | [isRenderComments()](#isRenderComments--) | Active le rendu des commentaires. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | Active le rendu des commentaires. |
|
|  | [isRemoveComments()](#isRemoveComments--) | Désactive le rendu des commentaires lorsqu'il est réglé sur true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | Désactive le rendu des commentaires lorsqu'il est réglé sur true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | Active le rendu des notes. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | Active le rendu des notes. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | Active le rendu des pages cachées. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | Active le rendu des pages cachées. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | Récupère les options d'affichage des fichiers d'archive. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | Définit les options d'affichage des fichiers d'archive. |
|
|  | [getCadOptions()](#getCadOptions--) | Récupère les options d'affichage des dessins CAD. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | Définit les options d'affichage des dessins CAD. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | Récupère les options d'affichage des messages électroniques. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | Définit les options d'affichage des messages électroniques. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | Récupère les options d'affichage des fichiers de données MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | Définit les options d'affichage des fichiers de données MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | Récupère les options d'affichage des documents PDF. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | Récupère les options d'affichage des documents PDF. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | Récupère les options d'affichage des fichiers de données de stockage Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | Définit les options d'affichage des fichiers de données de stockage Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | Récupère les options d'affichage des fichiers de gestion de projet. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | Définit les options d'affichage des fichiers de gestion de projet. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Récupère les options d'affichage des fichiers de feuilles de calcul. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | Définit les options d'affichage des fichiers de feuilles de calcul. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | Les options d'affichage des fichiers de traitement de texte. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | Les options d'affichage des fichiers de traitement de texte. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | Récupère les options de rendu pour le traitement des fichiers Visio lors de la visualisation des documents. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | Définit les options de rendu pour le traitement des fichiers Visio lors de la visualisation des documents. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | Récupère les options d'affichage pour le traitement des documents de présentation. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | Définit les options d'affichage pour le traitement des documents de présentation. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | Obtient les options de rendu qui permettent la personnalisation de l'apparence du HTML/PDF/PNG/JPEG de sortie |
lors du rendu des documents Web.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | Définit les options de rendu qui permettent la personnalisation de l'apparence du HTML/PDF/PNG/JPEG de sortie |
lors du rendu des documents Web.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


Récupère les options de division des fichiers texte en pages.


Pour plus d'informations et des exemples de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


Définit les options de division des fichiers texte en pages.


Pour plus d'informations et des exemples de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | Les options de fractionnement des fichiers texte. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


Active le rendu des commentaires.


Par défaut, GroupDocs.Viewer ne rend pas les commentaires. Pour ce faire, définissez cette propriété sur true.
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
booléen -  true  si les commentaires doivent être rendus,  false  sinon.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


Active le rendu des commentaires.


Par défaut, GroupDocs.Viewer ne rend pas les commentaires. Pour ce faire, définissez cette propriété sur true.
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  si les commentaires doivent être rendus,  false  sinon. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


Désactive le rendu des commentaires lorsqu'il est réglé sur true. Par défaut, c'est false \\u2014 tous les commentaires sont affichés.


Certains formats de documents comme PDF et WordProcessing peuvent contenir des commentaires. Par défaut, GroupDocs.Viewer les rend. Avec cette option réglée sur true, les commentaires peuvent être exclus du document résultant.
Cette option remplace la propriété obsolète 'RenderComments'.


**Returns:**
booléen -  true  si les commentaires doivent être rendus,  false  sinon.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


Désactive le rendu des commentaires lorsqu'il est réglé sur true. Par défaut, c'est false \\u2014 tous les commentaires sont affichés.


Certains formats de documents comme PDF et WordProcessing peuvent contenir des commentaires. Par défaut, GroupDocs.Viewer les rend. Avec cette option réglée sur true, les commentaires peuvent être exclus du document résultant.
Cette option remplace la propriété obsolète 'RenderComments'.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  si les commentaires doivent être rendus,  false  sinon. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


Active le rendu des notes.


Certains fichiers, comme les présentations ou les fichiers Microsoft Project, peuvent contenir des notes. Par défaut, GroupDocs.Viewer ne rend pas les notes. Pour ce faire, définissez cette propriété sur true.
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
booléen -  true  si les notes doivent être rendues,  false  sinon.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


Active le rendu des notes.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  si les notes doivent être rendues,  false  sinon. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


Active le rendu des pages cachées.


Certains fichiers, comme les présentations ou les feuilles de calcul, peuvent contenir des pages cachées. Par défaut, GroupDocs.Viewer ne rend pas ces pages. Pour ce faire, définissez cette propriété sur true.
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
booléen -  true  si les pages cachées doivent être rendues,  false  sinon.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


Active le rendu des pages cachées.


Certains fichiers, comme les présentations ou les feuilles de calcul, peuvent contenir des pages cachées. Par défaut, GroupDocs.Viewer ne rend pas ces pages. Pour ce faire, définissez cette propriété sur true.
Pour un exemple de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | true  si les pages cachées doivent être rendues,  false  sinon. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable.


Utilisez cette propriété pour définir la police par défaut d'un document. GroupDocs.Viewer utilise cette police lors du rendu à la place de toute police non installée.
Pour des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - le nom de la police par défaut.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable.


Utilisez cette propriété pour définir la police par défaut d'un document. GroupDocs.Viewer utilise cette police lors du rendu à la place de toute police non installée.
Pour des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom de la police par défaut. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


Récupère les options d'affichage des fichiers d'archive.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


Définit les options d'affichage des fichiers d'archive.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | Les options d'affichage des fichiers d'archive. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


Récupère les options d'affichage des dessins CAD.


Pour plus d'informations et des exemples de code, voir le [Rendre les dessins et modèles CAD en HTML, PDF et fichiers image](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) et le [Spécifier les options de rendu pour les fichiers CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


Définit les options d'affichage des dessins CAD.


Pour plus d'informations et des exemples de code, voir le [Rendre les dessins et modèles CAD en HTML, PDF et fichiers image](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) et le [Spécifier les options de rendu pour les fichiers CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | Les options d'affichage des dessins CAD. |
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


Récupère les options d'affichage des messages électroniques.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


Définit les options d'affichage des messages électroniques.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | Les options d'affichage des messages électroniques. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


Récupère les options d'affichage des fichiers de données MS Outlook.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


Définit les options d'affichage des fichiers de données MS Outlook.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | Les options d'affichage des fichiers de données MS Outlook à définir. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Récupère les options d'affichage des documents PDF.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Récupère les options d'affichage des documents PDF.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | Les options d'affichage des documents PDF. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


Récupère les options d'affichage des fichiers de données de stockage Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


Définit les options d'affichage des fichiers de données de stockage Lotus Notes.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | Les options d'affichage des fichiers de données de stockage Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


Récupère les options d'affichage des fichiers de gestion de projet.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


Définit les options d'affichage des fichiers de gestion de projet.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | Les options d'affichage des fichiers de gestion de projet à définir. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


Récupère les options d'affichage des fichiers de feuilles de calcul.


Pour plus d'informations et des exemples de code, voir le [Rendre les feuilles de calcul Excel et Apple Numbers en HTML, PDF et fichiers image](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), le [Diviser une feuille de calcul en pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), et le [Spécifier les options de rendu des feuilles de calcul](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


Définit les options d'affichage des fichiers de feuilles de calcul.


Pour plus d'informations et des exemples de code, voir le [Rendre les feuilles de calcul Excel et Apple Numbers en HTML, PDF et fichiers image](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/), le [Diviser une feuille de calcul en pages](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/), et le [Spécifier les options de rendu des feuilles de calcul](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | Les options d'affichage des fichiers de feuilles de calcul. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


Les options d'affichage des fichiers de traitement de texte.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


Les options d'affichage des fichiers de traitement de texte.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | Les options de traitement de texte pour le rendu des documents Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


Récupère les options de rendu pour le traitement des fichiers Visio lors de la visualisation des documents.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


Définit les options de rendu pour le traitement des fichiers Visio lors de la visualisation des documents.


Pour plus d'informations et des exemples de code, voir la [documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | Les options de rendu Visio pour le traitement des fichiers Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


Récupère les options d'affichage pour le traitement des documents de présentation.


Pour plus d'informations et des exemples de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - les options d'affichage de présentation pour le traitement des documents de présentation.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


Définit les options d'affichage pour le traitement des documents de présentation.


Pour plus d'informations et des exemples de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | Les options d'affichage de présentation pour le traitement des documents de présentation. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


Obtient les options de rendu qui permettent la personnalisation de l'apparence du HTML/PDF/PNG/JPEG de sortie
lors du rendu des documents Web.


Pour plus d'informations et des exemples de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - L'objet WebDocumentOptions pour personnaliser les options de rendu.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


Définit les options de rendu qui permettent la personnalisation de l'apparence du HTML/PDF/PNG/JPEG de sortie
lors du rendu des documents Web.


Pour plus d'informations et des exemples de code, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | L'objet WebDocumentOptions pour personnaliser les options de rendu. |
|

