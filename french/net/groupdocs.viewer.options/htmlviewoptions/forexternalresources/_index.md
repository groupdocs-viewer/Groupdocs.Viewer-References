---
title: ForExternalResources
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Initialise la nouvelle instance deHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions classe pour le rendu en HTML avec des ressources externes.
type: docs
weight: 20
url: /fr/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initialise la nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| createResourceStream | CreateResourceStream | La méthode qui libère le flux créé par*createPageStream* méthode. |
| createResourceUrl | CreateResourceUrl | La méthode qui crée l'URL pour la ressource HTML. |

### Return_Value

Nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*createPageStream* est nul. |
| ArgumentNullException | Jeté quand*createResourceStream* est nul. |
| ArgumentNullException | Jeté quand*createResourceUrl* est nul. |

### Voir également

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* espace de noms [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Assemblée [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initialise la nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| createPageStream | CreatePageStream | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| createResourceStream | CreateResourceStream | La méthode qui instancie le flux utilisé pour écrire les données de ressource HTML de sortie. |
| createResourceUrl | CreateResourceUrl | La méthode qui crée l'URL pour la ressource HTML. |
| releasePageStream | ReleasePageStream | La méthode qui libère le flux créé par la méthode affectée au délégué qui est passé à*createPageStream* paramètre. |
| releaseResourceStream | ReleaseResourceStream | La méthode qui libère le flux créé par la méthode affectée au délégué qui est passé à*createResourceStream* paramètre. |

### Return_Value

Nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*createPageStream* est nul. |
| ArgumentNullException | Jeté quand*createResourceStream* est nul. |
| ArgumentNullException | Jeté quand*createResourceUrl* est nul. |
| ArgumentNullException | Jeté quand*releasePageStream* est nul. |
| ArgumentNullException | Jeté quand*releaseResourceStream* est nul. |

### Voir également

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* espace de noms [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Assemblée [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Initialise la nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fabrique qui implémente les méthodes de création et de publication du flux de page de sortie. |
| resourceStreamFactory | IResourceStreamFactory | La fabrique qui implémente les méthodes nécessaires à la création d'une URL de ressource, à l'instanciation et à la publication du flux de ressources HTML de sortie. |

### Return_Value

Nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*pageStreamFactory* est nul. |
| ArgumentNullException | Jeté quand*resourceStreamFactory* est nul. |

### Voir également

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* espace de noms [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Assemblée [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initialise la nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Remarques

Ce constructeur initialise une nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) - avec "p_{0}.html" comme format de chemin de fichier pour les fichiers HTML de sortie ; - avec "p_{0}_{1}" comme format de chemin de fichier pour les fichiers de ressources HTML de sortie ; - avec " p_{0}_{1}" comme format d'URL pour les ressources HTML ; Les fichiers de sortie seront placés dans le répertoire de travail actuel de l'application.

### Voir également

* class [HtmlViewOptions](../../htmlviewoptions)
* espace de noms [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Assemblée [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initialise la nouvelle instance de[`HtmlViewOptions`](../../htmlviewoptions) classe.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePathFormat | String | Le format du chemin du fichier, par exemple 'page_{0}.html'. |
| resourceFilePathFormat | String | Le format du chemin du fichier de ressources, par exemple 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Le format de l'URL de la ressource, par exemple 'page_{0}/resource_{1}'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*filePathFormat* est nul ou vide. |
| ArgumentException | Jeté quand*resourceFilePathFormat* est nul ou vide. |
| ArgumentException | Jeté quand*resourceUrlFormat* est nul ou vide. |

### Voir également

* class [HtmlViewOptions](../../htmlviewoptions)
* espace de noms [GroupDocs.Viewer.Options](../../htmlviewoptions)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
