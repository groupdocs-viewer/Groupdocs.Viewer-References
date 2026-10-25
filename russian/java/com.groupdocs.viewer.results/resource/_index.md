---
title: "Resource"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет HTML-ресурс, такой как шрифт, стиль, изображение или графика."
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Представляет HTML‑ресурс, такой как шрифт, стиль, изображение или графика.


Класс Resource представляет ресурс, используемый при рендеринге HTML в компоненте GroupDocs.Viewer.
Он может представлять различные типы ресурсов, такие как шрифты, стили, изображения или графика, которые включены
или ссылаться в сгенерированном HTML-выводе во время процесса рендеринга.


Пример использования:

````

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Создаёт новый экземпляр |
Resource
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFileName()](#getFileName--) | Возвращает имя файла ресурса. |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | Устанавливает имя файла ресурса. |
|
|  | [isNested()](#isNested--) | Возвращает, находится ли ресурс внутри другого ресурса, например шрифт, находящийся в ресурсе CSS или SVG. |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | Устанавливает, находится ли ресурс внутри другого ресурса. |
|
|  | [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Создаёт новый экземпляр
Resource
класса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Имя файла ресурса. |
|
|  | вложенный | boolean | Указывает, находится ли ресурс внутри другого ресурса, например шрифт, находящийся в ресурсе CSS или SVG. |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Возвращает имя файла ресурса.


**Returns:**
java.lang.String — имя файла ресурса.

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Устанавливает имя файла ресурса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fileName | java.lang.String | Новое имя файла ресурса. |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


Возвращает, находится ли ресурс внутри другого ресурса, например шрифт, находящийся в ресурсе CSS или SVG.


**Returns:**
boolean - Является ли ресурс вложенным в другой ресурс.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Устанавливает, находится ли ресурс внутри другого ресурса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | вложенный | boolean | Должен ли ресурс быть установлен как вложенный. |
|

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.


**Returns:**
java.lang.String - строковое представление текущего объекта.

