---
title: "SetLicense"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Licencia el componente."
type: docs
weight: 20
url: /es/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| licenseStream | Flujo | El flujo de licencia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *licenseStream* es nulo. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando el Stream del archivo de licencia.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string licensePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| licensePath | String | La ruta del archivo de licencia. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *licensePath* es nulo o una cadena vacía. |

### Ejemplos

El siguiente ejemplo muestra cómo establecer una licencia pasando una ruta al archivo de licencia.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### Ver también

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
