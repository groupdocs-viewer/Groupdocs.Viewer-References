---
title: "MemoryCleaner"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Nettoie différentes ressources pour libérer la mémoire."
type: docs
weight: 12
url: /fr/java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

Nettoie différentes ressources pour libérer la mémoire.


Cette classe fournit des méthodes pour libérer la mémoire du tas, supprimer les fichiers temporaires et effacer les informations du registre des polices.
Elle comprend également une méthode pour libérer en toute sécurité les instances locales au thread pour le thread actuel.


Exemple d'utilisation :

````

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [clearKeepingFontSettings()](#clearKeepingFontSettings--) | Libère la mémoire du tas des instances PDF statiques (static et threadLocal) et supprime tous les fichiers temporaires. |
|
|  | [clear()](#clear--) | Libère la mémoire du tas des instances PDF statiques (static et threadLocal) et supprime tous les fichiers temporaires. |
|
|  | [clearStaticInstances()](#clearStaticInstances--) | Libère la mémoire du tas des instances PDF statiques. |
|
|  | [clearAllTempFiles()](#clearAllTempFiles--) | Supprime les fichiers temporaires créés par GroupDocs.Viewer dans le répertoire temporaire du système. |
|
|  | [clearFontRegistry()](#clearFontRegistry--) | Efface les informations du registre des polices de la mémoire du tas. |
|
|  | [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | Libère en toute sécurité la mémoire du tas des instances locales au thread pour le thread actuel. |
|
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


Libère la mémoire du tas des instances PDF statiques (static et threadLocal) et supprime tous les fichiers temporaires.
Cette méthode n'affecte pas les paramètres des polices.


### clear() {#clear--}
```
public static void clear()
```


Libère la mémoire du tas des instances PDF statiques (static et threadLocal) et supprime tous les fichiers temporaires.


### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


Libère la mémoire du tas des instances PDF statiques.


### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


Supprime les fichiers temporaires créés par GroupDocs.Viewer dans le répertoire temporaire du système.


### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


Efface les informations du registre des polices de la mémoire du tas.


### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


Libère en toute sécurité la mémoire du tas des instances locales au thread pour le thread actuel.


