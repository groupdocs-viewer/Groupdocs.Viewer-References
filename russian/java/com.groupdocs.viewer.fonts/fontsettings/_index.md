---
title: "FontSettings"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет методы для работы с источниками поиска шрифтов TrueType."
type: docs
weight: 12
url: /ru/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Предоставляет методы для работы с источниками поиска шрифтов TrueType.


Класс FontSettings используется для указания и управления источниками, используемыми для поиска TrueType шрифтов.
Он предоставляет методы для добавления и сброса источников шрифтов для API GroupDocs.Viewer.


Пример использования:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Устанавливает источники, в которых ищутся TrueType шрифты при рендеринге документов. |
|
|  | [resetFontSources()](#resetFontSources--) | Сбрасывает ранее установленные источники шрифтов. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Устанавливает источники, в которых ищутся TrueType шрифты при рендеринге документов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Источники шрифтов для установки. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Сбрасывает ранее установленные источники шрифтов.


