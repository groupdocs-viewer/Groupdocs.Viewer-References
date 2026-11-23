---
title: "disable_font_license_verifications Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft deaktiviert alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

Die Eigenschaft deaktiviert alle Lizenzbeschränkungen für alle Schriftarten im aktuellen XPS/OXPS-Dokument.

Viele Vorgänge mit Schriftarten können nicht ausgeführt werden, wenn sie durch die Lizenz der Schriftart verboten sind. Beispielsweise können einige Schriftarten nicht in ein PDF-Dokument eingebettet werden, wenn Lizenzregeln das Einbetten für diese Schriftart deaktivieren. Diese Option ermöglicht es Ihnen, die Überprüfung dieser Regeln zu überspringen.

Seien Sie vorsichtig bei der Verwendung dieses Flags. Wenn es gesetzt ist, bedeutet das, dass die Person, die dieses Flag setzt, die gesamte Verantwortung für mögliche Lizenz‑ oder Rechtsverstöße übernimmt. Es wird dringend empfohlen, dieses Flag nur zu verwenden, wenn Sie sich absolut sicher sind, dass Sie kein Urheberrecht verletzen. Der Standardwert ist `False`.

Für ein Code‑Beispiel siehe die Dokumentation unter https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Siehe auch
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
