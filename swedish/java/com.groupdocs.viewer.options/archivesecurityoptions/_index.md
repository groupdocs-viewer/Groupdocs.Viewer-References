---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Klass som kan användas för att begränsa extraktionsprocessen för arkiv."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Klass som kan användas för att begränsa extraktionsprocessen för arkiv.

Klassen ArchiveSecurityOptions tillhandahåller ett sätt att begränsa extrahering av arkiv och upprätthålla vissa restriktioner.

Exempel på användning:

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

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Detta alternativ specificerar den maximala längden som ett arkivpostnamn kan ha. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Ställer in den maximala tillåtna längden för arkivpostnamnen. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Hämtar den maximala tillåtna storleken för arkivposter. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Ställer in den maximala tillåtna storleken för arkivposter. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Hämtar det maximala tillåtna antalet poster i ett arkiv. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Ställer in det maximala tillåtna antalet poster i ett arkiv. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Specificerar den maximala komprimeringsgrad som är tillåten för att extrahera arkivposter. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Specificerar den maximala komprimeringsgrad som är tillåten för att extrahera arkivposter. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Detta alternativ specificerar den maximala längden som ett arkivpostnamn kan ha.
Om ett postnamn överskrider denna gräns kommer det att orsaka ett fel.


***Note:** The default value for this option is 255.*


**Returns:**
int - den maximala tillåtna längden för arkivpostnamnen.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Ställer in den maximala tillåtna längden för arkivpostnamnen.
Den maximala tillåtna längden specificerar gränsen för längden på ett arkivpostnamn.
Om längden på ett postnamn överskrider denna gräns kommer det att orsaka ett fel.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | Den maximala längden för arkivpostnamn som ska sättas. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Hämtar den maximala tillåtna storleken för arkivposter.
Den maximala tillåtna poststorleken specificerar gränsen för storleken på en arkivpost.
Om storleken på en post överskrider denna gräns kommer det att resultera i ett fel.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - den maximala storleken på ett arkivinlägg.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Ställer in den maximala tillåtna storleken för arkivposter.
Den maximala tillåtna poststorleken specificerar gränsen för storleken på en arkivpost.
Om storleken på en post överskrider denna gräns kommer det att resultera i ett fel.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | Den maximala storleken på ett arkivinlägg. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Hämtar det maximala tillåtna antalet poster i ett arkiv.
Det maximala tillåtna antalet poster anger gränsen för hur många poster ett arkiv kan innehålla.
Om ett arkiv innehåller fler poster än denna gräns kan det inte extraheras.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - det maximala antalet poster i ett arkiv.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Ställer in det maximala tillåtna antalet poster i ett arkiv.
Det maximala tillåtna antalet poster anger gränsen för hur många poster ett arkiv kan innehålla.
Om ett arkiv innehåller fler poster än denna gräns kan det inte extraheras.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Det maximala antalet poster i ett arkiv. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Specificerar den maximala komprimeringsgrad som är tillåten för att extrahera arkivposter.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - det maximala tillåtna komprimeringsförhållandet för arkivinlägg.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Specificerar den maximala komprimeringsgrad som är tillåten för att extrahera arkivposter.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Det maximala tillåtna komprimeringsförhållandet för arkivinlägg. |
|

