---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Klasse, die verwendet werden kann, um den Extraktionsvorgang von Archiven zu begrenzen."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Klasse, die verwendet werden kann, um den Extraktionsvorgang von Archiven zu begrenzen.

Die Klasse ArchiveSecurityOptions bietet eine Möglichkeit, das Extrahieren von Archiven zu begrenzen und bestimmte Einschränkungen durchzusetzen.

Beispielhafte Verwendung:

```

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
 
```

***Note:** Not each archive type supports all options.*
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Diese Option gibt die maximale Länge an, die ein Archiv‑Eintragsname haben darf. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Legt die maximal zulässige Länge für die Archiv‑Eintragsnamen fest. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Ruft die maximal zulässige Größe für Archiv‑Einträge ab. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Legt die maximal zulässige Größe für Archiv‑Einträge fest. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Ruft die maximal zulässige Anzahl von Einträgen in einem Archiv ab. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Legt die maximal zulässige Anzahl von Einträgen in einem Archiv fest. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv‑Einträgen an. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv‑Einträgen an. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Diese Option gibt die maximale Länge an, die ein Archiv‑Eintragsname haben darf. Überschreitet ein Eintragsname dieses Limit, führt dies zu einem Fehler.

***Note:** The default value for this option is 255.*

**Returns:**
int - die maximal zulässige Länge für die Archiv‑Eintragsnamen.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Legt die maximal zulässige Länge für die Namen von Archiveinträgen fest. Die maximal zulässige Länge gibt die Grenze für die Länge eines Archiveintragsnamens an. Wenn die Länge eines Eintragsnamens diese Grenze überschreitet, führt dies zu einem Fehler.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | Die maximale Länge des Archiveintragsnamens, die festgelegt werden soll. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Ruft die maximal zulässige Größe für Archiveinträge ab. Die maximal zulässige Eintragsgröße gibt die Grenze für die Größe eines Archiveintrags an. Wenn die Größe eines Eintrags diese Grenze überschreitet, führt dies zu einem Fehler.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - die maximale Größe eines Archiveintrags.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Legt die maximal zulässige Größe für Archiveinträge fest. Die maximal zulässige Eintragsgröße gibt die Grenze für die Größe eines Archiveintrags an. Wenn die Größe eines Eintrags diese Grenze überschreitet, führt dies zu einem Fehler.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxAllowedEntrySize | long | Die maximale Größe eines Archiveintrags. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Ruft die maximal zulässige Anzahl von Einträgen in einem Archiv ab. Die maximal zulässige Eintragsanzahl gibt die Grenze für die Anzahl der Einträge an, die ein Archiv enthalten kann. Wenn ein Archiv mehr Einträge als diese Grenze enthält, kann es nicht extrahiert werden.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - die maximale Anzahl von Einträgen in einem Archiv.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Legt die maximal zulässige Anzahl von Einträgen in einem Archiv fest. Die maximal zulässige Eintragsanzahl gibt die Grenze für die Anzahl der Einträge an, die ein Archiv enthalten kann. Wenn ein Archiv mehr Einträge als diese Grenze enthält, kann es nicht extrahiert werden.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxAllowedEntriesCount | long | Die maximale Anzahl von Einträgen in einem Archiv. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv‑Einträgen an.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - das maximal zulässige Kompressionsverhältnis für Archiveinträge.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Gibt das maximal zulässige Kompressionsverhältnis für das Extrahieren von Archiv‑Einträgen an.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | Das maximal zulässige Kompressionsverhältnis für Archiveinträge. |

