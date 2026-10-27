---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Elektronik tablo belgelerini HTML'ye renderleme için metin taşma modunu tanımlar."
type: docs
weight: 46
url: /tr/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Elektronik tablo belgelerini HTML'ye renderleme için metin taşma modunu tanımlar.

TextOverflowMode enum'u, GroupDocs.Viewer bileşeninde metin taşmasını yönetmek için farklı modları temsil eder. Hücrelerdeki mevcut alanı aşan metnin, elektronik tablo belgelerinin HTML'ye render edilmesi sırasında nasıl görüntüleneceğini kontrol etmek için kullanılabilecek önceden tanımlı seçenekler seti sağlar. Ayrıntılar için [documentation][] sayfasına bakın.

Örnek kullanım:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## Fields

| Field | Açıklama |
| --- | --- |
| [OVERLAY](#OVERLAY) | Boş olmasalar bile sonraki hücreleri ört. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Sadece boş olduklarında sonraki hücreleri ört. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Metne sığdırmak için sütunları genişlet. |
| [HIDE_TEXT](#HIDE-TEXT) | Taşan metni gizle. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Boş olmasalar bile sonraki hücreleri ört. Bu mod, metnin içeriğine bakılmaksızın komşu hücrelere taşmasına izin verir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Sadece boş olduklarında sonraki hücreleri ört. Bu mod, metnin yalnızca bu hücreler boşsa komşu hücrelere taşmasına izin verir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Metne sığdırmak için sütunları genişlet. Bu mod, taşan metni sığdırmak için sütun genişliğini otomatik olarak ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Taşan metni gizle. Bu mod, taşan metni gizleyerek görüntülenmesini engeller.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

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
