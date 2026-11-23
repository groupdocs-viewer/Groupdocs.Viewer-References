---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von Outlook‑Datendateien bereit."
type: docs
weight: 20
url: /de/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Stellt Optionen zum Rendern von Outlook‑Datendateien bereit.


Die OutlookOptions-Klasse kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um das Rendering von Outlook-Datendateien (wie PST- oder OST-Dateien) in der GroupDocs.Viewer-Komponente zu steuern.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Beispielverwendung:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFolder()](#getFolder--) | Ermittelt den Namen des Ordners, der gerendert werden soll. |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | Legt den Namen des Ordners fest, der gerendert werden soll. |
|
|  | [getTextFilter()](#getTextFilter--) | Liest die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden. |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Liest die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Liest die E‑Mail‑Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird. |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Setzt die E‑Mail‑Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird. |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Ermittelt die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können. |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Legt die maximale Anzahl von Nachrichten oder Elementen fest, die aus einem Ordner gerendert werden können. |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Ermittelt den Namen des Ordners, der gerendert werden soll.
Der Name des Ordners (z. B. Posteingang, Gesendete Elemente oder Gelöschte Elemente), der gerendert werden soll.


Beim Rendern einer Outlook-Datendatei rendert GroupDocs.Viewer Nachrichten aus allen im Datei enthaltenen Ordnern (einschließlich verschachtelter Ordner). Verwenden Sie diese Eigenschaft, um Elemente aus einem bestimmten Ordner zu rendern.
Ein Codebeispiel finden Sie in dieser [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Returns:**
java.lang.String - der Name des Ordners, der gerendert werden soll.

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Legt den Namen des Ordners fest, der gerendert werden soll.
Der Name des Ordners (z. B. Posteingang, Gesendete Elemente oder Gelöschte Elemente), der gerendert werden soll.


Beim Rendern einer Outlook-Datendatei rendert GroupDocs.Viewer Nachrichten aus allen im Datei enthaltenen Ordnern (einschließlich verschachtelter Ordner). Verwenden Sie diese Eigenschaft, um Elemente aus einem bestimmten Ordner zu rendern.
Ein Codebeispiel finden Sie in dieser [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Der Name des Ordners, der gerendert werden soll. |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Liest die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden.


Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text im Betreff oder im Textkörper enthalten. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - die Schlüsselwörter.

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Liest die Schlüsselwörter, die zum Filtern von Nachrichten verwendet werden.


Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text im Betreff oder im Textkörper enthalten. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Die Schlüsselwörter. |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Liest die E‑Mail‑Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird.


Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text in der Absender\\ufffds- oder Empfänger\\ufffds-Adresse enthalten. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Returns:**
java.lang.String - die E-Mail-Adresse, die zum Filtern von Nachrichten verwendet wird.

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Setzt die E‑Mail‑Adresse, die zum Filtern von Nachrichten nach Absender oder Empfänger verwendet wird.


Verwenden Sie diese Eigenschaft, um alle Nachrichten zu rendern, die einen bestimmten Text in der Absender\\ufffds- oder Empfänger\\ufffds-Adresse enthalten. Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.lang.String | Die E-Mail-Adresse, die zum Filtern von Nachrichten verwendet wird. |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Ermittelt die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können.


Outlook-Datendateien können groß sein und das Abrufen aller Nachrichten kann erhebliche Zeit in Anspruch nehmen.
Diese Einstellung begrenzt die maximale Anzahl von Nachrichten oder Elementen (wie Kontakte und Aufgaben), die gerendert werden.
Der Standardwert ist 50. Setzen Sie den Wert auf 0, um alle Nachrichten zu rendern.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Returns:**
int - die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können.

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Legt die maximale Anzahl von Nachrichten oder Elementen fest, die aus einem Ordner gerendert werden können.


Outlook-Datendateien können groß sein und das Abrufen aller Nachrichten kann erhebliche Zeit in Anspruch nehmen.
Diese Einstellung begrenzt die maximale Anzahl von Nachrichten oder Elementen (wie Kontakte und Aufgaben), die gerendert werden.
Der Standardwert ist 50. Setzen Sie den Wert auf 0, um alle Nachrichten zu rendern.
Für ein Codebeispiel siehe die [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | int | Die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können. |
|

