---
title: "ImageQuality"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Качество изображений в выводимом HTML, содержащемся в PDF‑документах."
type: docs
weight: 41
url: /ru/java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

Качество изображений в выводимом HTML, содержащемся в PDF‑документах.


Перечисление ImageQuality представляет качество изображений в выводимом HTML, содержащемся в PDF‑документах
в компоненте GroupDocs.Viewer. Оно предоставляет различные уровни качества изображений, которые могут использоваться
для управления рендерингом и сжатием изображений в сгенерированном HTML‑выводе.


Пример использования:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [LOW](#LOW) | Допустимое качество и лучшая производительность. |
|
|  | [MEDIUM](#MEDIUM) | Лучшее качество и более медленная производительность. |
|
|  | [HIGH](#HIGH) | Наилучшее качество, но медленная производительность. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


Допустимое качество и лучшая производительность.
Эта настройка отдает приоритет скорости рендеринга над качеством изображения.


### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Лучшее качество и более медленная производительность.
Эта настройка обеспечивает баланс между качеством изображения и скоростью рендеринга.


### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


Наилучшее качество, но медленная производительность.
Эта настройка отдает приоритет качеству изображения над скоростью рендеринга.


### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
