---
title: Viewer
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Initialise la nouvelle instance deViewergroupdocs.viewer/viewer classe.
type: docs
weight: 10
url: /fr/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| getLoadOptions | Func`1 | Les méthodes qui renvoient les options de chargement de document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |
| ArgumentNullException | Jeté quand*getLoadOptions* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| getLoadOptions | Func`1 | Les méthodes qui renvoient les options de chargement de document. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*getFileStream* est nul. |
| ArgumentNullException | Jeté quand*getLoadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| leaveOpen | Boolean | vrai pour laisser le flux ouvert après la suppression de l'objet Viewer ; sinon,FAUX. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| loadOptions | LoadOptions | Les options de chargement des documents. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| loadOptions | LoadOptions | Les options de chargement des documents. |
| leaveOpen | Boolean | vrai pour laisser le flux ouvert après la suppression de l'objet Viewer ; sinon,FAUX. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |
| leaveOpen | Boolean | vrai pour laisser le flux ouvert après la suppression de l'objet Viewer ; sinon,FAUX. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| loadOptions | LoadOptions | Les options de chargement des documents. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Le flux de fichiers. |
| loadOptions | LoadOptions | Les options de chargement des documents. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |
| leaveOpen | Boolean | vrai pour laisser le flux ouvert après la suppression de l'objet Viewer ; sinon,FAUX. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*stream* est nul. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier à afficher. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*filePath* est nul ou vide. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier à afficher. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*filePath* est nul ou vide. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir également

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier à afficher. |
| loadOptions | LoadOptions | Les options utilisées pour ouvrir le fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*filePath* est nul ou vide. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initialise la nouvelle instance de[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Chemin d'accès au fichier à afficher. |
| loadOptions | LoadOptions | Les options utilisées pour ouvrir le fichier. |
| settings | ViewerSettings | Les paramètres de la visionneuse. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*filePath* est nul ou vide. |
| ArgumentNullException | Jeté quand*loadOptions* est nul. |
| ArgumentNullException | Jeté quand*settings* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les types de fichiers pris en charge par GroupDocs.Viewer : [Formats de documents pris en charge par GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* En savoir plus sur les fonctionnalités de GroupDocs.Viewer pour .NET : [Guide du développeur](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* En savoir plus sur le chargement de documents chiffrés et l'affichage de fichiers à partir de stockages tiers avec GroupDocs.Viewer pour .NET : [Comment charger et afficher un document avec GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir également

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
