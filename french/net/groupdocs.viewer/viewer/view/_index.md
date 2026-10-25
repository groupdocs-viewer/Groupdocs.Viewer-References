---
title: "View"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Crée une vue de toutes les pages du document."
type: docs
weight: 90
url: /fr/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Crée une vue de toutes les pages du document.

```csharp
public void View(ViewOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ViewOptions | Les options de vue. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *options* est null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Levée lorsque la pièce jointe n'a pas pu être trouvée. |

### Remarques

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir aussi

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Crée une vue de toutes les pages du document.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ViewOptions | Les options de vue. |
| cancellationToken | CancellationToken | Jeton d'annulation pour envoyer une requête afin d'annuler le processus de vue actuel. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *options* est null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Levée lorsque la pièce jointe n'a pas pu être trouvée. |

### Remarques

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir aussi

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Crée une vue de pages spécifiques du document.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ViewOptions | Les options de vue. |
| pageNumbers | Int32[] | Les numéros de page à afficher. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *options* est null. |
| ArgumentNullException | Lancée lorsque *pageNumbers* est nul. |
| ArgumentException | Lancée lorsque *pageNumbers* est vide. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Levée lorsque la pièce jointe n'a pas pu être trouvée. |

### Remarques

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir aussi

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Crée une vue de pages spécifiques du document.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ViewOptions | Les options de vue. |
| pageNumbers | CancellationToken | Les numéros de page à afficher. |
| cancellationToken | Int32[] | Jeton d'annulation pour annuler le traitement. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *options* est null. |
| ArgumentNullException | Lancée lorsque *pageNumbers* est nul. |
| ArgumentException | Lancée lorsque *pageNumbers* est vide. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Levée lorsque la pièce jointe n'a pas pu être trouvée. |

### Remarques

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir aussi

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
