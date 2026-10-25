---
title: "PngViewOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe PngViewOptionsgroupdocs.viewer.options/pngviewoptions."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

Initialise une instance de la classe [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui crée un flux utilisé pour écrire les données de page de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Initialise une instance de la classe [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui crée un flux utilisé pour écrire les données de page de sortie. |
| releasePageStream | ReleasePageStream | La méthode qui libère un flux créé par la méthode assignée au délégué passé au paramètre *createPageStream*. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |
| ArgumentNullException | Lancée lorsque *releasePageStream* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Initialise une instance de la classe [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *pageStreamFactory* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Voir aussi

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Initialise une instance de la classe [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions()
```

### Remarques

Ce constructeur initialise une instance de [`PngViewOptions`](../../pngviewoptions) avec "p_{0}.png" comme format de chemin de fichier pour les fichiers de sortie. Les fichiers de sortie sont placés dans le répertoire de travail actuel de l'application.

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Voir aussi

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Initialise une instance de la classe [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(string filePathFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'page_{0}.png'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePathFormat* est nul ou vide. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### Voir aussi

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
