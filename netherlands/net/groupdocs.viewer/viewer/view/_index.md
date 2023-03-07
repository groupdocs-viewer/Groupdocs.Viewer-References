---
title: View
second_title: GroupDocs.Viewer voor .NET API-referentie
description: Creëert weergave van alle documentpaginas.
type: docs
weight: 70
url: /nl/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Creëert weergave van alle documentpagina's.

```csharp
public void View(ViewOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | ViewOptions | De weergave-opties. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*options* is niets. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegenereerd wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegenereerd wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Gegooid wanneer bijlage niet kon worden gevonden. |

### Opmerkingen

**Kom meer te weten**

* Meer over verschillende weergaveopties volgens deze gids: [Uitvoer van documentweergave aanpassen met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Creëert weergave van alle documentpagina's.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | ViewOptions | De weergave-opties. |
| cancellationToken | CancellationToken | Annuleringstoken om een verzoek te verzenden om het huidige weergaveproces te annuleren. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*options* is niets. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegenereerd wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegenereerd wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Gegooid wanneer bijlage niet kon worden gevonden. |

### Opmerkingen

**Kom meer te weten**

* Meer over verschillende weergaveopties volgens deze gids: [Uitvoer van documentweergave aanpassen met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Creëert weergave van specifieke documentpagina's.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | ViewOptions | De weergave-opties. |
| pageNumbers | Int32[] | De paginanummers om te bekijken. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*options* is niets. |
| ArgumentNullException | Wanneer gegooid*pageNumbers* is niets. |
| ArgumentException | Wanneer gegooid*pageNumbers* is leeg. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegenereerd wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegenereerd wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Gegooid wanneer bijlage niet kon worden gevonden. |

### Opmerkingen

**Kom meer te weten**

* Meer over verschillende weergaveopties volgens deze gids: [Uitvoer van documentweergave aanpassen met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Creëert weergave van specifieke documentpagina's.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | ViewOptions | De weergave-opties. |
| pageNumbers | CancellationToken | De paginanummers om te bekijken. |
| cancellationToken | Int32[] | Annuleringstoken om de verwerking te annuleren. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*options* is niets. |
| ArgumentNullException | Wanneer gegooid*pageNumbers* is niets. |
| ArgumentException | Wanneer gegooid*pageNumbers* is leeg. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegenereerd wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegenereerd wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Gegooid wanneer bijlage niet kon worden gevonden. |

### Opmerkingen

**Kom meer te weten**

* Meer over verschillende weergaveopties volgens deze gids: [Uitvoer van documentweergave aanpassen met GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* naamruimte [GroupDocs.Viewer](../../viewer)
* montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
