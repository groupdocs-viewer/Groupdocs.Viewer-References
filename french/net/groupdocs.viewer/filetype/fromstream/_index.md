---
title: "FromStream"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Détecte le type de fichier en lisant la signature du fichier."
type: docs
weight: 2000
url: /fr/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

Détecte le type de fichier en lisant la signature du fichier.

```csharp
public static FileType FromStream(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |

### Voir aussi

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

Détecte le type de fichier en lisant la signature du fichier.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| password | String | Le mot de passe pour ouvrir le fichier. |

### Voir aussi

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

Détecte le type de fichier en lisant la signature du fichier.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| logger | ILogger | Le logger. |

### Valeur de retour

Renvoie le type de fichier s'il a été détecté avec succès, sinon renvoie le type de fichier par défaut [`Unknown`](../unknown).

### Voir aussi

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

Détecte le type de fichier en lisant la signature du fichier.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| password | String | Le mot de passe pour ouvrir le fichier. |
| logger | ILogger | Le logger. |

### Valeur de retour

Renvoie le type de fichier s'il a été détecté avec succès, sinon renvoie le type de fichier par défaut [`Unknown`](../unknown).

### Voir aussi

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
