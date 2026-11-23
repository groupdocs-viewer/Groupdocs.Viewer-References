---
title: "ForEmbeddedResources"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions pour le rendu en HTML avec des ressources intégrées."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |

### Valeur de retour

Nouvelle instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| releasePageStream | ReleasePageStream | La méthode qui libère le flux créé par la méthode assignée au délégué passé au paramètre *createPageStream*. |

### Valeur de retour

Nouvelle instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |
| ArgumentNullException | Lancée lorsque *releasePageStream* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |

### Valeur de retour

Nouvelle instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *pageStreamFactory* est nul. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Voir aussi

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Voir aussi

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'page_{0}.html'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePathFormat* est nul ou vide. |

### Remarques

Pour l'exemple de code, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Voir aussi

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
