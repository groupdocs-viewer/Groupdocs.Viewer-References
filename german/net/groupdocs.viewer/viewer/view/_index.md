---
title: View
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Erstellt eine Ansicht aller Dokumentseiten.
type: docs
weight: 70
url: /de/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Erstellt eine Ansicht aller Dokumentseiten.

```csharp
public void View(ViewOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*options* ist Null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn zum Öffnen des Dokuments ein Kennwort erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Kennwort falsch ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn kein Anhang gefunden werden konnte. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu verschiedenen Anzeigeoptionen finden Sie in dieser Anleitung: [So passen Sie die Dokumentanzeigeausgabe mit GroupDocs.Viewer an](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Erstellt eine Ansicht aller Dokumentseiten.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtsoptionen. |
| cancellationToken | CancellationToken | Abbruchtoken zum Senden einer Anforderung zum Abbrechen des aktuellen Ansichtsprozesses. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*options* ist Null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn zum Öffnen des Dokuments ein Kennwort erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Kennwort falsch ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn kein Anhang gefunden werden konnte. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu verschiedenen Anzeigeoptionen finden Sie in dieser Anleitung: [So passen Sie die Dokumentanzeigeausgabe mit GroupDocs.Viewer an](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Erstellt eine Ansicht bestimmter Dokumentseiten.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtsoptionen. |
| pageNumbers | Int32[] | Die anzuzeigenden Seitenzahlen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*options* ist Null. |
| ArgumentNullException | Wann geworfen*pageNumbers* ist Null. |
| ArgumentException | Wann geworfen*pageNumbers* ist leer. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn zum Öffnen des Dokuments ein Kennwort erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Kennwort falsch ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn kein Anhang gefunden werden konnte. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu verschiedenen Anzeigeoptionen finden Sie in dieser Anleitung: [So passen Sie die Dokumentanzeigeausgabe mit GroupDocs.Viewer an](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Erstellt eine Ansicht bestimmter Dokumentseiten.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | ViewOptions | Die Ansichtsoptionen. |
| pageNumbers | CancellationToken | Die anzuzeigenden Seitenzahlen. |
| cancellationToken | Int32[] | Abbruch-Token zum Abbrechen der Verarbeitung. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*options* ist Null. |
| ArgumentNullException | Wann geworfen*pageNumbers* ist Null. |
| ArgumentException | Wann geworfen*pageNumbers* ist leer. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn zum Öffnen des Dokuments ein Kennwort erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Kennwort falsch ist. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Wird ausgelöst, wenn kein Anhang gefunden werden konnte. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu verschiedenen Anzeigeoptionen finden Sie in dieser Anleitung: [So passen Sie die Dokumentanzeigeausgabe mit GroupDocs.Viewer an](https://docs.groupdocs.com/display/viewernet/Viewing)

### Siehe auch

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namensraum [GroupDocs.Viewer](../../viewer)
* Montage [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
