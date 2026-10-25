---
title: "Viewer"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt die Hauptklasse dar, die den Dokument-Renderprozess steuert."
type: docs
weight: 50
url: /de/net/groupdocs.viewer/viewer/
---

## Viewer class

Stellt die Hauptklasse dar, die den Dokument-Renderprozess steuert.

```csharp
public class Viewer : IDisposable
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Initialisiert eine neue Instanz der Klasse [`Viewer`](../viewer). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Gibt den Dateistream und verwaltete interne Ressourcen frei. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Gibt alle Schriftarten zurück, die in den geladenen Dokumenten verwendet werden, einschließlich derjenigen, die im Dokument selbst eingebettet sind, sowie der Systemschriftarten, die im Betriebssystem installiert und im Dokument verwendet werden. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Gibt die im Dokument enthaltenen Anhänge zurück. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Gibt die im Dokument enthaltenen Anhänge zurück. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Gibt Informationen über die Datei zurück, wie Dateityp und ein Flag, das angibt, ob die Datei verschlüsselt ist. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Gibt Informationen zur Ansicht und dokumentspezifische Informationen zurück. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Gibt Informationen zur Ansicht und dokumentspezifische Informationen zurück. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Speichert die Anhangsdatei in den *Ziel*-Stream. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Speichert die Anhangsdatei in den *Ziel*-Stream. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Führt eine Textsuche durch und hebt das Ergebnis (falls gefunden) im geladenen Dokument gemäß den geladenen Optionen hervor. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Erstellt eine Ansicht aller Dokumentseiten. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Erstellt eine Ansicht aller Dokumentseiten. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Erstellt eine Ansicht bestimmter Dokumentseiten. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Erstellt eine Ansicht bestimmter Dokumentseiten. |

### Siehe auch

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
