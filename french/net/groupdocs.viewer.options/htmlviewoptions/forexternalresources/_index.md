---
title: "ForExternalResources"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions pour le rendu en HTML avec des ressources externes."
type: docs
weight: 20
url: /fr/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources externes.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| createResourceStream | CreateResourceStream | La méthode qui libère le flux créé par la méthode *createPageStream*. |
| createResourceUrl | CreateResourceUrl | La méthode qui crée l'URL pour la ressource HTML. |

### Valeur de retour

Nouvelle instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources externes.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |
| ArgumentNullException | Lancée lorsque *createResourceStream* est nul. |
| ArgumentNullException | Lancée lorsque *createResourceUrl* est nul. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources externes.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| createResourceStream | CreateResourceStream | La méthode qui instancie le flux utilisé pour écrire les données de la ressource HTML de sortie. |
| createResourceUrl | CreateResourceUrl | La méthode qui crée l'URL pour la ressource HTML. |
| releasePageStream | ReleasePageStream | La méthode qui libère le flux créé par la méthode assignée au délégué passé au paramètre *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | La méthode qui libère le flux créé par la méthode assignée au délégué passé au paramètre *createResourceStream*. |

### Valeur de retour

Nouvelle instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources externes.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *createPageStream* est nul. |
| ArgumentNullException | Lancée lorsque *createResourceStream* est nul. |
| ArgumentNullException | Lancée lorsque *createResourceUrl* est nul. |
| ArgumentNullException | Lancée lorsque *releasePageStream* est nul. |
| ArgumentNullException | Lancée lorsque *releaseResourceStream* est nul. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources externes.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |
| resourceStreamFactory | IResourceStreamFactory | La fabrique qui implémente les méthodes requises pour créer l'URL de la ressource, instancier et libérer le flux de ressource HTML de sortie. |

### Valeur de retour

Nouvelle instance de la classe [`HtmlViewOptions`](../../htmlviewoptions) pour le rendu en HTML avec des ressources externes.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *pageStreamFactory* est nul. |
| ArgumentNullException | Lancée lorsque *resourceStreamFactory* est nul. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Voir aussi

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Remarques

Ce constructeur initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Les fichiers de sortie seront placés dans le répertoire de travail actuel de l'application.

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Voir aussi

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initialise une instance de la classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin de fichier, par ex. 'page_{0}.html'. |
| resourceFilePathFormat | String | Le format du chemin du fichier de ressource, par ex. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Le format de l'URL de la ressource, par ex. 'page_{0}/resource_{1}'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePathFormat* est nul ou vide. |
| ArgumentException | Lancée lorsque *resourceFilePathFormat* est nul ou vide. |
| ArgumentException | Lancée lorsque *resourceUrlFormat* est nul ou vide. |

### Remarques

Pour l'exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Voir aussi

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
