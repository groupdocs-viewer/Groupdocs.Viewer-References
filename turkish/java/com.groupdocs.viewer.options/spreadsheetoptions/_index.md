---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Elektronik tabloları işlemek için seçenekler sağlar."
type: docs
weight: 31
url: /tr/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Elektronik tabloları işlemek için seçenekler sağlar.


SpreadsheetOptions sınıfı, kullanılabilecek çeşitli ayarları ve parametreleri kapsar
GroupDocs.Viewer bileşeninde elektronik tablo dosyalarının (örneğin Excel veya CSV dosyaları) oluşturulmasını kontrol etmek için.
Ayrıntılar için, [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/) konusunun alt bölümlerine bakın.


Örnek kullanım:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Çalışma sayfasının sayfa sonlarına göre oluşturulup oluşturulmayacağını belirler. |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Çalışma sayfasının sayfa sonlarına göre oluşturulup oluşturulmayacağını ayarlar. |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV dosyaları için ayırıcıyı algılar. |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | CSV/TSV dosyaları için ayırıcıyı algılayıp almayacağını ayarlar. |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | Yeni bir örnek oluşturur. |
SpreadsheetOptions
bir sayfada bir sayfa oluşturmak için sınıf.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Yeni bir örnek oluşturur. |
SpreadsheetOptions
bir sayfayı birden çok sayfaya oluşturmak için sınıf.
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Yeni bir örnek başlatır |
SpreadsheetOptions
bir sayfayı sayfalara oluşturmak için sınıf.
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | Yeni bir örnek başlatır |
SpreadsheetOptions
yalnızca yazdırma alanlarını oluşturmak için sınıf.
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | Bir sayfanın bir sayfaya oluşturulup oluşturulmadığını gösterir. |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek satır sayısını alır. |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını alır. |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını ayarlar. |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Yalnızca yazdırma alanlarının oluşturulup oluşturulmadığını gösterir. |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Bu seçenek etkinleştirildiğinde, çalışma sayfası yazdırma alanı içindeki sayfa sonlarına göre oluşturulur. |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Yazdırma alanı içindeki sayfa sonlarına göre bir çalışma sayfasının oluşturulup oluşturulmayacağını ayarlar. |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | Kılavuz çizgilerinin oluşturulmasını etkinleştirir. |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Kılavuz çizgilerinin oluşturulmasını etkinleştirir veya devre dışı bırakır. |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | Boş satırların oluşturma sırasında atlanıp atlanmayacağını gösterir. |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Boş satırların işleme sırasında atlanıp atlanmayacağını ayarlar. |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Boş sütunların işleme sırasında atlanıp atlanmayacağını gösterir. |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Boş sütunların işleme sırasında atlanıp atlanmayacağını ayarlar. |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | Gizli satırların işlenip işlenmeyeceğini belirler. |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Gizli satırların işlenip işlenmeyeceğini ayarlar. |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | Başlıkların işlenmesinin etkin olup olmadığını kontrol eder. |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Başlıkların işlenmesini etkinleştirir. |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Gizli sütunların işlenmesini etkinleştirir. |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Gizli sütunların işlenmesini etkinleştirir. |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | Elektronik tablo belgelerinin HTML'e işlenmesi için metin taşması modunu döndürür. |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Elektronik tablo belgelerinin HTML'e işlenmesi için metin taşması modunu ayarlar. |
|
|  | [getLeftMargin()](#getLeftMargin--) | Çalışma sayfasını PDF'e dönüştürürken sol kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Çalışma sayfasını PDF'e dönüştürürken sol kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. |
|
|  | [getRightMargin()](#getRightMargin--) | Çalışma sayfasını PDF'e dönüştürürken sağ kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | Çalışma sayfasını PDF'e dönüştürürken sağ kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
|
|  | [getTopMargin()](#getTopMargin--) | Çalışma sayfasını PDF'e dönüştürürken üst kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | Çalışma sayfasını PDF'e dönüştürürken üst kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Çalışma sayfasını PDF'e dönüştürürken alt kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Çalışma sayfasını PDF'e dönüştürürken alt kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü alır veya ayarlar. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü ayarlar. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlüğü alır veya ayarlar. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlüğü ayarlar. |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Baskı alanları ve sayfa sonlarını işlemek için yeni bir SpreadsheetOptions örneği başlatır. |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Yalnızca baskı alanlarını işlemek için yeni bir SpreadsheetOptions sınıfı örneği başlatır. |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Çalışma sayfasının sayfa sonlarına göre oluşturulup oluşturulmayacağını belirler.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  eğer çalışma sayfası sayfa sonlarına göre işlenecekse,  false  aksi takdirde.

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Çalışma sayfasının sayfa sonlarına göre oluşturulup oluşturulmayacağını ayarlar.


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  eğer çalışma sayfası sayfa sonlarına göre işlenecekse,  false  aksi takdirde. |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV dosyaları için ayırıcıyı algılar.


Ayrıntılar için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator) adresine bakın.


**Returns:**
boolean -  true  eğer ayırıcı otomatik olarak algılanacaksa,  false  aksi takdirde.

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


CSV/TSV dosyaları için ayırıcıyı algılayıp almayacağını ayarlar.


Ayrıntılar için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | detectSeparator | boolean | true  otomatik olarak ayırıcıyı algılamak için,  false  aksi takdirde. |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Yeni bir örnek oluşturur.
SpreadsheetOptions
bir sayfada bir sayfa oluşturmak için sınıf.
Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Yeni bir örnek oluşturur.
SpreadsheetOptions
bir sayfayı birden çok sayfaya oluşturmak için sınıf.
Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | countRowsPerPage | int | Her sayfada dahil edilecek satır sayısı. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Yeni bir örnek başlatır
SpreadsheetOptions
bir sayfayı sayfalara oluşturmak için sınıf.
Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | countRowsPerPage | int | Her sayfada dahil edilecek satır sayısı. |
|
|  | countColumnsPerPage | int | Her sayfada dahil edilecek sütun sayısı. |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Yeni bir örnek başlatır
SpreadsheetOptions
yalnızca yazdırma alanlarını oluşturmak için sınıf.
Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Bir sayfanın bir sayfaya oluşturulup oluşturulmadığını gösterir.


**Returns:**
boolean -  true  bir sayfa bir sayfaya render edilirse;  false  aksi takdirde.

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek satır sayısını alır.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).


**Returns:**
int - her sayfaya dahil edilecek satır sayısı.

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını alır.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Returns:**
int - her sayfaya dahil edilecek sütun sayısı.

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Çalışma sayfasını sayfalara bölerken her sayfaya dahil edilecek sütun sayısını ayarlar.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | countColumnsPerPage | int | Her sayfaya dahil edilecek sütun sayısı. |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Yalnızca yazdırma alanlarının oluşturulup oluşturulmadığını gösterir.


**Returns:**
boolean -  true  yalnızca baskı alanları render edilirse,  false  aksi takdirde.

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Bu seçenek etkinleştirildiğinde, çalışma sayfası yazdırma alanı içindeki sayfa sonlarına göre oluşturulur.


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Yazdırma alanı içindeki sayfa sonlarına göre bir çalışma sayfasının oluşturulup oluşturulmayacağını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | Etkinleştirmek için true, devre dışı bırakmak için false olarak ayarlayın. |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Kılavuz çizgilerinin oluşturulmasını etkinleştirir.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
boolean -  true  ızgara çizgileri etkinse,  false  aksi takdirde.

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Kılavuz çizgilerinin oluşturulmasını etkinleştirir veya devre dışı bırakır.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  ızgara çizgileri render etmeyi etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Boş satırların oluşturma sırasında atlanıp atlanmayacağını gösterir.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  boş satırların atlanması gerekiyorsa,  false  aksi takdirde.

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Boş satırların işleme sırasında atlanıp atlanmayacağını ayarlar.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  boş satırları atlamak için,  false  aksi takdirde. |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Boş sütunların işleme sırasında atlanıp atlanmayacağını gösterir.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  boş sütunlar atlanıyorsa,  false  aksi takdirde.

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Boş sütunların işleme sırasında atlanıp atlanmayacağını ayarlar.


Ayrıntılar için, [belge](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  boş sütunları atlamak için,  false  aksi takdirde. |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Gizli satırların işlenip işlenmeyeceğini belirler.


Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) bakın.


**Returns:**
boolean -  true  gizli satırlar işlenmesi gerekiyorsa,  false  aksi takdirde.

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Gizli satırların işlenip işlenmeyeceğini ayarlar.


Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  gizli satırların işlenmesini etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Başlıkların işlenmesinin etkin olup olmadığını kontrol eder.


Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings) bakın.


