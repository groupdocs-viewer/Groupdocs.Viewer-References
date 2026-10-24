---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Klasse, die verwendet werden kann, um den Extraktionsvorgang von Archiven zu begrenzen."
type: docs
weight: 11
url: /de/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Klasse, die verwendet werden kann, um den Extraktionsvorgang von Archiven zu begrenzen.

Die ArchiveSecurityOptions-Klasse bietet eine Möglichkeit, die Extraktion von Archiven zu begrenzen und bestimmte Einschränkungen durchzusetzen.

Beispielverwendung:

````

 ArchiveSecurityOptions securityOptions = new ArchiveSecurityOptions();
 securityOptions.setMaxAllowedEntryNameLength(255);
 securityOptions.setMaxAllowedEntrySize(10737418240L);
 securityOptions.setMaxAllowedEntriesCount(1000);
 securityOptions.setMaxAllowedEntryCompressionRatio(100);

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setArchiveSecurityOptions(securityOptions);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** Not each archive type supports all options.*

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Diese Option gibt die maximale Länge an, die ein Archiv-Eintragsname haben kann. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Setzt die maximal zulässige Länge für die Archiv-Eintragsnamen. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Ruft die maximal zulässige Größe für Archiv-Einträge ab. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Setzt die maximal zulässige Größe für Archiv-Einträge. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Ruft die maximal zulässige Anzahl von Einträgen in einem Archiv ab. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Setzt die maximal zulässige Anzahl von Einträgen in einem Archiv. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv-Einträgen an. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv-Einträgen an. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Diese Option gibt die maximale Länge an, die ein Archiv-Eintragsname haben kann.
Wenn ein Eintragsname dieses Limit überschreitet, führt dies zu einem Fehler.


***Note:** The default value for this option is 255.*


**Returns:**
int - die maximal zulässige Länge für die Archiv-Eintragsnamen.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Setzt die maximal zulässige Länge für die Archiv-Eintragsnamen.
Die maximal zulässige Länge gibt das Limit für die Länge eines Archiv-Eintragsnamens an.
Wenn die Länge eines Eintragsnamens dieses Limit überschreitet, führt dies zu einem Fehler.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | Die maximale Länge des Archiv-Eintragsnamens, die festzulegen ist. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Ruft die maximal zulässige Größe für Archiv-Einträge ab.
Die maximal zulässige Eintragsgröße gibt das Limit für die Größe eines Archiv-Eintrags an.
Wenn die Größe eines Eintrags dieses Limit überschreitet, führt dies zu einem Fehler.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - die maximale Größe des Archiv-Eintrags.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Setzt die maximal zulässige Größe für Archiv-Einträge.
Die maximal zulässige Eintragsgröße gibt das Limit für die Größe eines Archiv-Eintrags an.
Wenn die Größe eines Eintrags dieses Limit überschreitet, führt dies zu einem Fehler.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | Die maximale Größe des Archiv-Eintrags. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Ruft die maximal zulässige Anzahl von Einträgen in einem Archiv ab.
Die maximal zulässige Eintragsanzahl gibt das Limit für die Anzahl der Einträge an, die ein Archiv enthalten kann.
Wenn ein Archiv mehr Einträge als dieses Limit enthält, kann es nicht extrahiert werden.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - die maximale Anzahl von Einträgen in einem Archiv.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Setzt die maximal zulässige Anzahl von Einträgen in einem Archiv.
Die maximal zulässige Eintragsanzahl gibt das Limit für die Anzahl der Einträge an, die ein Archiv enthalten kann.
Wenn ein Archiv mehr Einträge als dieses Limit enthält, kann es nicht extrahiert werden.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Die maximale Anzahl von Einträgen in einem Archiv. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv-Einträgen an.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double – das maximal zulässige Kompressionsverhältnis für Archiveinträge.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv-Einträgen an.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Das maximal zulässige Kompressionsverhältnis für Archiveinträge. |
|

