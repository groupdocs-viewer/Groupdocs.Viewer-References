---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce opzioni per il rendering delle presentazioni."
type: docs
weight: 26
url: /it/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Fornisce opzioni per il rendering delle presentazioni.

Per i dettagli, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Abilita una nuova modalità di rendering HTML per i documenti Presentation. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Abilita una nuova modalità di rendering HTML per i documenti Presentation. |
| [getResolution()](#getResolution--) | Risoluzione per le immagini all'interno della presentazione (solo per il rendering HTML/PDF). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Risoluzione per le immagini all'interno della presentazione (solo per il rendering HTML/PDF). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Abilita una nuova modalità di rendering HTML per i documenti Presentation.

In questa modalità, i file Presentation vengono renderizzati in markup HTML/CSS puro, senza immagini SVG. Per impostazione predefinita, questa funzionalità è disabilitata (false). Viene utilizzato il renderer HTML basato su SVG esistente se questa opzione non è abilitata.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Abilita una nuova modalità di rendering HTML per i documenti Presentation.

In questa modalità, i file Presentation vengono renderizzati in markup HTML/CSS puro, senza immagini SVG. Per impostazione predefinita, questa funzionalità è disabilitata (false). Viene utilizzato il renderer HTML basato su SVG esistente se questa opzione non è abilitata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Risoluzione per le immagini all'interno della presentazione (solo per il rendering HTML/PDF).

Per un esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Risoluzione per le immagini all'interno della presentazione (solo per il rendering HTML/PDF).

Per un esempio di codice, vedere la [documentazione][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

