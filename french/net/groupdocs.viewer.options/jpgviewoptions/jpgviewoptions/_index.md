---
title: "JpgViewOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

Initialise une instance de la classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui crée un flux utilisé pour écrire les données de page de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Initialise une instance de la classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

Initialise une instance de la classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *pageStreamFactory* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Voir aussi

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

Initialise une instance de la classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions()
```

### Remarques

Ce constructeur initialise une instance de [`JpgViewOptions`](../../jpgviewoptions) avec "p_{0}.jpg" comme format de chemin de fichier pour les fichiers de sortie. Les fichiers de sortie sont placés dans le répertoire de travail actuel de l'application.

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Voir aussi

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

Initialise une instance de la classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(string filePathFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'page_{0}.jpg'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePathFormat* est nul ou vide. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Voir aussi

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
