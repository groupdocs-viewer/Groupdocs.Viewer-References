---
title: "com.groupdocs.viewer.fonts"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "El paquete proporciona clases y enumeraciones para gestionar fuentes utilizadas durante el proceso de renderizado."
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.viewer.fonts/
---

El paquete proporciona clases y enumeraciones para gestionar fuentes utilizadas durante el proceso de renderizado.

Las principales clases e interfaces en este paquete son:

 *  [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
 *  [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
 *  [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.

Para obtener más detalles sobre cómo trabajar con fuentes en GroupDocs.Viewer, consulte la [Documentación de GroupDocs.Viewer][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Clases

| Clase | Descripción |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Representa una carpeta que contiene fuentes TrueType. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Representa todos los formatos de fuentes, que pueden estar presentes en la clase UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Proporciona métodos para trabajar con fuentes para buscar fuentes TrueType. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Representa 4 estilos posibles de la fuente, usados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Encapsula meta‑información y datos binarios de una fuente de un documento PDF, cargada en la instancia del Viewer. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Encapsula metadatos y datos binarios de una fuente usada en un documento de Presentación, cargada en la instancia del Viewer. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Encapsula información de metadatos y datos binarios de una fuente del documento de Hoja de cálculo, cargada en la instancia del Viewer. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Encapsula información de metadatos y datos binarios de una fuente del documento de Procesamiento de Texto, cargada en la instancia del Viewer. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Encapsula metadatos y datos binarios de una fuente sustituida usada en un documento de Procesamiento de Texto a través de GroupDocs.Viewer. |

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Interfaz marcador para las fuentes de tipografía. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Interfaz común para todas las fuentes que pueden extraerse de los formatos de documento: PDF, WordProcessing, Spreadsheet y Presentation. |

## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas. |
