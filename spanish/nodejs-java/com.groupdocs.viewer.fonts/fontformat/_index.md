---
title: "FontFormat"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa todos los formatos de fuente que pueden estar presentes en la clase UsedFontInfo."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Representa todos los formatos de fuentes, que pueden estar presentes en la clase UsedFontInfo.
## Fields

| Field | Descripción |
| --- | --- |
| [Unknown](#Unknown) | Formato de fuente desconocido o inválido. |
| [TrueType](#TrueType) | Formato de fuente TrueType (TTF). |
| [OpenType](#OpenType) | Formato de fuente OpenType (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | Formato de fuente TrueType Collection (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Formato de fuente Embedded OpenType (EOT). |
## Métodos

| Método | Descripción |
| --- | --- |
| [toString(int format)](#toString-int-) | Convierte un valor de formato a una cadena legible por humanos. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Formato de fuente desconocido o inválido.

### TrueType {#TrueType}
```
public static final int TrueType
```


Formato de fuente TrueType (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


Formato de fuente OpenType (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


Formato de fuente TrueType Collection (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Formato de fuente Embedded OpenType (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Convierte un valor de formato a una cadena legible por humanos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | int | el valor del formato de fuente |

**Returns:**
java.lang.String - una representación en cadena del formato de fuente
