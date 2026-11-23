---
title: "PdfOptimizationOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Используйте этот класс, чтобы указать параметры оптимизации PDF, применяемые к выходному PDF‑файлу."
type: docs
weight: 21
url: /ru/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

Используйте этот класс, чтобы указать параметры оптимизации PDF, применяемые к выходному PDF‑файлу.


Эти параметры оптимизации поддерживаются для любых входных форматов файлов, которые поддерживаются для экспорта в PDF.
Для деталей и примеров кода, смотрите эту [страницу](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) и её дочерние элементы.


Пример использования:

````

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
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Устанавливает значения по умолчанию параметра MaxResolution в 300 и параметра ImageQuality в 100. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | Включает оптимизацию выходного PDF‑файла для онлайн‑просмотра в веб‑браузере. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | Устанавливает, следует ли оптимизировать выходной PDF для онлайн‑просмотра в веб‑браузере. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | Аннотации могут быть удалены, когда они не нужны. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | Устанавливает, следует ли удалять ненужные аннотации из PDF. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | Если PDF‑документ содержит AcroForms, мы можем попытаться уменьшить размер файла, уплощая поля формы. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | Устанавливает, следует ли удалять поля формы из PDF. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF‑файл состоит из текста, изображений, вложений, аннотаций, графиков и других объектов. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | Устанавливает, следует ли преобразовать PDF в градации серого. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | Каждый шрифт, используемый для отображения текста на странице, содержит набор глифов для символов шрифта. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | Устанавливает, следует ли использовать подмножество шрифтов в PDF. |
|
|  | [isCompressImages()](#isCompressImages--) | Если исходный PDF‑файл содержит изображения, рассмотрите возможность их сжатия и установки качества. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | Устанавливает, следует ли сжимать изображения в PDF. |
|
|  | [getImageQuality()](#getImageQuality--) | Если исходный PDF‑файл содержит изображения, рассмотрите возможность их сжатия и установки качества. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | Устанавливает качество изображений при их сжатии в PDF. |
|
|  | [isResizeImages()](#isResizeImages--) | Можно использовать вместе с параметром CompressImages для изменения размера изображений до более низкого разрешения. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | Устанавливает, следует ли изменять размер изображений в PDF. |
|
|  | [getMaxResolution()](#getMaxResolution--) | Можно использовать вместе с параметром CompressImages для изменения размера изображений до более низкого разрешения. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | Устанавливает максимальное разрешение для изменения размера изображений в PDF. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | Оптимизирует границы и шрифты Excel‑таблиц для уменьшения размера выходного файла. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | Устанавливает, следует ли оптимизировать таблицы в PDF. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | Удаляет личную информацию (информация о частях страниц), если установлено значение true. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | Устанавливает, следует ли удалять личную информацию из PDF. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | Если документ использует встроенные шрифты, это означает, что все данные шрифтов размещены в документе. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | Устанавливает, следует ли извлекать встроенные шрифты из PDF. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | Иногда документ содержит несколько одинаковых потоков ресурсов (например, изображения). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | Устанавливает, следует ли связывать дублирующие потоки в PDF. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | Если это свойство установлено в true, содержимое страниц будет повторно использоваться при оптимизации документа для одинаковых страниц. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | Устанавливает, следует ли разрешить повторное использование содержимого страниц в PDF. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | Иногда документ содержит неиспользуемые потоки ресурсов. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | Устанавливает, следует ли удалять неиспользуемые потоки из PDF. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF‑документ иногда содержит PDF‑объекты, которые не имеют ссылок |
из любого другого объекта в документе.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | Устанавливает, следует ли удалять неиспользуемые объекты из PDF. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Устанавливает значения по умолчанию параметра MaxResolution в 300 и параметра ImageQuality в 100.


Для деталей и примеров кода, смотрите эту [страницу](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) и её дочерние элементы.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


Включает оптимизацию выходного PDF‑файла для онлайн‑просмотра в веб‑браузере.


Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
boolean -  true  если выходной PDF оптимизирован для онлайн‑просмотра,  false  в противном случае.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


Устанавливает, следует ли оптимизировать выходной PDF для онлайн‑просмотра в веб‑браузере.


Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | linearize | boolean | true  для оптимизации выходного PDF для онлайн‑просмотра,  false  в противном случае. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


Аннотации можно удалить, когда они не нужны. Когда они нужны, но не требуют дополнительного редактирования, их можно «сплющить». Это уменьшит размер файла.


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
boolean -  true  если аннотации удалены,  false  в противном случае.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


Устанавливает, следует ли удалять ненужные аннотации из PDF.


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  чтобы удалить ненужные аннотации,  false  в противном случае. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


Если PDF‑документ содержит AcroForms, мы можем попытаться уменьшить размер файла, уплощая поля формы.


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
boolean -  true  если поля формы удалены,  false  в противном случае.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


Устанавливает, следует ли удалять поля формы из PDF.


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | removeFormFields | boolean | true  чтобы удалить поля формы,  false  в противном случае. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF‑файл состоит из текста, изображений, вложений, аннотаций, графиков и других объектов.
Возможно, вам понадобится преобразовать PDF из цветового пространства RGB в градации серого, чтобы ускорить печать этих PDF‑файлов.
Также при преобразовании файла в градации серого размер документа уменьшается, но при этом качество документа может ухудшиться.
В настоящее время эта функция поддерживается функцией Pre‑Flight в Adobe Acrobat.


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
boolean -  true  если PDF преобразован в градации серого,  false  в противном случае.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


Устанавливает, следует ли преобразовать PDF в градации серого.


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  чтобы преобразовать PDF в градации серого,  false  в противном случае. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


Каждый шрифт, используемый для отображения текста на странице, содержит набор глифов для символов шрифта.
Спецификация PDF поддерживает "font subset", т.е. шрифт только с теми глифами, которые используются.
Это может вызвать проблемы при обновлении текста (поскольку, вероятно, необходимые глифы отсутствуют в шрифте), но для документа, который не планируется изменять, это позволяет уменьшить размер.


***Note:** The default value is 
false
.*
Если файл использует встроенные шрифты, он содержит все данные шрифта. GroupDocs.Viewer может выполнять субсетинг встроенных шрифтов для уменьшения размера файла. Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
boolean -  true  если шрифты подвергнуты субсетингу,  false  в противном случае.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


Устанавливает, следует ли использовать подмножество шрифтов в PDF.


***Note:** The default value is 
false
.*
Если файл использует встроенные шрифты, он содержит все данные шрифта. GroupDocs.Viewer может выполнять субсетинг встроенных шрифтов для уменьшения размера файла. Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | subsetFonts | boolean | true  чтобы выполнить субсетинг шрифтов,  false  в противном случае. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


Если исходный PDF‑файл содержит изображения, рассмотрите возможность их сжатия и установки качества.
Чтобы включить сжатие изображений, установите эту опцию в true. Все изображения в документе будут повторно сжаты.
Сжатие определяется свойством ImageQuality, которое задаёт значение качества в процентах.
100% — это неизменное качество. Чтобы уменьшить качество изображения, установите свойство ImageQuality меньше 100.


***Note:** The default value is 
false
.*
Используйте эту опцию, чтобы разрешить другие параметры сжатия: #setImageQuality(int).setImageQuality(int) and . Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
boolean -  true  если изображения сжаты,  false  в противном случае.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


Устанавливает, следует ли сжимать изображения в PDF.


***Note:** The default value is 
false
.*
Используйте эту опцию, чтобы разрешить другие параметры сжатия: #setImageQuality(int).setImageQuality(int) and . Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | compressImages | boolean | true  чтобы сжать изображения,  false  в противном случае. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


Если исходный PDF‑файл содержит изображения, рассмотрите возможность сжатия изображений и установки их качества. Чтобы включить сжатие изображений, установите параметр CompressImages в значение true. Все изображения в документе будут повторно сжаты. Сжатие определяется свойством ImageQuality, которое задаёт значение качества в процентах. 100 % — это неизменное качество. Чтобы уменьшить качество изображения, установите параметр CompressImages в значение true и свойство ImageQuality меньше 100.

<br />


***Note:** The default value is 
100
.*
Чтобы изменить качество изображения, сначала установите свойство #setCompressImages(boolean).setCompressImages(boolean) в значение true. Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int — качество изображения (значение от 1 до 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


Устанавливает качество изображений при их сжатии в PDF.


***Note:** The default value is 
100
.*
Чтобы изменить качество изображения, сначала установите свойство #setCompressImages(boolean).setCompressImages(boolean) в значение true. Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | imageQuality | int | качество изображения (значение от 1 до 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


Можно использовать вместе с параметром CompressImages для изменения размера изображений до более низкого разрешения.
В этом случае следует установить CompressImage в значение true, ResizeImages в значение true и MaxResolution в соответствующее значение.


***Note:** The default value is 
false
.*
Чтобы включить эту опцию, установите свойство в значение true. Эта опция позволяет задавать свойство. Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean —  true  если изображения изменены в размере,  false  в противном случае.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


Устанавливает, следует ли изменять размер изображений в PDF.


***Note:** The default value is 
false
.*
Чтобы включить эту опцию, установите свойство в значение true. Эта опция позволяет задавать свойство. Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | resizeImages | boolean | true  — для изменения размера изображений,  false  — в противном случае. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


Можно использовать вместе с опцией CompressImages для изменения размера изображений с более низким разрешением. В этом случае следует установить CompressImage в значение true, ResizeImages в значение true и MaxResolution в соответствующее значение.


***Note:** The default value is 
300
.*
Чтобы включить эту опцию, установите свойства #setCompressImages(boolean).setCompressImages(boolean) и #setMaxResolution(int).setMaxResolution(int) в значение true.
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int — максимальное разрешение для изображений.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


Устанавливает максимальное разрешение для изменения размера изображений в PDF.


***Note:** The default value is 
300
.*
Чтобы включить эту опцию, установите свойства #setCompressImages(boolean).setCompressImages(boolean) и #setMaxResolution(int).setMaxResolution(int) в значение true.
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxResolution | int | максимальное разрешение для изображений. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


Оптимизирует границы и шрифты Excel‑таблиц для уменьшения размера выходного файла.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean —  true  если таблицы оптимизированы,  false  в противном случае.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


Устанавливает, следует ли оптимизировать таблицы в PDF.


Для примера кода см. эту [документацию](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  — для оптимизации таблиц,  false  — в противном случае. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


Удаляет личную информацию (информация о частях страниц), если установлено значение true.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если конфиденциальная информация удалена,  false  в противном случае.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


Устанавливает, следует ли удалять личную информацию из PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  — для удаления конфиденциальной информации,  false  — в противном случае. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


Если документ использует встроенные шрифты, это означает, что все данные шрифтов размещены в документе.
Преимущество в том, что документ доступен для просмотра независимо от того, установлен шрифт на машине пользователя\u2019s или нет. Но встраивание шрифтов делает документ больше.
Метод удаления встраиваемых шрифтов удаляет все встроенные шрифты. Это уменьшает размер документа, но документ может стать нечитаемым, если нужный шрифт не установлен.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если встроенные шрифты удалены,  false  в противном случае.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


Устанавливает, следует ли извлекать встроенные шрифты из PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | unembedFonts | boolean | true  для удаления встроенных шрифтов,  false  в противном случае. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


Иногда документ содержит несколько одинаковых потоков ресурсов (например, изображения).
Это может произойти, например, когда документ конкатенируется сам с собой.
Выходной документ содержит две независимые копии одного и того же потока ресурсов.
Мы анализируем все потоки ресурсов и сравниваем их. Если потоки дублируются, они объединяются, то есть остаётся только одна копия, ссылки изменяются соответствующим образом, а копии объекта удаляются.
Иногда это уменьшает размер документа.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если дублирующие потоки связаны,  false  в противном случае.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


Устанавливает, следует ли связывать дублирующие потоки в PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  для связывания дублирующих потоков,  false  в противном случае. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


Если это свойство установлено в true, содержимое страниц будет повторно использоваться при оптимизации документа для одинаковых страниц.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если содержимое страницы переиспользуется,  false  в противном случае.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


Устанавливает, следует ли разрешить повторное использование содержимого страниц в PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  для разрешения переиспользования содержимого страницы,  false  в противном случае. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


Иногда документ содержит неиспользуемые потоки ресурсов.
Эти потоки не являются \u201cнеиспользуемыми объектами\u201d, потому что они находятся в словаре ресурсов страницы\u2019s.
Это может произойти в случаях, когда изображение удалено со страницы, но не из ресурсов страницы.
Также такая ситуация часто возникает, когда страницы извлекаются из документа, и страницы документа имеют \u201cобщие\u201d ресурсы,
то есть один и тот же объект Resources. Содержимое страниц анализируется, чтобы определить, является ли поток ресурса
используется или нет. Неиспользуемые потоки удаляются. Иногда это уменьшает размер документа.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если неиспользуемые потоки удалены,  false  в противном случае.

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


Устанавливает, следует ли удалять неиспользуемые потоки из PDF.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  для удаления неиспользуемых потоков,  false  в противном случае. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


PDF‑документ иногда содержит PDF‑объекты, которые не имеют ссылок
из любого другого объекта в документе. Это может произойти, например,
когда страница удаляется из дерева страниц документа, но сам объект страницы isn\u2019t удалён.
Удаление этих объектов не делает документ недействительным, а наоборот сжимает его.


***Note:** The default value is 
false
.*


**Returns:**
boolean —  true  если неиспользуемые объекты удалены,  false  в противном случае.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


Устанавливает, следует ли удалять неиспользуемые объекты из PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  для удаления неиспользуемых объектов,  false  в противном случае. |
|

