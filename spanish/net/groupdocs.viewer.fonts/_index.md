---
title: "GroupDocs.Viewer.Fonts"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "El espacio de nombres proporciona clases y enumeraciones para gestionar fuentes utilizadas durante el proceso de renderizado."
type: docs
weight: 50
url: /es/net/groupdocs.viewer.fonts/
---

El espacio de nombres proporciona clases y enumeraciones para gestionar fuentes utilizadas durante el proceso de renderizado.

## Clases

| Clase | Descripción |
| --- | --- |
| [FolderFontSource](./folderfontsource) | Representa la carpeta que contiene fuentes TrueType. |
| [FontSettings](./fontsettings) | Proporciona métodos para trabajar con orígenes para buscar fuentes TrueType. |
## Structures

| Estructura | Descripción |
| --- | --- |
| [FontStyles](./fontstyles) | Representa 4 estilos posibles de la fuente, utilizados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva. |
| [PdfFontInfo](./pdffontinfo) | Encapsula metainformación y datos binarios de una fuente del documento PDF, cargada en la instancia de [`Viewer`](../groupdocs.viewer/viewer). Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer. |
| [PresentationFontInfo](./presentationfontinfo) | Encapsula metainformación y datos binarios de una fuente del documento de Presentación, cargada en la instancia de [`Viewer`](../groupdocs.viewer/viewer). Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer. |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | Encapsula metainformación y datos binarios de una fuente del documento de Hoja de cálculo, cargada en la instancia de [`Viewer`](../groupdocs.viewer/viewer). Los documentos de hoja de cálculo no pueden tener fuentes incrustadas, por lo que esta fuente en particular, si fue devuelta por el método [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts), está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer. |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | Encapsula metainformación y datos binarios de una fuente del documento de procesamiento de texto, cargada en la instancia de [`Viewer`](../groupdocs.viewer/viewer). Esta fuente se utiliza en el contenido del documento y está incrustada dentro del propio documento o está instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer. |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | Encapsula metainformación y datos binarios de una fuente del documento WordProcessing, que originalmente no se utiliza en el documento cargado en la instancia de [`Viewer`](../groupdocs.viewer/viewer), pero sirve como fuente de sustitución para aquellas que no pueden encontrarse en la máquina objetivo. Las fuentes sustitutas existen solo para la familia de formatos WordProcessing. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IFontInfo](./ifontinfo) | Interfaz común para todas las fuentes, que pueden extraerse de todas las familias de formatos de documento compatibles: PDF, WordProcessing, Spreadsheet y Presentation. |
| [IFontSource](./ifontsource) | Interfaz marcador para los orígenes de fuentes. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [FontFormat](./fontformat) | Representa todos los formatos de fuentes, que pueden estar presentes en los herederos de [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo). |
| [SearchOption](./searchoption) | Especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas. |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
