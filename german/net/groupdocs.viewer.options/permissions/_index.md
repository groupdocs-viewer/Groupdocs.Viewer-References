---
title: "Berechtigungen"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Definiert die Berechtigungen für PDF-Dokumente."
type: docs
weight: 430
url: /de/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

Definiert die Berechtigungen für PDF-Dokumente.

```csharp
[Flags]
public enum Permissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AllowAll | `0` | Erlaubt das Drucken, Ändern und Extrahieren von Daten. |
| DenyPrinting | `1` | Drucken verweigern. |
| DenyModification | `2` | Verweigert die Inhaltsänderung, das Ausfüllen von Formularen, das Hinzufügen oder Ändern von Anmerkungen. |
| DenyDataExtraction | `4` | Verweigert das Extrahieren von Text und Grafiken. |
| DenyAll | `7` | Verweigert das Drucken, die Inhaltsänderung und das Extrahieren von Daten. |

### Siehe auch

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
