---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Определяет режим переполнения текста при рендеринге электронных таблиц в HTML."
type: docs
weight: 46
url: /ru/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Определяет режим переполнения текста при рендеринге электронных таблиц в HTML.

Перечисление TextOverflowMode представляет различные режимы обработки переполнения текста в компоненте GroupDocs.Viewer. Оно предоставляет набор предопределённых вариантов, которые можно использовать для управления отображением текста, когда он превышает доступное пространство в ячейках при рендеринге электронных таблиц в HTML. Подробности см. в [documentation][].

Пример использования:

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
## Поля

| Поле | Описание |
| --- | --- |
| [OVERLAY](#OVERLAY) | Перекрывать следующие ячейки, даже если они не пусты. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Перекрывать следующие ячейки только если они пусты. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Расширять столбцы, чтобы вместить текст. |
| [HIDE_TEXT](#HIDE-TEXT) | Скрывать переполненный текст. |
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Перекрывать следующие ячейки, даже если они не пусты. Этот режим позволяет тексту переполняться в соседние ячейки независимо от их содержимого.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Перекрывать следующие ячейки только если они пусты. Этот режим позволяет тексту переполняться в соседние ячейки только в том случае, если эти ячейки пусты.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Расширять столбцы, чтобы вместить текст. Этот режим автоматически регулирует ширину столбцов, чтобы разместить переполняющийся текст.

Для получения подробностей см. [документацию][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Скрывать переполненный текст. Этот режим скрывает переполняющийся текст, не позволяя ему отображаться.

Для получения подробностей см. [документацию][].


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
