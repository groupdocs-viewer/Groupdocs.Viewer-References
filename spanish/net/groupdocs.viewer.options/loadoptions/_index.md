---
title: "LoadOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones que se utilizan para abrir el archivo. Para más detalles, consulte esta página https//docs.groupdocs.com/viewer/net/loading/ y sus hijos."
type: docs
weight: 360
url: /es/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Contiene opciones que se utilizan para abrir el archivo. Para más detalles, consulte esta [página](https://docs.groupdocs.com/viewer/net/loading/) y sus subpáginas.

```csharp
public class LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Inicializa una instancia de la clase [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Inicializa una instancia de la clase [`LoadOptions`](../loadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Habilita la detección de codificación para los archivos [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) y [`TSV`](../../groupdocs.viewer/filetype/tsv). |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Establece la codificación utilizada al abrir archivos de texto o mensajes de correo electrónico como [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) y [`MSG`](../../groupdocs.viewer/filetype/msg). El valor predeterminado es UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Establece el tipo de archivo a abrir. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Establece la contraseña para abrir el archivo cifrado. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Establece el tiempo de espera para cargar recursos externos. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | Desactiva la carga de todos los recursos externos, como imágenes, excepto [`WhitelistedResources`](./whitelistedresources). |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. El valor predeterminado es `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | La lista de fragmentos de URL correspondientes a recursos externos que deben cargarse cuando [`SkipExternalResources`](./skipexternalresources) está configurado en `true`. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
