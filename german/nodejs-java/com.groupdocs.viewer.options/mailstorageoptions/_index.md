---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Bietet Optionen zum Rendern von Mail‑Speicher‑Lotus‑Notes‑MBox‑Datendateien."
type: docs
weight: 19
url: /de/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Bietet Optionen zum Rendern von Mail‑Speicher (Lotus Notes, MBox)‑Datendateien.

Die MailStorageOptions‑Klasse kapselt verschiedene Einstellungen und Parameter, die verwendet werden können, um das Rendern von Mail‑Speicher‑Datendateien (wie Lotus Notes oder MBox) in der GroupDocs.Viewer‑Komponente zu steuern.

Weitere Details finden Sie in der [Dokumentation][].

Beispielhafte Verwendung:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Liest die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Legt die Schlüsselwörter fest, die zum Filtern von Nachrichten verwendet werden. |
| [getAddressFilter()](#getAddressFilter--) | Liest die E‑Mail‑Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Legt die E‑Mail‑Adresse fest, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird. |
| [getMaxItems()](#getMaxItems--) | Liest die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden sollen. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Legt die maximale Anzahl von Nachrichten oder Elementen fest, die gerendert werden sollen. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Liest die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden.

Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text im Betreff oder im Textkörper enthalten. Für ein Code‑Beispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String – die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Legt die Schlüsselwörter fest, die zum Filtern von Nachrichten verwendet werden.

Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text im Betreff oder im Textkörper enthalten. Für ein Code‑Beispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textFilter | java.lang.String | Die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Liest die E‑Mail‑Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird.

Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text in der Adresse des Absenders\u2019s oder Empfängers\u2019s enthalten. Für ein Code‑Beispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String – die E‑Mail‑Adresse, die zum Filtern von Nachrichten verwendet wird.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Legt die E‑Mail‑Adresse fest, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird.

Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text in der Adresse des Absenders\u2019s oder Empfängers\u2019s enthalten. Für ein Code‑Beispiel siehe die [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| addressFilter | java.lang.String | Die E‑Mail‑Adresse, die zum Filtern von Nachrichten verwendet wird. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Liest die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden sollen.

Lotus‑Notes‑Datendateien können groß sein, und das Abrufen aller Nachrichten kann erhebliche Zeit in Anspruch nehmen. Diese Einstellung begrenzt die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int – die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden sollen.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Legt die maximale Anzahl von Nachrichten oder Elementen fest, die gerendert werden sollen.

Lotus‑Notes‑Datendateien können groß sein, und das Abrufen aller Nachrichten kann erhebliche Zeit in Anspruch nehmen. Diese Einstellung begrenzt die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxItems | int | Die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden sollen. |

