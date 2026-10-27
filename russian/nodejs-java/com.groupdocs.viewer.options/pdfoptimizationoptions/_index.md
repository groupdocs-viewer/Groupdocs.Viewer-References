---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Используйте этот класс, чтобы указать параметры оптимизации PDF, применяемые к выходному PDF‑файлу."
type: docs
weight: 21
url: /ru/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Используйте этот класс, чтобы указать параметры оптимизации PDF, применяемые к выходному PDF‑файлу.

Эти параметры оптимизации поддерживаются для всех форматов входных файлов, которые поддерживаются для экспорта в PDF. Для подробностей и примеров кода см. эту [page][] и её дочерние элементы.

Пример использования:

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
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Устанавливает значения по умолчанию для параметра MaxResolution равным 300 и параметра ImageQuality равным 100. |
## Методы

| Метод | Описание |
| --- | --- |
| [isLinearize()](#isLinearize--) | Включает оптимизацию выходного PDF‑файла для просмотра онлайн в веб‑браузере. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | Устанавливает, следует ли оптимизировать выходной PDF для онлайн‑просмотра в веб‑браузере. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | Аннотации могут быть удалены, когда они не нужны. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Устанавливает, следует ли удалять ненужные аннотации из PDF. |
| [isRemoveFormFields()](#isRemoveFormFields--) | Если PDF‑документ содержит AcroForms, мы можем попытаться уменьшить размер файла, уплощая поля форм. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Устанавливает, следует ли удалять поля форм из PDF. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF‑файл состоит из текста, изображений, вложений, аннотаций, графиков и других объектов. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Устанавливает, следует ли преобразовать PDF в градации серого. |
| [isSubsetFonts()](#isSubsetFonts--) | Каждый шрифт, используемый для отображения текста на странице, содержит набор глифов для символов шрифта. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Устанавливает, следует ли создавать подмножества шрифтов в PDF. |
| [isCompressImages()](#isCompressImages--) | Если исходный PDF‑файл содержит изображения, рекомендуется сжать их и установить их качество. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Устанавливает, следует ли сжимать изображения в PDF. |
| [getImageQuality()](#getImageQuality--) | Если исходный PDF‑файл содержит изображения, рекомендуется сжать их и установить их качество. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | Устанавливает качество изображений при их сжатии в PDF. |
| [isResizeImages()](#isResizeImages--) | Можно использовать вместе с параметром CompressImages для изменения размера изображений до более низкого разрешения. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Устанавливает, следует ли изменять размер изображений в PDF. |
| [getMaxResolution()](#getMaxResolution--) | Можно использовать вместе с параметром CompressImages для изменения размера изображений до более низкого разрешения. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Устанавливает максимальное разрешение при изменении размера изображений в PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Оптимизировать границы и шрифты таблиц Excel для уменьшения размера выходного файла. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Устанавливает, следует ли оптимизировать таблицы в PDF. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Удалять личную информацию (данные о частях страниц), если установлено значение true. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Устанавливает, следует ли удалять личную информацию из PDF. |
| [isUnembedFonts()](#isUnembedFonts--) | Если документ использует встроенные шрифты, это означает, что все данные шрифтов размещены в документе. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Устанавливает, следует ли извлекать встроенные шрифты из PDF. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Иногда документ содержит несколько одинаковых потоков ресурсов (например, изображения). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Устанавливает, следует ли связывать дублирующие потоки в PDF. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | Если это свойство установлено в true, содержимое страниц будет повторно использоваться при оптимизации документа для одинаковых страниц. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Устанавливает, разрешено ли повторное использование содержимого страниц в PDF. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Иногда документ содержит неиспользуемые потоки ресурсов. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Устанавливает, следует ли удалять неиспользуемые потоки из PDF. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF‑документ иногда содержит объекты PDF, которые не ссылаются ни на один другой объект в документе. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Устанавливает, следует ли удалять неиспользуемые объекты из PDF. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Устанавливает значения по умолчанию для параметра MaxResolution равным 300 и параметра ImageQuality равным 100.

Для получения подробностей и примеров кода см. эту [page][] и её дочерние элементы.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Включает оптимизацию выходного PDF‑файла для просмотра онлайн в веб‑браузере.

Для примера кода см. эту [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  если выходной PDF оптимизирован для онлайн‑просмотра,  false  в противном случае.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Устанавливает, следует ли оптимизировать выходной PDF для онлайн‑просмотра в веб‑браузере.

Для примера кода см. эту [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| linearize | boolean | true  для оптимизации выходного PDF для онлайн‑просмотра,  false  в противном случае. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Аннотации можно удалить, когда они не нужны. Когда они нужны, но не требуют дополнительного редактирования, их можно уплощать. Это уменьшит размер файла.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  если аннотации удалены,  false  в противном случае.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Устанавливает, следует ли удалять ненужные аннотации из PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| removeAnnotations | boolean | true  для удаления ненужных аннотаций,  false  в противном случае. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Если PDF‑документ содержит AcroForms, мы можем попытаться уменьшить размер файла, уплощая поля форм.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  если поля формы удалены,  false  в противном случае.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Устанавливает, следует ли удалять поля форм из PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| removeFormFields | boolean | true  для удаления полей формы,  false  в противном случае. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF‑файл состоит из текста, изображений, вложений, аннотаций, графиков и других объектов. Вы можете столкнуться с требованием конвертировать PDF из цветового пространства RGB в градации серого, чтобы ускорить печать таких PDF‑файлов. При конвертации в градации серого также уменьшается размер документа, однако при этом может пострадать качество. В настоящее время эта функция поддерживается функцией Pre‑Flight в Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  если PDF конвертирован в градации серого,  false  в противном случае.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Устанавливает, следует ли преобразовать PDF в градации серого.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| convertToGrayScale | boolean | true  для конвертации PDF в градации серого,  false  в противном случае. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Каждый шрифт, используемый для отображения текста на странице, содержит набор глифов для символов шрифта. Спецификация PDF поддерживает «подмножество шрифта», т.е. шрифт только с теми глифами, которые используются. Это может вызвать проблемы, когда требуется обновить текст (поскольку необходимые глифы могут отсутствовать в шрифте), но для документа, который не планируется изменять, это позволяет уменьшить размер.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  если шрифты подмножены,  false  в противном случае.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Устанавливает, следует ли создавать подмножества шрифтов в PDF.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subsetFonts | boolean | true  для подмножества шрифтов,  false  в противном случае. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Если исходный PDF‑файл содержит изображения, рассмотрите возможность сжатия изображений и установки их качества. Чтобы включить сжатие изображений, установите эту опцию в true. Все изображения в документе будут повторно сжаты. Сжатие определяется свойством ImageQuality, которое задаёт значение качества в процентах. 100 % — неизменное качество. Чтобы уменьшить качество изображения, установите свойство ImageQuality меньше 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  если изображения сжаты,  false  иначе.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Устанавливает, следует ли сжимать изображения в PDF.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| compressImages | boolean | true  чтобы сжать изображения,  false  иначе. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Если исходный PDF‑файл содержит изображения, рассмотрите возможность сжатия изображений и установки их качества. Чтобы включить сжатие изображений, установите опцию CompressImages в true. Все изображения в документе будут повторно сжаты. Сжатие определяется свойством ImageQuality, которое задаёт значение качества в процентах. 100 % — неизменное качество. Чтобы уменьшить качество изображения, установите опцию CompressImages в true и свойство ImageQuality меньше 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - качество изображения (значение от 1 до 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Устанавливает качество изображений при их сжатии в PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageQuality | int | качество изображения (значение от 1 до 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Можно использовать вместе с опцией CompressImages для изменения размера изображений с более низким разрешением. В этом случае следует установить CompressImage в true, ResizeImages в true и MaxResolution в соответствующее значение.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  если изображения изменены в размере,  false  иначе.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Устанавливает, следует ли изменять размер изображений в PDF.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| resizeImages | boolean | true  чтобы изменить размер изображений,  false  иначе. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Можно использовать вместе с опцией CompressImages для изменения размера изображений с более низким разрешением. В этом случае следует установить CompressImage в true, ResizeImages в true и MaxResolution в соответствующее значение.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - максимальное разрешение для изображений.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Устанавливает максимальное разрешение при изменении размера изображений в PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxResolution | int | максимальное разрешение для изображений. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Оптимизировать границы и шрифты таблиц Excel для уменьшения размера выходного файла.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  если таблицы оптимизированы,  false  иначе.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Устанавливает, следует ли оптимизировать таблицы в PDF.

Для примера кода см. эту [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  чтобы оптимизировать таблицы,  false  иначе. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Удалять личную информацию (данные о частях страниц), если установлено значение true.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  если конфиденциальная информация удалена,  false  иначе.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Устанавливает, следует ли удалять личную информацию из PDF.

***Note:** The default value is  false .*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| removePrivateInfo | boolean | true  чтобы удалить конфиденциальную информацию,  false  иначе. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Если документ использует встроенные шрифты, это означает, что все данные шрифта помещены в документ. Преимущество в том, что документ можно просматривать независимо от того, установлен шрифт на машине пользователя или нет. Но встраивание шрифтов увеличивает размер документа. Метод unembed fonts удаляет все встроенные шрифты. Это уменьшает размер документа, но документ может стать нечитаемым, если нужный шрифт не установлен.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  если встроенные шрифты разъединены,  false  иначе.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Устанавливает, следует ли извлекать встроенные шрифты из PDF.

***Note:** The default value is  false .*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| unembedFonts | boolean | true  чтобы разъединить встроенные шрифты,  false  иначе. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Иногда документ содержит несколько идентичных потоков ресурсов (например изображения). Это может произойти, например, когда документ конкатенируется сам с собой. Выходной документ содержит две независимые копии одного и того же потока ресурсов. Мы анализируем все потоки ресурсов и сравниваем их. Если потоки дублируются, они объединяются, то есть остаётся только одна копия, ссылки изменяются соответствующим образом и копии объекта удаляются. Иногда это уменьшает размер документа.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  если дублированные потоки связаны,  false  в противном случае.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Устанавливает, следует ли связывать дублирующие потоки в PDF.

***Note:** The default value is  false .*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  для связывания дублированных потоков,  false  в противном случае. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Если это свойство установлено в true, содержимое страниц будет повторно использоваться при оптимизации документа для одинаковых страниц.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  если содержимое страницы переиспользуется,  false  в противном случае.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Устанавливает, разрешено ли повторное использование содержимого страниц в PDF.

***Note:** The default value is  false .*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| allowReusePageContent | boolean | true  для разрешения переиспользования содержимого страницы,  false  в противном случае. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Иногда документ содержит неиспользуемые потоки ресурсов. Эти потоки не являются \u201cunused objects\u201d, потому что они находятся в словаре ресурсов страницы. Это может произойти в случаях, когда изображение было удалено со страницы, но не из ресурсов страницы. Кроме того, такая ситуация часто возникает, когда страницы извлекаются из документа, а страницы документа имеют \u201ccommon\u201d ресурсы, то есть один и тот же объект Resources. Содержимое страниц анализируется, чтобы определить, используется поток ресурса или нет. Неиспользуемые потоки удаляются. Иногда это уменьшает размер документа.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  если неиспользуемые потоки удаляются,  false  в противном случае.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Устанавливает, следует ли удалять неиспользуемые потоки из PDF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  для удаления неиспользуемых потоков,  false  в противном случае. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


PDF‑документ иногда содержит PDF‑объекты, которые не ссылаются из любого другого объекта в документе. Это может произойти, например, когда страница удаляется из дерева страниц документа, но сам объект страницы сам isn\u2019t удалён. Удаление этих объектов doesn\u2019t делает документ недействительным, а наоборот уменьшает его.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  если неиспользуемые объекты удаляются,  false  в противном случае.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Устанавливает, следует ли удалять неиспользуемые объекты из PDF.

***Note:** The default value is  false .*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  для удаления неиспользуемых объектов,  false  в противном случае. |