**Returns:**
boolean -  true  başlık işleme etkinse,  false  aksi takdirde.

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Başlıkların işlenmesini etkinleştirir.


Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderHeadings | boolean | true  başlık işleme etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Gizli sütunların işlenmesini etkinleştirir.


Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) bakın.


**Returns:**
boolean -  true  gizli sütunların işlenmesi etkinse,  false  aksi takdirde.

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Gizli sütunların işlenmesini etkinleştirir.


Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  gizli sütunların işlenmesini etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Elektronik tablo belgelerinin HTML'e işlenmesi için metin taşması modunu döndürür.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Elektronik tablo belgelerinin HTML'e işlenmesi için metin taşması modunu ayarlar. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Ayarlanacak metin taşması modu. |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Çalışma sayfasını PDF'e dönüştürürken sol kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır.


Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Çalışma sayfasını PDF'e dönüştürürken sol kenar boşluğunu ayarlamak için, değer 0'dan küçükse varsayılan dönüşüm değeri kullanılır.


Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


PDF'ye dönüştürürken çalışma sayfasının sağ kenar boşluğunu ayarlamak için, eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


PDF'ye dönüştürürken çalışma sayfasının sağ kenar boşluğunu ayarlamak için, eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


PDF'ye dönüştürürken çalışma sayfasının üst kenar boşluğunu ayarlamak için, eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


PDF'ye dönüştürürken çalışma sayfasının üst kenar boşluğunu ayarlamak için, eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


PDF'ye dönüştürürken çalışma sayfasının alt kenar boşluğunu ayarlamak için, eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


PDF'ye dönüştürürken çalışma sayfasının alt kenar boşluğunu ayarlamak için, eğer 0'dan küçükse varsayılan dönüştürme değeri kullanılır. Parametre 0'dan küçükse, varsayılan değer kullanılır. Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü alır veya ayarlar. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatlarına işlenirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Returns:**
int - DPI cinsinden yatay çözünürlük.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Oluşturulan görüntüler için yatay çözünürlüğü inç başına nokta (dpi) olarak ayarlar. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | horizontalResolution | int | yatay çözünürlük DPI cinsinden. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Oluşturulan görüntüler için dikey çözünürlüğü inç başına nokta (dpi) olarak alır veya ayarlar. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Returns:**
int - dikey çözünürlük DPI cinsinden.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Oluşturulan görüntüler için dikey çözünürlüğü inç başına nokta (dpi) olarak ayarlar. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verticalResolution | int | dikey çözünürlük DPI cinsinden. |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Yeni bir SpreadsheetOptions örneği başlatarak baskı alanları ve sayfa sonlarını render eder. Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area) bakın.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Yalnızca baskı alanlarını render etmek için SpreadsheetOptions sınıfının yeni bir örneğini başlatır. Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/) bakın.


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

