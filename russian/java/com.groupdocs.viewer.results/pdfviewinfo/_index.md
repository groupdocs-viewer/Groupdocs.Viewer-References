---
title: "PdfViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет информацию о представлении PDF‑документа."
type: docs
weight: 24
url: /ru/java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

Представляет информацию о представлении PDF‑документа.


Интерфейс PdfViewInfo определяет контракт для доступа и изменения информации представления
для PDF‑документа в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации
таких как разрешение печати и другие свойства.


Пример использования:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is PdfViewInfoImpl.*

## Методы

| Метод | Описание |
| --- | --- |
|  | [isPrintingAllowed()](#isPrintingAllowed--) | Проверяет, разрешена ли печать документа. |
|
|  | [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | Устанавливает, разрешена ли печать документа. |
|
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


Проверяет, разрешена ли печать документа.


**Returns:**
boolean -  true  если печать разрешена,  false  в противном случае.

### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


Устанавливает, разрешена ли печать документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | allowPrinting | boolean | true  для разрешения печати,  false  в противном случае. |
|

