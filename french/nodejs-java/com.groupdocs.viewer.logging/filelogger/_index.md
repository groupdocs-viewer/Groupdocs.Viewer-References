---
title: "FileLogger"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Écrit les messages de journal dans un fichier."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Écrit les messages de journal dans un fichier.

La classe  FileLogger  fournit des fonctionnalités pour écrire des messages de journal dans un fichier. Elle implémente l'interface ILogger et peut être utilisée pour consigner divers événements et messages dans une application. Les messages de journal sont écrits dans le fichier spécifié.

Exemple d'utilisation :

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Crée un logger qui enregistre les messages dans un fichier spécifié par le nom de fichier fourni. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Crée un logger qui enregistre les messages dans un fichier avec des niveaux de journalisation spécifiés. |
## Champs

| Champ | Description |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Écrit un message de trace dans la console. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal de trace dans la console. |
| [isTraceEnabled()](#isTraceEnabled--) | Vérifie si le niveau de trace est activé pour la journalisation. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Écrit un message de journal de débogage dans la console. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal de débogage dans la console. |
| [isDebugEnabled()](#isDebugEnabled--) | Vérifie si le niveau de débogage est activé pour la journalisation. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'avertissement dans la console. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'avertissement dans la console. |
| [isWarningEnabled()](#isWarningEnabled--) | Vérifie si le niveau d'avertissement est activé pour la journalisation. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'erreur dans la console. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'erreur dans la console. |
| [isErrorEnabled()](#isErrorEnabled--) | Vérifie si la journalisation de niveau erreur est activée. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Crée un logger qui enregistre les messages dans un fichier spécifié par le nom de fichier fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom complet du fichier avec le chemin. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Crée un logger qui enregistre les messages dans un fichier avec des niveaux de journalisation spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom complet du fichier avec le chemin. |
| isTraceEnabled | boolean | Spécifie si la journalisation au niveau trace est activée. |
| isDebugEnabled | boolean | Spécifie si la journalisation au niveau débogage est activée. |
| isWarningEnabled | boolean | Spécifie si la journalisation au niveau avertissement est activée. |
| isErrorEnabled | boolean | Spécifie si la journalisation au niveau erreur est activée. |

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


Écrit un message de trace dans la console. Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message de trace. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre de passage. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal de trace sur la console. Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | L'exception associée au message de journal de trace. |
| message | java.lang.String | Le message de journal de trace. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Vérifie si le niveau de trace est activé pour la journalisation.

**Returns:**
booléen -  true  si le niveau de trace est activé,  false  sinon.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Écrit un message de journal de débogage sur la console. Les messages de journal de débogage fournissent des informations sur différents processus du flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message de journal de débogage. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal de débogage sur la console. Les messages de journal de débogage fournissent des informations sur différents processus du flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | L'exception associée au message de journal de débogage. |
| message | java.lang.String | Le message de journal de débogage. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Vérifie si le niveau de débogage est activé pour la journalisation.

**Returns:**
booléen -  true  si le niveau de débogage est activé,  false  sinon.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Écrit un message de journal d'avertissement sur la console. Les messages de journal d'avertissement fournissent des informations sur des événements inattendus et récupérables dans le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message de journal d'avertissement. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal d'avertissement sur la console. Les messages de journal d'avertissement fournissent des informations sur des événements inattendus et récupérables dans le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | L'exception associée au message de journal d'avertissement. |
| message | java.lang.String | Le message de journal d'avertissement. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Vérifie si le niveau d'avertissement est activé pour la journalisation.

**Returns:**
booléen -  true  si le niveau d'avertissement est activé,  false  sinon.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Écrit un message de journal d'erreur sur la console. Les messages de journal d'erreur fournissent des informations sur des événements irrécupérables dans le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message de journal d'erreur. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal d'erreur sur la console. Les messages de journal d'erreur fournissent des informations sur des événements irrécupérables dans le flux de l'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| throwable | java.lang.Throwable | L'exception associée au message de journal d'erreur. |
| message | java.lang.String | Le message de journal d'erreur. |
| arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés \{\} dans l'ordre où ils sont fournis. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Vérifie si la journalisation de niveau erreur est activée.

**Returns:**
booléen -  true  si la journalisation de niveau erreur est activée,  false  sinon.
