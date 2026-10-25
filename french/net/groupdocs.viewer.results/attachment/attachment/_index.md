---
title: "Attachment"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe Attachmentgroupdocs.viewer.results/attachment."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

Initialise une nouvelle instance de la classe [`Attachment`](../../attachment).

```csharp
public Attachment()
```

### Voir aussi

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

Initialise une nouvelle instance de la classe [`Attachment`](../../attachment).

```csharp
public Attachment(string fileName, string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Nom de fichier de la pièce jointe. |
| filePath | String | Chemin relatif de la pièce jointe, par ex. dossier/fichier.docx ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message électronique ou un fichier de données. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *fileName* est nul ou vide. |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |

### Voir aussi

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

Initialise une nouvelle instance de la classe [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| id | String | Identifiant unique (dans le contexte d'un seul fichier) de la pièce jointe. |
| fileName | String | Nom de fichier de la pièce jointe. |
| filePath | String | Chemin relatif de la pièce jointe, par ex. dossier/fichier.docx ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message électronique ou un fichier de données. |
| taille | Int64 | Taille du fichier de la pièce jointe en octets. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *id* est nul ou vide. |
| ArgumentException | Lancée lorsque *fileName* est nul ou vide. |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |

### Voir aussi

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

Initialise une nouvelle instance de la classe [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| id | String | Identifiant unique (dans le contexte d'un seul fichier) de la pièce jointe. |
| fileName | String | Nom de fichier de la pièce jointe. |
| filePath | String | Chemin relatif de la pièce jointe, par ex. dossier/fichier.docx ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message électronique ou un fichier de données. |
| fileType | FileType | Type de fichier de la pièce jointe. |
| taille | Int64 | Taille du fichier de la pièce jointe en octets. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *id* est nul ou vide. |
| ArgumentException | Lancée lorsque *fileName* est nul ou vide. |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
