---
title: "ArchiveSecurityOptions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Classe pouvant être utilisée pour limiter le processus d'extraction des archives."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Classe pouvant être utilisée pour limiter le processus d'extraction des archives.

La classe ArchiveSecurityOptions offre un moyen de limiter l'extraction des archives et d'appliquer certaines restrictions.

Exemple d'utilisation :

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

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Cette option spécifie la longueur maximale qu'un nom d'entrée d'archive peut avoir. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Définit la longueur maximale autorisée pour les noms d'entrées d'archive. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Récupère la taille maximale autorisée pour les entrées d'archive. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Définit la taille maximale autorisée pour les entrées d'archive. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Récupère le nombre maximal autorisé d'entrées dans une archive. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Définit le nombre maximal autorisé d'entrées dans une archive. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Spécifie le taux de compression maximal autorisé pour l'extraction des entrées d'archive. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Spécifie le taux de compression maximal autorisé pour l'extraction des entrées d'archive. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Cette option spécifie la longueur maximale qu'un nom d'entrée d'archive peut avoir.
Si un nom d'entrée dépasse cette limite, cela provoquera une erreur.


***Note:** The default value for this option is 255.*


**Returns:**
int - la longueur maximale autorisée pour les noms d'entrées d'archive.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Définit la longueur maximale autorisée pour les noms d'entrées d'archive.
La longueur maximale autorisée spécifie la limite de la longueur d'un nom d'entrée d'archive.
Si la longueur d'un nom d'entrée dépasse cette limite, cela provoquera une erreur.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | La longueur maximale du nom d'entrée d'archive à définir. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Récupère la taille maximale autorisée pour les entrées d'archive.
La taille maximale autorisée d'une entrée spécifie la limite de la taille d'une entrée d'archive.
Si la taille d'une entrée dépasse cette limite, cela entraînera une erreur.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - la taille maximale d'une entrée d'archive.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Définit la taille maximale autorisée pour les entrées d'archive.
La taille maximale autorisée d'une entrée spécifie la limite de la taille d'une entrée d'archive.
Si la taille d'une entrée dépasse cette limite, cela entraînera une erreur.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | La taille maximale d'une entrée d'archive. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Récupère le nombre maximal autorisé d'entrées dans une archive.
Le nombre maximal d'entrées autorisées spécifie la limite du nombre d'entrées qu'une archive peut contenir.
Si une archive contient plus d'entrées que cette limite, elle ne peut pas être extraite.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - le nombre maximal d'entrées dans une archive.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Définit le nombre maximal autorisé d'entrées dans une archive.
Le nombre maximal d'entrées autorisées spécifie la limite du nombre d'entrées qu'une archive peut contenir.
Si une archive contient plus d'entrées que cette limite, elle ne peut pas être extraite.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Le nombre maximal d'entrées dans une archive. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Spécifie le taux de compression maximal autorisé pour l'extraction des entrées d'archive.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - le taux de compression maximal autorisé pour les entrées d'archive.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Spécifie le taux de compression maximal autorisé pour l'extraction des entrées d'archive.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Le taux de compression maximal autorisé pour les entrées d'archive. |
|

