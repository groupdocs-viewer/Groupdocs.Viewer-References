---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Elektronik tablo belgelerinin HTML'ye render edilmesi için metin taşma modunu tanımlar."
type: docs
weight: 46
url: /tr/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Elektronik tablo belgelerinin HTML'ye render edilmesi için metin taşma modunu tanımlar.


TextOverflowMode enum'ı, GroupDocs.Viewer bileşeninde metin taşmasını yönetmek için farklı modları temsil eder.
Metin mevcut alanı aştığında nasıl görüntüleneceğini kontrol etmek için kullanılabilecek önceden tanımlanmış seçenekler seti sağlar
hücrelerdeki boşluk, elektronik tablo belgelerinin HTML'ye render edilmesi sırasında.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


Örnek kullanım:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | Boş olmayan hücrelerde bile sonraki hücreleri üzerine bindir. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Sadece boş hücrelerde sonraki hücreleri üzerine bindir. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Metni sığdırmak için sütunları genişlet. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | Taşan metni gizle. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Boş olmayan hücrelerde bile sonraki hücreleri üzerine bindir.
Bu mod, metnin komşu hücrelere, içeriklerinden bağımsız olarak taşmasına izin verir.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Sadece boş hücrelerde sonraki hücreleri üzerine bindir.
Bu mod, metnin yalnızca o hücreler boşsa komşu hücrelere taşmasına izin verir.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Metni sığdırmak için sütunları genişlet.
Bu mod, taşan metni sığdırmak için sütun genişliğini otomatik olarak ayarlar.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Taşan metni gizle.
Bu mod, taşan metni gizler ve görüntülenmesini engeller.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
