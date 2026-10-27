---
title: "Watermark"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Metin filigranını temsil eder."
type: docs
weight: 37
url: /tr/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Metin filigranını temsil eder. Ayrıntılar için [documentation][] sayfasına bakın.

Watermark sınıfı, GroupDocs.Viewer bileşeninde bir metin filigranını temsil eder. Belgelerin render edilen çıktısına bir filigran tanımlamak ve uygulamak için kullanılır.

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


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Watermark sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getText()](#getText--) | Filigran metnini döndürür. |
| [getColor()](#getColor--) | Filigran rengini döndürür. |
| [getColorAsHex()](#getColorAsHex--) | Filigran rengini onaltılık biçimde döndürür. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Filigran rengini ayarlar. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Filigran rengini ayarlar. |
| [getPosition()](#getPosition--) | Filigran konumunu döndürür. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Filigran konumunu ayarlar. |
| [getSize()](#getSize--) | Filigran boyutunu döndürür. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Filigran boyutunu ayarlar. |
| [getFontName()](#getFontName--) | Filigran için kullanılan yazı tipi adını döndürür. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Filigran için kullanılan yazı tipi adını ayarlar. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Watermark sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Filigran metni. |

### getText() {#getText--}
```
public final String getText()
```


Filigran metnini döndürür. Bu yöntem, belgeye uygulanan filigranın metnini alır.

**Returns:**
java.lang.String - filigran metni.
### getColor() {#getColor--}
```
public final Color getColor()
```


Filigran rengini döndürür. Bu yöntem, belgeye uygulanan filigranın rengini alır.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - filigran rengi.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Filigran rengini onaltılık biçimde döndürür. Bu yöntem, belgeye uygulanan filigranın rengini alır.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - filigran renginin onaltılık biçimi.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Filigran rengini ayarlar. Bu yöntem, belgeye uygulanan filigranın rengini belirler.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color | Ayarlanacak filigran rengi. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Filigran rengini ayarlar. Bu yöntem, belgeye uygulanan filigranın rengini belirler.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorName | java.lang.String | Ayarlanacak filigran rengi. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Filigran konumunu döndürür. Bu yöntem, belgeye uygulanan filigranın konumunu verir.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Filigran konumunu ayarlar. Bu yöntem, belgeye uygulanan filigranın konumunu belirler.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | Filigran konumu. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Filigran boyutunu döndürür. Bu yöntem, belgeye uygulanan filigranın boyutunu alır.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Filigran boyutunu ayarlar. Bu yöntem, belgeye uygulanacak filigranın boyutunu ayarlar.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | Filigran boyutu. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Filigran için kullanılan yazı tipi adını döndürür.

**Returns:**
java.lang.String - filigran için kullanılan yazı tipi adı.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Filigran için kullanılan yazı tipi adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Filigran için kullanılan yazı tipi adı. |

