---
title: "LotusNotesViewInfo"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Representa información de vista para el almacenamiento de bases de datos Lotus Notes."
type: docs
weight: 19
url: /es/nodejs-java/com.groupdocs.viewer.results/lotusnotesviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface LotusNotesViewInfo extends ViewInfo
```

Representa información de vista para el almacenamiento de bases de datos Lotus Notes.

La interfaz LotusNotesViewInfo define el contrato para acceder y manipular la información de vista del almacenamiento de bases de datos Lotus Notes en el componente GroupDocs.Viewer. Proporciona métodos para obtener información como el recuento de notas y otras propiedades.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("document.nsf")) {
     final LotusNotesViewInfo viewInfo = (LotusNotesViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is LotusNotesViewInfoImpl.*
## Métodos

| Método | Descripción |
| --- | --- |
| [getNotesCount()](#getNotesCount--) | Recupera el recuento de notas en el almacenamiento. |
| [setNotesCount(int count)](#setNotesCount-int-) | Establece el recuento de notas en el almacenamiento. |
### getNotesCount() {#getNotesCount--}
```
public abstract int getNotesCount()
```


Recupera el recuento de notas en el almacenamiento.

**Returns:**
int - el recuento de notas en el almacenamiento.
### setNotesCount(int count) {#setNotesCount-int-}
```
public abstract void setNotesCount(int count)
```


Establece el recuento de notas en el almacenamiento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| recuento | int | el recuento de notas en el almacenamiento. |

