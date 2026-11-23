---
title: "DisableFontLicenseVerifications"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Desactiva cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual."
type: docs
weight: 40
url: /es/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

Desactiva cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### Observaciones

Muchas operaciones con la fuente no pueden ejecutarse si están prohibidas por la licencia de esa fuente. Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de licencia deshabilitan la incrustación de esa fuente. Esta opción le permite omitir la verificación de estas reglas.

Tenga cuidado al usar esta bandera. Cuando está establecida, significa que la persona que la establece asume toda la responsabilidad de posibles violaciones de licencia o ley. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. El valor predeterminado es `false`.

Para ver un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### Ver también

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
