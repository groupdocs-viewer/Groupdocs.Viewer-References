---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von Präsentationsoptionen."
type: docs
weight: 26
url: /de/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Bietet Optionen zum Rendern von Präsentationsoptionen.

Weitere Details finden Sie in der [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Aktiviert einen neuen HTML‑Rendermodus für Präsentationsdokumente. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Aktiviert einen neuen HTML‑Rendermodus für Präsentationsdokumente. |
| [getResolution()](#getResolution--) | Auflösung für Bilder innerhalb der Präsentation (nur für die HTML/PDF‑Renderung). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Auflösung für Bilder innerhalb der Präsentation (nur für die HTML/PDF‑Renderung). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Aktiviert einen neuen HTML‑Rendermodus für Präsentationsdokumente.

In diesem Modus werden die Präsentationsdateien in reines HTML/CSS‑Markup gerendert, ohne SVG‑Bilder. Standardmäßig ist diese Funktion deaktiviert (false). Der vorhandene SVG‑basierte HTML‑Renderer wird verwendet, wenn diese Option nicht aktiviert ist.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Aktiviert einen neuen HTML‑Rendermodus für Präsentationsdokumente.

In diesem Modus werden die Präsentationsdateien in reines HTML/CSS‑Markup gerendert, ohne SVG‑Bilder. Standardmäßig ist diese Funktion deaktiviert (false). Der vorhandene SVG‑basierte HTML‑Renderer wird verwendet, wenn diese Option nicht aktiviert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Auflösung für Bilder innerhalb der Präsentation (nur für die HTML/PDF‑Renderung).

Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Auflösung für Bilder innerhalb der Präsentation (nur für die HTML/PDF‑Renderung).

Für ein Codebeispiel siehe die [Dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

