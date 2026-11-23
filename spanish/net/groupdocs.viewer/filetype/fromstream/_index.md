---
title: "FromStream"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Detecta el tipo de archivo leyendo la firma del archivo."
type: docs
weight: 2000
url: /es/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

Detecta el tipo de archivo leyendo la firma del archivo.

```csharp
public static FileType FromStream(Stream stream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |

### Ver también

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

Detecta el tipo de archivo leyendo la firma del archivo.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| password | String | La contraseña para abrir el archivo. |

### Ver también

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

Detecta el tipo de archivo leyendo la firma del archivo.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| logger | ILogger | El logger. |

### Valor devuelto

Devuelve el tipo de archivo en caso de que se haya detectado correctamente; de lo contrario, devuelve el tipo de archivo predeterminado [`Unknown`](../unknown).

### Ver también

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

Detecta el tipo de archivo leyendo la firma del archivo.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| password | String | La contraseña para abrir el archivo. |
| logger | ILogger | El logger. |

### Valor devuelto

Devuelve el tipo de archivo en caso de que se haya detectado correctamente; de lo contrario, devuelve el tipo de archivo predeterminado [`Unknown`](../unknown).

### Ver también

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
