---
title: "PdfViewOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

Initialise une instance de la classe [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createFileStream | CreateFileStream | La méthode qui instancie le flux utilisé pour écrire les données du fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createFileStream* est nul. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Voir aussi

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Initialise une instance de la classe [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createFileStream | CreateFileStream | La méthode qui instancie le flux utilisé pour écrire les données du fichier de sortie. |
| releaseFileStream | ReleaseFileStream | La méthode qui libère le flux créé par la méthode assignée au délégué passé au paramètre *createFileStream*. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *releaseFileStream* est nul. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Voir aussi

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Initialise une instance de la classe [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | La fabrique qui implémente les méthodes de création et de libération du flux de fichier de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileStreamFactory* est nul. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Voir aussi

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Initialise une instance de la classe [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions()
```

### Remarques

Ce constructeur initialise une instance de [`PdfViewOptions`](../../pdfviewoptions) avec "output.pdf" comme format de chemin de fichier pour le fichier de sortie. Le fichier de sortie sera placé dans le répertoire de travail actuel de l'application.

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Voir aussi

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Initialise une instance de la classe [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(string outputFilePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFilePath | String | Le chemin du fichier PDF de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *outputFilePath* est nul ou vide. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Voir aussi

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
