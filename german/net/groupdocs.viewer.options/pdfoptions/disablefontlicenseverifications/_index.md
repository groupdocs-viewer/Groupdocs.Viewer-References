---
title: "DisableFontLicenseVerifications"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Deaktiviert alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument."
type: docs
weight: 40
url: /de/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

Deaktiviert alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### Bemerkungen

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn sie durch die Lizenz dieser Schriftart verboten sind. Zum Beispiel kann manche Schriftart nicht in ein PDF‑Dokument eingebettet werden, wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Diese Option ermöglicht es, die Überprüfung dieser Regeln zu überspringen.

Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑/Gesetzesverstöße selbst übernimmt. Sie handelt also auf eigenes Risiko. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie kein Urheberrecht verletzen. Der Standardwert ist `false`.

Für ein Code‑Beispiel siehe die [Dokumentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### Siehe auch

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
