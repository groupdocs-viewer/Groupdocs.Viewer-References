---
title: "View"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Maakt een weergave van alle documentpagina's."
type: docs
weight: 90
url: /nl/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Maakt een weergave van alle documentpagina's.

```csharp
public void View(ViewOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | ViewOptions | De weergave-opties. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *options* null is. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegooid wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegooid wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wordt gegooid wanneer de bijlage niet gevonden kon worden. |

### Opmerkingen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Maakt een weergave van alle documentpagina's.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | ViewOptions | De weergave-opties. |
| cancellationToken | CancellationToken | Annuleringstoken om een verzoek te verzenden om het huidige weergaveproces te annuleren. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *options* null is. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegooid wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegooid wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wordt gegooid wanneer de bijlage niet gevonden kon worden. |

### Opmerkingen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Maakt een weergave van specifieke documentpagina's.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | ViewOptions | De weergave-opties. |
| pageNumbers | Int32[] | De paginanummers om te bekijken. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *options* null is. |
| ArgumentNullException | Wordt gegooid wanneer *pageNumbers* null is. |
| ArgumentException | Wordt gegooid wanneer *pageNumbers* leeg is. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegooid wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegooid wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wordt gegooid wanneer de bijlage niet gevonden kon worden. |

### Opmerkingen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Maakt een weergave van specifieke documentpagina's.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | ViewOptions | De weergave-opties. |
| pageNumbers | CancellationToken | De paginanummers om te bekijken. |
| cancellationToken | Int32[] | Annuleringstoken om de verwerking te annuleren. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *options* null is. |
| ArgumentNullException | Wordt gegooid wanneer *pageNumbers* null is. |
| ArgumentException | Wordt gegooid wanneer *pageNumbers* leeg is. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wordt gegooid wanneer een wachtwoord vereist is om het document te openen. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wordt gegooid wanneer het opgegeven wachtwoord onjuist is. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wordt gegooid wanneer de bijlage niet gevonden kon worden. |

### Opmerkingen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Zie ook

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
