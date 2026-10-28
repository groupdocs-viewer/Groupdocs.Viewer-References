---
title: "propiedad disable_font_license_verifications"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad desactiva cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

La propiedad desactiva cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual.

Muchas operaciones con fuentes no pueden ejecutarse si están prohibidas por la licencia de la fuente. Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación de esa fuente. Esta opción le permite omitir la verificación de estas reglas.

Tenga cuidado al usar esta bandera. Cuando está establecida, significa que la persona que la establece asume toda la responsabilidad por posibles violaciones de licencias o leyes. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. El valor predeterminado es `False`.

Para un ejemplo de código, consulte la documentación en https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Ver también
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
