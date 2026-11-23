---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Klass som kan användas för att begränsa extraktionsprocessen för arkiv."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Klass som kan användas för att begränsa extraktionsprocessen för arkiv.

Klassen ArchiveSecurityOptions tillhandahåller ett sätt att begränsa extrahering av arkiv och upprätthålla vissa begränsningar.

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Detta alternativ anger den maximala längden som ett arkivpostnamn kan ha. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Ställer in den maximala tillåtna längden för arkivpostnamnen. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Hämtar den maximala tillåtna storleken för arkivposter. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Ställer in den maximala tillåtna storleken för arkivposter. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Hämtar det maximala tillåtna antalet poster i ett arkiv. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Ställer in det maximala tillåtna antalet poster i ett arkiv. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Anger den maximala komprimeringsgrad som tillåts vid extrahering av arkivposter. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Anger den maximala komprimeringsgrad som tillåts vid extrahering av arkivposter. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Detta alternativ anger den maximala längden som ett arkivpostnamn kan ha. Om ett postnamn överskrider denna gräns kommer det att orsaka ett fel.

***Note:** The default value for this option is 255.*

**Returns:**
int - den maximala tillåtna längden för arkivpostnamnen.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Ställer in den maximalt tillåtna längden för arkivpostnamn. Den maximalt tillåtna längden specificerar gränsen för längden på ett arkivpostnamn. Om längden på ett postnamn överstiger denna gräns kommer det att orsaka ett fel.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | Den maximala längden för arkivpostnamn som ska ställas in. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Hämtar den maximalt tillåtna storleken för arkivposter. Den maximalt tillåtna poststorleken specificerar gränsen för storleken på en arkivpost. Om storleken på en post överstiger denna gräns kommer det att resultera i ett fel.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - den maximala storleken för en arkivpost.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Ställer in den maximalt tillåtna storleken för arkivposter. Den maximalt tillåtna poststorleken specificerar gränsen för storleken på en arkivpost. Om storleken på en post överstiger denna gräns kommer det att resultera i ett fel.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxAllowedEntrySize | long | Den maximala storleken för en arkivpost. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Hämtar det maximalt tillåtna antalet poster i ett arkiv. Det maximalt tillåtna antalet poster specificerar gränsen för hur många poster ett arkiv kan innehålla. Om ett arkiv innehåller fler poster än denna gräns kan det inte extraheras.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - det maximala antalet poster i ett arkiv.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Ställer in det maximalt tillåtna antalet poster i ett arkiv. Det maximalt tillåtna antalet poster specificerar gränsen för hur många poster ett arkiv kan innehålla. Om ett arkiv innehåller fler poster än denna gräns kan det inte extraheras.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxAllowedEntriesCount | long | Det maximala antalet poster i ett arkiv. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Anger den maximala komprimeringsgrad som tillåts vid extrahering av arkivposter.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - den maximalt tillåtna komprimeringsgraden för arkivposter.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Anger den maximala komprimeringsgrad som tillåts vid extrahering av arkivposter.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | Den maximalt tillåtna komprimeringsgraden för arkivposter. |

