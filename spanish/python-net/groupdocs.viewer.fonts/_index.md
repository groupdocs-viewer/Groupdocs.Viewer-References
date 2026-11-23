---
title: "groupdocs.viewer.fonts"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Configuración de carga y sustitución de fuentes."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Configuración de carga y sustitución de fuentes.

### Clases
| Clase | Descripción |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Representa la carpeta que contiene fuentes TrueType. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Proporciona métodos para trabajar con orígenes y buscar fuentes TrueType. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Representa 4 estilos posibles de la fuente, utilizados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Representa una interfaz común para todas las fuentes que pueden extraerse de todas las familias de formatos de documento compatibles: PDF, WordProcessing, Spreadsheet y Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Encapsula los metadatos y los datos binarios de una fuente PDF cargada en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), que puede estar incrustada en el documento o instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Representa la información de metadatos y los datos binarios de una fuente de un documento Presentation cargado en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). La fuente se utiliza en el contenido del documento y puede estar incrustada en el documento o instalada en el sistema operativo donde se ejecuta el visor. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Encapsula la información de metadatos y los datos binarios de una fuente de un documento de hoja de cálculo cargado en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Los documentos de hoja de cálculo no pueden contener fuentes incrustadas, por lo que una fuente devuelta por [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) se instala en el sistema operativo donde se ejecuta el visor. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Encapsula la información de metadatos y los datos binarios de una fuente de un documento WordProcessing cargado en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Encapsula la información de metadatos y los datos binarios de una fuente de un documento WordProcessing, que originalmente no se utiliza en el documento de la instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) cargada, pero sirve como fuente de sustitución para aquellas que no pueden encontrarse en la máquina de destino. Las fuentes sustitutas existen solo para la familia de formatos WordProcessing. |

### Enumeraciones
| Enumeración | Descripción |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Representa una interfaz marcador para fuentes. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
