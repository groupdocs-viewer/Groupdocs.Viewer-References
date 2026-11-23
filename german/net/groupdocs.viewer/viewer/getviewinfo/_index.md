---
title: "GetViewInfo"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Gibt Informationen zur Ansicht und dokumentspezifische Informationen zurück."
type: docs
weight: 60
url: /de/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Gibt Informationen zur Ansicht und dokumentspezifische Informationen zurück.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | ViewInfoOptions | Die Optionen für die Ansichtsinformationen. |

### Rückgabewert

Informationen zur Ansicht und zu dokumentenspezifischen Informationen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *options* null ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |

### Bemerkungen

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Siehe auch

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Gibt Informationen zur Ansicht und dokumentspezifische Informationen zurück.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | ViewInfoOptions | Die Optionen für die Ansichtsinformationen. |
| cancellationToken | CancellationToken | Abbruch‑Token. |

### Rückgabewert

Informationen zur Ansicht und zu dokumentenspezifischen Informationen.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *options* null ist. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Wird ausgelöst, wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Wird ausgelöst, wenn das angegebene Passwort inkorrekt ist. |

### Bemerkungen

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Siehe auch

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
