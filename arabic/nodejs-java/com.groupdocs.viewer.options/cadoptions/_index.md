---
title: "CadOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض رسومات CAD."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

يوفر خيارات لعرض رسومات CAD.

فئة CadOptions تضم إعدادات ومعلمات مختلفة يمكن استخدامها للتحكم في عرض رسومات CAD في مكوّن GroupDocs.Viewer.

لمزيد من المعلومات وأمثلة التعليمات البرمجية، راجع [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] و [Specify rendering options for CAD files][].

مثال على الاستخدام:

```

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## الحقول

| حقل | الوصف |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPc3File()](#getPc3File--) | يسترجع ملف PC3 (تكوين المؤطر) المرتبط بالمخطط. |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | يضبط ملف PC3 (تكوين المؤطر) المرتبط بالمخطط. |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | ينشئ مثيلاً جديدًا من فئة  CadOptions  للعرض وفقًا لعامل المقياس. |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | ينشئ مثيلاً جديدًا من فئة  CadOptions  للعرض وفقًا للعرض. |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | ينشئ مثيلاً جديدًا من فئة  CadOptions  للعرض وفقًا للارتفاع. |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | يُنشئ مثيلاً جديدًا من الفئة CadOptions للعرض حسب العرض والارتفاع. |
| [getScaleFactor()](#getScaleFactor--) | يحصل على معامل المقياس للعرض. |
| [getWidth()](#getWidth--) | يحصل على عرض النتيجة الناتجة بالبكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع النتيجة الناتجة بالبكسل. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الخلفية للصورة. |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | يحصل على لون الخلفية للصورة. |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | يضبط لون الخلفية للصورة. |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | يضبط لون الخلفية للصورة. |
| [getTiles()](#getTiles--) | يحصل على مناطق الرسم للعرض. |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | يضبط مناطق الرسم للعرض. |
| [isRenderLayouts()](#isRenderLayouts--) | يشير إلى ما إذا كان يجب عرض التخطيطات من مستند CAD. |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | يضبط ما إذا كان يجب عرض التخطيطات من مستند CAD. |
| [getLayoutName()](#getLayoutName--) | يحصل على اسم التخطيط المحدد للعرض. |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | يضبط اسم التخطيط المحدد للعرض. |
| [getLayers()](#getLayers--) | يحصل على طبقات الرسم CAD للعرض. |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | يحصل على طبقات الرسم CAD للعرض. |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | ضبط هذا العلم على true يُفعِّل وضع تحويل خاص يركز على الأداء لجميع الصيغ داخل عائلة CAD. |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | ضبط هذا العلم على true يُفعِّل وضع تحويل خاص يركز على الأداء لجميع الصيغ داخل عائلة CAD. |
| [equals(Object o)](#equals-java.lang.Object-) | يتحقق مما إذا كان كائن CadOptions هذا يساوي كائنًا آخر. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


يسترجع ملف PC3 (تكوين المؤطر) المرتبط بالمخطط.

**Returns:**
java.lang.String - مسار ملف PC3.
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


يضبط ملف PC3 (تكوين المؤطر) المرتبط بالمخطط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pc3File | java.lang.String | مسار ملف PC3. |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


ينشئ مثيلاً جديدًا من فئة  CadOptions  للعرض وفقًا لعامل المقياس.

للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleFactor | double | معامل المقياس للعرض. القيم الأكبر من 1 ستكبر النتيجة الناتجة، بينما القيم بين 0 و 1 ستصغر النتيجة الناتجة. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


ينشئ مثيلاً جديدًا من فئة  CadOptions  للعرض وفقًا للعرض.

للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض النتيجة الناتجة بالبكسل. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


ينشئ مثيلاً جديدًا من فئة  CadOptions  للعرض وفقًا للارتفاع.

للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| height | int | ارتفاع النتيجة الناتجة بالبكسل. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


يُنشئ مثيلاً جديدًا من الفئة CadOptions للعرض حسب العرض والارتفاع.

للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض النتيجة الناتجة بالبكسل. |
| height | int | ارتفاع النتيجة الناتجة بالبكسل. |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


يحصل على معامل المقياس للعرض. القيم الأعلى من 1 ستكبر النتيجة الناتجة، بينما القيم بين 0 و 1 ستصغر النتيجة الناتجة.

**Returns:**
double - معامل المقياس للعرض.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض النتيجة الناتجة بالبكسل.

**Returns:**
int - عرض النتيجة الناتجة.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع النتيجة الناتجة بالبكسل.

**Returns:**
int - ارتفاع النتيجة الناتجة.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الخلفية للصورة.

**Returns:**
java.awt.Color - لون الخلفية للصورة.
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


يحصل على لون الخلفية للصورة.

**Returns:**
java.lang.String - لون الخلفية للصورة بصيغة 0xFFFFFF.
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


يضبط لون الخلفية للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| backgroundColor | java.awt.Color | لون الخلفية للصورة. |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


يضبط لون الخلفية للصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| colorName | java.lang.String | اسم لون الخلفية للصورة. |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


يحصل على مناطق الرسم للعرض.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - قائمة مناطق الرسم التي سيتم عرضها.
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


يضبط مناطق الرسم للعرض.

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | قائمة مناطق الرسم التي سيتم عرضها. |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


يشير إلى ما إذا كان يجب عرض التخطيطات من مستند CAD.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  إذا كان يجب عرض التخطيطات،  false  خلاف ذلك.
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


يضبط ما إذا كان يجب عرض التخطيطات من مستند CAD.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لعرض التخطيطات،  false  خلاف ذلك. |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


يحصل على اسم التخطيط المحدد للعرض. اسم التخطيط حساس لحالة الأحرف.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - اسم التخطيط المحدد للعرض.
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


يضبط اسم التخطيط المحدد للعرض. اسم التخطيط حساس لحالة الأحرف.

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | اسم التخطيط المحدد للعرض. |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


يحصل على طبقات الرسم CAD للعرض.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - طبقات الرسم في CAD.
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


يحصل على طبقات الرسم CAD للعرض.

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | طبقات الرسم في CAD. |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


تعيين هذا العلم إلى true يفعّل وضع تحويل خاص يركز على الأداء لجميع الصيغ ضمن عائلة CAD. في هذا الوضع، تكون سرعة التحويل أسرع بكثير، لكن جودة المستندات الناتجة أسوأ بشكل ملحوظ. بشكل افتراضي، يكون معطلاً (false). جودة المستندات الناتجة هي الأفضل الممكنة على حساب الأداء.

**Returns:**
boolean -  true  إذا كان وضع التحويل الموجه للأداء مفعّلاً،  false  خلاف ذلك.
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


تعيين هذا العلم إلى true يفعّل وضع تحويل خاص يركز على الأداء لجميع الصيغ ضمن عائلة CAD. في هذا الوضع، تكون سرعة التحويل أسرع بكثير، لكن جودة المستندات الناتجة أسوأ بشكل ملحوظ. بشكل افتراضي، يكون معطلاً (false). جودة المستندات الناتجة هي الأفضل الممكنة على حساب الأداء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  لتمكين وضع التحويل الموجه للأداء،  false  لتعطيله. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


يتحقق مما إذا كان كائن CadOptions هذا يساوي كائنًا آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن للمقارنة معه. |

**Returns:**
boolean -  true  إذا كان الكائنان متساويين،  false  خلاف ذلك.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحسب قيمة رمز التجزئة لهذا الكائن. رمز التجزئة يعتمد على الحالة الداخلية للكائن ويُستخدم في هياكل البيانات القائمة على التجزئة مثل خرائط التجزئة ومجموعات التجزئة.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - قيمة رمز التجزئة لهذا الكائن.
### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا لهذا الكائن.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - تمثيل نصي لهذا الكائن.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


يرجع تمثيلًا نصيًا لهذا الكائن.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| النمط | org.apache.commons.lang3.builder.ToStringStyle | نمط ToStringStyle المستخدم لإنشاء التمثيل النصي. |

**Returns:**
java.lang.String - تمثيل نصي لهذا الكائن باستخدام نمط ToStringStyle المحدد.
