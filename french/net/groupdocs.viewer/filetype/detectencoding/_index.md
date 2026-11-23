---
title: "DetectEncoding"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Tentatives de détection de l'encodage des fichiers texte TXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv et CSVgroupdocs.viewer/filetype/csv par chemin."
type: docs
weight: 2060
url: /fr/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

Tentatives de détection de l'encodage des fichiers texte [`TXT`](../txt), [`TSV`](../tsv) et [`CSV`](../csv) par chemin.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le nom du fichier ou le chemin d'accès. |

### Valeur de retour

Encodage ou null lorsqu'il échoue à détecter l'encodage d'un fichier.

### Exemples

L'exemple montre comment détecter l'encodage d'un fichier texte.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### Voir aussi

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

Tentatives de détection de l'encodage du fichier texte [`TXT`](../txt), [`TSV`](../tsv) et [`CSV`](../csv) par flux.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |

### Valeur de retour

Encodage ou null lorsqu'il échoue à détecter l'encodage d'un fichier.

### Exemples

L'exemple montre comment détecter l'encodage d'un fichier texte.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### Voir aussi

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
