---
title: "Position"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Filigran konumunu tanımlar."
type: docs
weight: 43
url: /tr/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Filigran konumunu tanımlar.

Position enum'ı, GroupDocs.Viewer bileşeninde bir filigran için farklı konumları temsil eder. Renderleme sürecinde bir belge veya görüntü üzerine filigranın yerleştirilmesini belirlemek için kullanılabilecek önceden tanımlanmış bir dizi konum sağlar.

Örnek kullanım:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Açıklama |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | Diyagonal konum. |
| [TOP_LEFT](#TOP-LEFT) | Üst sol konum. |
| [TOP_CENTER](#TOP-CENTER) | Üst orta konum. |
| [TOP_RIGHT](#TOP-RIGHT) | Üst sağ konum. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | Alt sol konum. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | Alt orta konum. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | Alt sağ konum. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


Diyagonal konum. Bu konum, diyagonal bir hizalama veya yerleşimi temsil eder.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


Üst sol konum. Bu konum, üst sol köşe hizalamasını veya yerleşimini temsil eder.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


Üst orta konum. Bu konum, üst orta hizalamasını veya yerleşimini temsil eder.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


Üst sağ konum. Bu konum, üst sağ köşe hizalamasını veya yerleşimini temsil eder.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


Alt sol konum. Bu konum, alt sol köşe hizalamasını veya yerleşimini temsil eder.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


Alt orta konum. Bu konum, alt orta hizalamasını veya yerleşimini temsil eder.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


Alt sağ konum. Bu konum, alt sağ köşe hizalamasını veya yerleşimini temsil eder.

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
