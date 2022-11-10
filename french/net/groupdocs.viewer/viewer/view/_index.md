---
title: View
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Crée une vue de toutes les pages du document.
type: docs
weight: 70
url: /fr/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Crée une vue de toutes les pages du document.

```csharp
public void View(ViewOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | ViewOptions | Les options d'affichage. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*options* est nul. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Levée lorsqu'un mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Levé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lancé lorsque la pièce jointe est introuvable. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les différentes options d'affichage en suivant ce guide : [Comment personnaliser la sortie de visualisation de documents à l'aide de GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir également

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Crée une vue de toutes les pages du document.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | ViewOptions | Les options d'affichage. |
| cancellationToken | CancellationToken | Jeton d'annulation pour envoyer une demande d'annulation du processus d'affichage en cours. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*options* est nul. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Levée lorsqu'un mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Levé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lancé lorsque la pièce jointe est introuvable. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les différentes options d'affichage en suivant ce guide : [Comment personnaliser la sortie de visualisation de documents à l'aide de GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir également

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Crée une vue de pages de document spécifiques.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | ViewOptions | Les options d'affichage. |
| pageNumbers | Int32[] | Les numéros de page à afficher. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*options* est nul. |
| ArgumentNullException | Jeté quand*pageNumbers* est nul. |
| ArgumentException | Jeté quand*pageNumbers* est vide. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Levée lorsqu'un mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Levé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lancé lorsque la pièce jointe est introuvable. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les différentes options d'affichage en suivant ce guide : [Comment personnaliser la sortie de visualisation de documents à l'aide de GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir également

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Crée une vue de pages de document spécifiques.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| options | ViewOptions | Les options d'affichage. |
| pageNumbers | CancellationToken | Les numéros de page à afficher. |
| cancellationToken | Int32[] | Jeton d'annulation pour annuler le traitement. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*options* est nul. |
| ArgumentNullException | Jeté quand*pageNumbers* est nul. |
| ArgumentException | Jeté quand*pageNumbers* est vide. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Levée lorsqu'un mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Levé lorsque le mot de passe spécifié est incorrect. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lancé lorsque la pièce jointe est introuvable. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les différentes options d'affichage en suivant ce guide : [Comment personnaliser la sortie de visualisation de documents à l'aide de GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Voir également

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espace de noms [GroupDocs.Viewer](../../viewer)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
