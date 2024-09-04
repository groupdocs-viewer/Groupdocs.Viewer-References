---
title: PdfOptimizationOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Use this class to specify PDF optimization options to apply to the output PDF file.
type: docs
weight: 21
url: /nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Use this class to specify PDF optimization options to apply to the output PDF file.

These optimization options are supported for any input file formats which are supported for export to PDF. For details and code samples, see this [page][] and its children.

Example usage:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Sets up default values of MaxResolution option to 300 and ImageQuality option to 100. |
## Methods

| Method | Description |
| --- | --- |
| [isLinearize()](#isLinearize--) | Enables optimization the output PDF file for viewing online with a web browser. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Sets whether to optimize output PDF for online browsing with a web browser. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Annotations can be deleted when they are unnecessary. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Sets whether to remove unnecessary annotations from the PDF. |
| [isRemoveFormFields()](#isRemoveFormFields--) | If the PDF document contains AcroForms, we can try to reduce the file size by flattening form fields. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Sets whether to remove form fields from the PDF. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF file is composed of Text, Image, Attachment, Annotations, Graphs and other objects. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Sets whether to convert the PDF to grayscale. |
| [isSubsetFonts()](#isSubsetFonts--) | Every font used to display text on the page contains set of glyphs for font characters. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Sets whether to subset the fonts in the PDF. |
| [isCompressImages()](#isCompressImages--) | If the source PDF file contains images, consider compressing the images and setting their quality. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Sets whether to compress the images in the PDF. |
| [getImageQuality()](#getImageQuality--) | If the source PDF file contains images, consider compressing the images and setting their quality. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Sets the image quality for compressing the images in the PDF. |
| [isResizeImages()](#isResizeImages--) | Can be used with CompressImages option to resize the images with a lower resolution. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Sets whether to resize the images in the PDF. |
| [getMaxResolution()](#getMaxResolution--) | Can be used with CompressImages option to resize the images with a lower resolution. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Sets the maximum resolution for resizing the images in the PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Optimize Excel spreadsheets border lines and fonts for smaller output file size. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Sets whether to optimize the spreadsheets in the PDF. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Remove private information (page piece info) if set to true. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Sets whether to remove private information from the PDF. |
| [isUnembedFonts()](#isUnembedFonts--) | If the document uses embedded fonts it means that all font data is placed in the document. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Sets whether to unembed the embedded fonts in the PDF. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Sometimes a document contains several identical resource streams (for example images). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Sets whether to link duplicate streams in the PDF. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | If this property is set to true, the page content will be reused when optimizing the document for identical pages. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Sets whether to allow reusing page content in the PDF. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Sometimes a document contains unused resource streams. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Sets whether to remove unused streams from the PDF. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | A PDF document sometimes contains the PDF objects that are not referenced from any other object in the document. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Sets whether to remove unused objects from the PDF. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Sets up default values of MaxResolution option to 300 and ImageQuality option to 100.

For details and code samples, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Enables optimization the output PDF file for viewing online with a web browser.

For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  if the output PDF is optimized for online browsing,  false  otherwise.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Sets whether to optimize output PDF for online browsing with a web browser.

For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| linearize | boolean |  true  to optimize the output PDF for online browsing,  false  otherwise. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Annotations can be deleted when they are unnecessary. When they are needed but do not require additional editing, they can be flattened. It will reduce the file size.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  if annotations are removed,  false  otherwise.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Sets whether to remove unnecessary annotations from the PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeAnnotations | boolean |  true  to remove unnecessary annotations,  false  otherwise. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


If the PDF document contains AcroForms, we can try to reduce the file size by flattening form fields.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  if form fields are removed,  false  otherwise.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Sets whether to remove form fields from the PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeFormFields | boolean |  true  to remove form fields,  false  otherwise. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF file is composed of Text, Image, Attachment, Annotations, Graphs and other objects. You may come across a requirement to convert a PDF from RGB colorspace to grayscale so that it would be faster while printing those PDF files. Also when the file is converted to grayscale, the size of the document is also reduced but with this change, the quality of the document may drop. Currently, this feature is supported by the Pre-Flight feature of Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  if the PDF is converted to grayscale,  false  otherwise.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Sets whether to convert the PDF to grayscale.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertToGrayScale | boolean |  true  to convert the PDF to grayscale,  false  otherwise. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Every font used to display text on the page contains set of glyphs for font characters. PDF specification supports "font subset" i.e. font with only those glyphs which are used. This may cause issues when text should be updated (since probably required glyphs are absent in the font), but for the document which is not planned to change this allows to decrease size.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  if fonts are subsetted,  false  otherwise.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Sets whether to subset the fonts in the PDF.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subsetFonts | boolean |  true  to subset the fonts,  false  otherwise. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


If the source PDF file contains images, consider compressing the images and setting their quality. In order to enable image compression, set this option to true. All the images in a document will be re-compressed. The compression is defined by the ImageQuality property, which is the value of the quality in percent. 100% is unchanged quality. To decrease image quality, set the ImageQuality property less than 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  if images are compressed,  false  otherwise.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Sets whether to compress the images in the PDF.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| compressImages | boolean |  true  to compress the images,  false  otherwise. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


If the source PDF file contains images, consider compressing the images and setting their quality. In order to enable image compression, set CompressImages option to true. All the images in a document will be re-compressed. The compression is defined by the ImageQuality property, which is the value of the quality in percent. 100% is unchanged quality. To decrease image quality, set the CompressImages option to true and ImageQuality property less than 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - the image quality (value between 1 and 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Sets the image quality for compressing the images in the PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageQuality | int | the image quality (value between 1 and 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Can be used with CompressImages option to resize the images with a lower resolution. In this case, we should set CompressImage to true, ResizeImages to true and MaxResolution to the appropriate value.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  if images are resized,  false  otherwise.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Sets whether to resize the images in the PDF.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resizeImages | boolean |  true  to resize the images,  false  otherwise. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Can be used with CompressImages option to resize the images with a lower resolution. In this case, we should set CompressImage to true, ResizeImages to true and MaxResolution to the appropriate value.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - the maximum resolution for the images.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Sets the maximum resolution for resizing the images in the PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxResolution | int | the maximum resolution for the images. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Optimize Excel spreadsheets border lines and fonts for smaller output file size.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  if spreadsheets are optimized,  false  otherwise.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Sets whether to optimize the spreadsheets in the PDF.

For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| optimizeSpreadsheets | boolean |  true  to optimize the spreadsheets,  false  otherwise. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Remove private information (page piece info) if set to true.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if private information is removed,  false  otherwise.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Sets whether to remove private information from the PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removePrivateInfo | boolean |  true  to remove private information,  false  otherwise. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


If the document uses embedded fonts it means that all font data is placed in the document. The advantage is that the document is viewable regardless of whether the font is installed on the user\\u2019s machine or not. But embedding fonts makes the document larger. The unembed fonts method removes all embedded fonts. This decreases the document size but the document may become unreadable if the correct font is not installed.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if embedded fonts are unembedded,  false  otherwise.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Sets whether to unembed the embedded fonts in the PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| unembedFonts | boolean |  true  to unembed the embedded fonts,  false  otherwise. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Sometimes a document contains several identical resource streams (for example images). This may happen for example when a document is concatenated with itself. The output document contains two independent copies of the same resource stream. We analyze all resource streams and compare them. If streams are duplicated they are merged, that is, only one copy is left, references are changed appropriately and copies of the object are removed. Sometimes this decreases the document size.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if duplicate streams are linked,  false  otherwise.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Sets whether to link duplicate streams in the PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| linkDuplicateStreams | boolean |  true  to link duplicate streams,  false  otherwise. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


If this property is set to true, the page content will be reused when optimizing the document for identical pages.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if page content is reused,  false  otherwise.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Sets whether to allow reusing page content in the PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowReusePageContent | boolean |  true  to allow reusing page content,  false  otherwise. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Sometimes a document contains unused resource streams. These streams are not \\u201cunused objects\\u201d because they are referenced from a page\\u2019s resource dictionary. This may happen in cases where an image has been removed from the page but not from the page resources. Also, this situation often occurs when pages are extracted from the document and document pages have \\u201ccommon\\u201d resources, that is, the same Resources object. Page contents are analyzed in order to determine if a resource stream is used or not. Unused streams are removed. Sometimes this decreases the document size.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if unused streams are removed,  false  otherwise.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Sets whether to remove unused streams from the PDF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeUnusedStreams | boolean |  true  to remove unused streams,  false  otherwise. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


A PDF document sometimes contains the PDF objects that are not referenced from any other object in the document. This may happen, for example, when a page is removed from the document page tree but the page object itself isn\\u2019t removed. Removing these objects doesn\\u2019t make the document invalid but rather shrinks it.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  if unused objects are removed,  false  otherwise.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Sets whether to remove unused objects from the PDF.

***Note:** The default value is  false .*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeUnusedObjects | boolean |  true  to remove unused objects,  false  otherwise. |

