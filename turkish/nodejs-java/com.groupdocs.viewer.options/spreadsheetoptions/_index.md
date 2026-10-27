---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Elektronik tablo renderleme seçenekleri sağlar."
type: docs
weight: 31
url: /tr/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Elektronik tablo renderleme seçenekleri sağlar.

SpreadsheetOptions sınıfı, GroupDocs.Viewer bileşeninde elektronik tablo dosyalarının (örneğin Excel veya CSV dosyaları) işlenmesini kontrol etmek için kullanılabilecek çeşitli ayarları ve parametreleri kapsüller. Ayrıntılar için [Render spreadsheet files][] konusunun alt öğelerine bakın.

Örnek kullanım:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render spreadsheet files]: https://docs.groupdocs.com/viewer/java/render-spreadsheets/
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Çalışma sayfasının sayfa sonlarına göre işlenip işlenmeyeceğini belirler. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Çalışma sayfasının sayfa sonlarına göre işlenip işlenmeyeceğini ayarlar. |
| [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV dosyaları için ayırıcıyı algılar. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | CSV/TSV dosyaları için ayırıcı algılamayı ayarlar. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Tek bir sayfayı tek bir sayfaya işlemek için SpreadsheetOptions sınıfının yeni bir örneğini oluşturur. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Bir sayfayı birden çok sayfaya işlemek için SpreadsheetOptions sınıfının yeni bir örneğini oluşturur. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Bir sayfayı sayfalara işlemek için SpreadsheetOptions sınıfının yeni bir örneğini başlatır. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Yalnızca yazdırma alanlarını işlemek için SpreadsheetOptions sınıfının yeni bir örneğini başlatır. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Bir sayfanın tek bir sayfaya işlenip işlenmediğini gösterir. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek satır sayısını alır. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını alır. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını ayarlar. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Yalnızca yazdırma alanlarının işlenip işlenmediğini gösterir. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Bu seçenek etkinleştirildiğinde, çalışma sayfası yazdırma alanı içindeki sayfa sonlarına göre işlenecektir. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Yazdırma alanı içindeki sayfa sonlarına göre bir çalışma sayfasının işlenip işlenmeyeceğini ayarlar. |
| [isRenderGridLines()](#isRenderGridLines--) | Kılavuz çizgilerinin işlenmesini etkinleştirir. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Kılavuz çizgilerinin işlenmesini etkinleştirir veya devre dışı bırakır. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Boş satırların işleme sırasında atlanıp atlanmayacağını gösterir. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Boş satırların işleme sırasında atlanıp atlanmayacağını ayarlar. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Boş sütunların işleme sırasında atlanıp atlanmayacağını gösterir. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Boş sütunların işleme sırasında atlanıp atlanmayacağını ayarlar. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Gizli satırların işlenip işlenmeyeceğini belirler. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Gizli satırların işlenip işlenmeyeceğini ayarlar. |
| [isRenderHeadings()](#isRenderHeadings--) | Başlıkların işlenmesinin etkin olup olmadığını kontrol eder. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Başlıkların işlenmesini etkinleştirir. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Gizli sütunların işlenmesini etkinleştirir. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Gizli sütunların işlenmesini etkinleştirir. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Elektronik tablo belgelerini HTML'ye render ederken metin taşma modunu döndürür. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Elektronik tablo belgelerini HTML'ye render ederken metin taşma modunu ayarlar. |
| [getLeftMargin()](#getLeftMargin--) | Çalışma sayfasının sol kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Çalışma sayfasının sol kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. |
| [getRightMargin()](#getRightMargin--) | Çalışma sayfasının sağ kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Çalışma sayfasının sağ kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
| [getTopMargin()](#getTopMargin--) | Çalışma sayfasının üst kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Çalışma sayfasının üst kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
| [getBottomMargin()](#getBottomMargin--) | Çalışma sayfasının alt kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Çalışma sayfasının alt kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Baskı alanlarını ve sayfa sonlarını render etmek için yeni bir SpreadsheetOptions örneği başlatır. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Yalnızca yazdırma alanlarını işlemek için SpreadsheetOptions sınıfının yeni bir örneğini başlatır. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Çalışma sayfasının sayfa sonlarına göre işlenip işlenmeyeceğini belirler.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  eğer çalışma sayfası sayfa sonlarıyla render edilmesi gerekiyorsa,  false  aksi takdirde.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Çalışma sayfasının sayfa sonlarına göre işlenip işlenmeyeceğini ayarlar.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  eğer çalışma sayfası sayfa sonlarıyla render edilmesi gerekiyorsa,  false  aksi takdirde. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV dosyaları için ayırıcıyı algılar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  eğer ayırıcı otomatik olarak algılanmalıysa,  false  aksi takdirde.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


CSV/TSV dosyaları için ayırıcı algılamayı ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| detectSeparator | boolean | true  ayırıcıyı otomatik olarak algılamak için,  false  aksi takdirde. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Tek bir sayfayı tek bir sayfaya işlemek için SpreadsheetOptions sınıfının yeni bir örneğini oluşturur.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Bir sayfayı birden çok sayfaya işlemek için SpreadsheetOptions sınıfının yeni bir örneğini oluşturur.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| countRowsPerPage | int | Her sayfada dahil edilecek satır sayısı. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Bir sayfayı sayfalara işlemek için SpreadsheetOptions sınıfının yeni bir örneğini başlatır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| countRowsPerPage | int | Her sayfada dahil edilecek satır sayısı. |
| countColumnsPerPage | int | Her sayfada dahil edilecek sütun sayısı. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Yalnızca yazdırma alanlarını işlemek için SpreadsheetOptions sınıfının yeni bir örneğini başlatır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Bir sayfanın tek bir sayfaya işlenip işlenmediğini gösterir.

**Returns:**
boolean -  true  eğer bir sayfa tek bir sayfaya render ediliyorsa;  false  aksi takdirde.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek satır sayısını alır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - her sayfaya dahil edilecek satır sayısı.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını alır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - her sayfaya dahil edilecek sütun sayısı.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| countColumnsPerPage | int | Her sayfaya dahil edilecek sütun sayısı. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Yalnızca yazdırma alanlarının işlenip işlenmediğini gösterir.

**Returns:**
boolean -  true  eğer yalnızca baskı alanları render ediliyorsa,  false  aksi takdirde.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Bu seçenek etkinleştirildiğinde, çalışma sayfası yazdırma alanı içindeki sayfa sonlarına göre işlenecektir.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Yazdırma alanı içindeki sayfa sonlarına göre bir çalışma sayfasının işlenip işlenmeyeceğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | true etkinleştirmek için, false devre dışı bırakmak için ayarlayın. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Kılavuz çizgilerinin işlenmesini etkinleştirir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  eğer ızgara çizgileri etkinse,  false  aksi takdirde.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Kılavuz çizgilerinin işlenmesini etkinleştirir veya devre dışı bırakır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  ızgara çizgileri renderını etkinleştirmek için,  false  devre dışı bırakmak için. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Boş satırların işleme sırasında atlanıp atlanmayacağını gösterir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  eğer boş satırlar atlanmalıysa,  false  aksi takdirde.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Boş satırların işleme sırasında atlanıp atlanmayacağını ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  boş satırları atlamak için,  false  aksi takdirde. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Boş sütunların işleme sırasında atlanıp atlanmayacağını gösterir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  eğer boş sütunlar atlanıyorsa,  false  aksi takdirde.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Boş sütunların işleme sırasında atlanıp atlanmayacağını ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  boş sütunları atlamak için,  false  aksi takdirde. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Gizli satırların işlenip işlenmeyeceğini belirler.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  eğer gizli satırlar renderlanmalıysa,  false  aksi takdirde.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Gizli satırların işlenip işlenmeyeceğini ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  gizli satırların renderını etkinleştirmek için,  false  devre dışı bırakmak için. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Başlıkların işlenmesinin etkin olup olmadığını kontrol eder.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  eğer başlıkların renderı etkinse,  false  aksi takdirde.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Başlıkların işlenmesini etkinleştirir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderHeadings | boolean | true  başlıkların renderını etkinleştirmek için,  false  devre dışı bırakmak için. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Gizli sütunların işlenmesini etkinleştirir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  eğer gizli sütunların renderı etkinse,  false  aksi takdirde.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Gizli sütunların işlenmesini etkinleştirir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  gizli sütunların renderını etkinleştirmek için,  false  devre dışı bırakmak için. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Elektronik tablo belgelerini HTML'ye render ederken metin taşma modunu döndürür.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Elektronik tablo belgelerinin HTML'e renderlanması için metin taşması modunu ayarlar. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Ayarlanacak metin taşması modu. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Çalışma sayfasının sol kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır.

Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Çalışma sayfasının sol kenar boşluğunu PDF'ye dönüştürürken ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır.

Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Çalışma sayfasının PDF'ye dönüştürülürken sağ kenar boşluğunu ayarlamak için; eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Çalışma sayfasının PDF'ye dönüştürülürken sağ kenar boşluğunu ayarlamak için; eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Çalışma sayfasının PDF'ye dönüştürülürken üst kenar boşluğunu ayarlamak için; eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Çalışma sayfasının PDF'ye dönüştürülürken üst kenar boşluğunu ayarlamak için; eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Çalışma sayfasının PDF'ye dönüştürülürken alt kenar boşluğunu ayarlamak için; eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Çalışma sayfasının PDF'ye dönüştürülürken alt kenar boşluğunu ayarlamak için; eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Baskı alanları ve sayfa sonlarını renderlamak için yeni bir SpreadsheetOptions örneği başlatır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Yalnızca baskı alanlarını renderlamak için yeni bir SpreadsheetOptions sınıfı örneği başlatır. Ayrıntılar için [documentation][] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
