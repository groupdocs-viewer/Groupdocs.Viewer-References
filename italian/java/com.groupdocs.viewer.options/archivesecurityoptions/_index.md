---
title: "ArchiveSecurityOptions"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Classe che può essere utilizzata per limitare il processo di estrazione degli archivi."
type: docs
weight: 11
url: /it/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Classe che può essere utilizzata per limitare il processo di estrazione degli archivi.

La classe ArchiveSecurityOptions fornisce un modo per limitare l'estrazione degli archivi e applicare alcune restrizioni.

Esempio di utilizzo:

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

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Questa opzione specifica la lunghezza massima che un nome di voce dell'archivio può avere. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Imposta la lunghezza massima consentita per i nomi delle voci dell'archivio. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Recupera la dimensione massima consentita per le voci dell'archivio. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Imposta la dimensione massima consentita per le voci dell'archivio. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Recupera il conteggio massimo consentito di voci in un archivio. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Imposta il conteggio massimo consentito di voci in un archivio. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Specifica il rapporto di compressione massimo consentito per l'estrazione delle voci dell'archivio. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Specifica il rapporto di compressione massimo consentito per l'estrazione delle voci dell'archivio. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Questa opzione specifica la lunghezza massima che un nome di voce dell'archivio può avere.
Se un nome di voce supera questo limite, causerà un errore.


***Note:** The default value for this option is 255.*


**Returns:**
int - la lunghezza massima consentita per i nomi delle voci dell'archivio.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Imposta la lunghezza massima consentita per i nomi delle voci dell'archivio.
La lunghezza massima consentita specifica il limite per la lunghezza di un nome di voce dell'archivio.
Se la lunghezza di un nome di voce supera questo limite, causerà un errore.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | La lunghezza massima del nome della voce dell'archivio da impostare. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Recupera la dimensione massima consentita per le voci dell'archivio.
La dimensione massima consentita della voce specifica il limite per la dimensione di una voce dell'archivio.
Se la dimensione di una voce supera questo limite, si verificherà un errore.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - la dimensione massima dell'elemento dell'archivio.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Imposta la dimensione massima consentita per le voci dell'archivio.
La dimensione massima consentita della voce specifica il limite per la dimensione di una voce dell'archivio.
Se la dimensione di una voce supera questo limite, si verificherà un errore.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | La dimensione massima dell'elemento dell'archivio. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Recupera il conteggio massimo consentito di voci in un archivio.
Il conteggio massimo consentito di voci specifica il limite per il numero di voci che un archivio può contenere.
Se un archivio contiene più voci di questo limite, non può essere estratto.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - il conteggio massimo di voci in un archivio.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Imposta il conteggio massimo consentito di voci in un archivio.
Il conteggio massimo consentito di voci specifica il limite per il numero di voci che un archivio può contenere.
Se un archivio contiene più voci di questo limite, non può essere estratto.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Il conteggio massimo di voci in un archivio. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Specifica il rapporto di compressione massimo consentito per l'estrazione delle voci dell'archivio.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - il rapporto di compressione massimo consentito per le voci dell'archivio.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Specifica il rapporto di compressione massimo consentito per l'estrazione delle voci dell'archivio.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Il rapporto di compressione massimo consentito per le voci dell'archivio. |
|

