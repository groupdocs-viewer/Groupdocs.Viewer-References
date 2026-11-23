---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Präsentationen bereit."
type: docs
weight: 26
url: /de/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Stellt Optionen zum Rendern von Präsentationen bereit.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Aktiviert einen neuen HTML-Rendermodus für Präsentationsdokumente. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Aktiviert einen neuen HTML-Rendermodus für Präsentationsdokumente. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Aktiviert das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Aktiviert das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie. |
|
|  | [getResolution()](#getResolution--) | Auflösung für Bilder innerhalb der Präsentation (nur für das Rendern zu HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Auflösung für Bilder innerhalb der Präsentation (nur für das Rendern zu HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Aktiviert einen neuen HTML-Rendermodus für Präsentationsdokumente.


In diesem Modus werden die Präsentationsdateien in reines HTML/CSS-Markup gerendert, ohne SVG-Bilder.
Standardmäßig ist diese Funktion deaktiviert (false). Der vorhandene SVG-basierte HTML-Renderer wird verwendet, wenn diese Option nicht aktiviert ist.


**Returns:**
boolesch
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Aktiviert einen neuen HTML-Rendermodus für Präsentationsdokumente.


In diesem Modus werden die Präsentationsdateien in reines HTML/CSS-Markup gerendert, ohne SVG-Bilder.
Standardmäßig ist diese Funktion deaktiviert (false). Der vorhandene SVG-basierte HTML-Renderer wird verwendet, wenn diese Option nicht aktiviert ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderToPureHtml | boolesch |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Aktiviert das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie. Standardmäßig deaktiviert (false). Diese Option gilt für alle 4 Rendermodi von Präsentationen: HTML, PDF, PNG und JPEG. Nicht anwendbar beim Rendern einer Präsentation zu reinem HTML/CSS-Markup mittels .


**Returns:**
boolesch
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Aktiviert das Rendern von Platzhaltern in Kopf- und Fußzeile einer Folie. Standardmäßig deaktiviert (false). Diese Option gilt für alle 4 Rendermodi von Präsentationen: HTML, PDF, PNG und JPEG. Nicht anwendbar beim Rendern einer Präsentation zu reinem HTML/CSS-Markup mittels .


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolesch |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Auflösung für Bilder innerhalb der Präsentation (nur für das Rendern zu HTML/PDF).


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Auflösung für Bilder innerhalb der Präsentation (nur für das Rendern zu HTML/PDF).


Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

