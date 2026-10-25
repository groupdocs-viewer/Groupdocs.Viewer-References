---
title: "Ansicht"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Erstellt eine Ansicht aller Dokumentseiten."
type: docs
weight: 90
url: /de/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Erstellt eine Ansicht aller Dokumentseiten.

```csharp
public void View(ViewOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *options* null ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn der Anhang nicht gefunden werden konnte. |

### Bemerkungen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Erstellt eine Ansicht aller Dokumentseiten.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtoptionen. |
| cancellationToken | CancellationToken | Abbruch-Token, um eine Anforderung zum Abbrechen des aktuellen Ansichtsvorgangs zu senden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *options* null ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn der Anhang nicht gefunden werden konnte. |

### Bemerkungen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Erstellt eine Ansicht bestimmter Dokumentseiten.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtoptionen. |
| Seitenzahlen | Int32[] | Die Seitenzahlen, die angezeigt werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *options* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *pageNumbers* null ist. |
| ArgumentException | Wird ausgelöst, wenn *pageNumbers* leer ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn der Anhang nicht gefunden werden konnte. |

### Bemerkungen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Erstellt eine Ansicht bestimmter Dokumentseiten.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtoptionen. |
| Seitenzahlen | CancellationToken | Die Seitenzahlen, die angezeigt werden sollen. |
| cancellationToken | Int32[] | Abbruch-Token, um die Verarbeitung abzubrechen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *options* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *pageNumbers* null ist. |
| ArgumentException | Wird ausgelöst, wenn *pageNumbers* leer ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn der Anhang nicht gefunden werden konnte. |

### Bemerkungen

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
