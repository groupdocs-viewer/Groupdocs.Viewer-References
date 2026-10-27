---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Klasse die kan worden gebruikt om het extractieproces van archieven te beperken."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Klasse die kan worden gebruikt om het extractieproces van archieven te beperken.

De ArchiveSecurityOptions-klasse biedt een manier om de extractie van archieven te beperken en bepaalde beperkingen af te dwingen.

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Deze optie specificeert de maximale lengte die een archiefitemnaam kan hebben. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Stelt de maximaal toegestane lengte in voor de namen van archiefitems. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Haalt de maximaal toegestane grootte op voor archiefitems. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Stelt de maximaal toegestane grootte in voor archiefitems. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Haalt het maximaal toegestane aantal items in een archief op. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Stelt het maximaal toegestane aantal items in een archief in. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Specificeert de maximaal toegestane compressieverhouding voor het extraheren van archiefitems. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Specificeert de maximaal toegestane compressieverhouding voor het extraheren van archiefitems. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Deze optie specificeert de maximale lengte die een archiefitemnaam kan hebben. Als een itemnaam deze limiet overschrijdt, zal dit een fout veroorzaken.

***Note:** The default value for this option is 255.*

**Returns:**
int - de maximaal toegestane lengte voor de namen van archiefitems.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Stelt de maximaal toegestane lengte voor de archiefitemnamen in. De maximaal toegestane lengte geeft de limiet aan voor de lengte van een archiefitemnaam. Als de lengte van een itemnaam deze limiet overschrijdt, zal dit een fout veroorzaken.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | De maximale lengte van de archiefitemnaam die moet worden ingesteld. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Haalt de maximaal toegestane grootte voor archiefitems op. De maximaal toegestane itemgrootte geeft de limiet aan voor de grootte van een archiefitem. Als de grootte van een item deze limiet overschrijdt, resulteert dit in een fout.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - de maximale archiefitemgrootte.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Stelt de maximaal toegestane grootte voor archiefitems in. De maximaal toegestane itemgrootte geeft de limiet aan voor de grootte van een archiefitem. Als de grootte van een item deze limiet overschrijdt, resulteert dit in een fout.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxAllowedEntrySize | long | De maximale archiefitemgrootte. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Haalt het maximaal toegestane aantal items in een archief op. Het maximaal toegestane aantal items geeft de limiet aan voor het aantal items dat een archief kan bevatten. Als een archief meer items bevat dan deze limiet, kan het niet worden uitgepakt.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - het maximale aantal items in een archief.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Stelt het maximaal toegestane aantal items in een archief in. Het maximaal toegestane aantal items geeft de limiet aan voor het aantal items dat een archief kan bevatten. Als een archief meer items bevat dan deze limiet, kan het niet worden uitgepakt.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxAllowedEntriesCount | long | Het maximale aantal items in een archief. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Specificeert de maximaal toegestane compressieverhouding voor het extraheren van archiefitems.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - de maximaal toegestane compressieverhouding voor archiefitems.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Specificeert de maximaal toegestane compressieverhouding voor het extraheren van archiefitems.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | De maximaal toegestane compressieverhouding voor archiefitems. |

