---
title: "FileLogger"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Écrit les messages de journal dans un fichier."
type: docs
weight: 10
url: /fr/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Écrit les messages de journal dans un fichier.


Le
FileLogger
La classe fournit des fonctionnalités pour écrire des messages de journalisation dans un fichier. Elle implémente l'interface ILogger.
et peut être utilisé pour consigner divers événements et messages dans une application. Les messages de journal sont écrits dans le fichier spécifié.


Exemple d'utilisation :

````

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
````


***Note:** The 
FileLogger
La classe fournit une fonctionnalité de journalisation de base.
Vous pouvez étendre cette classe pour ajouter des niveaux de journalisation personnalisés ou des fonctionnalités de journalisation supplémentaires selon vos besoins.*

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Crée un journaliseur qui consigne les messages dans un fichier spécifié par le nom de fichier fourni. |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Crée un journaliseur qui consigne les messages dans un fichier avec des niveaux de journalisation spécifiés. |
|
## Champs

| Champ | Description |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Écrit un message de trace dans la console. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal de trace dans la console. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Vérifie si le niveau de trace est activé pour la journalisation. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Écrit un message de journal de débogage dans la console. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal de débogage dans la console. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Vérifie si le niveau de débogage est activé pour la journalisation. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'avertissement dans la console. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'avertissement dans la console. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Vérifie si le niveau d'avertissement est activé pour la journalisation. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'erreur dans la console. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Écrit un message de journal d'erreur dans la console. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Vérifie si la journalisation de niveau erreur est activée. |
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Crée un journaliseur qui consigne les messages dans un fichier spécifié par le nom de fichier fourni.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileName | java.lang.String | Le nom complet du fichier avec le chemin. |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Crée un journaliseur qui consigne les messages dans un fichier avec des niveaux de journalisation spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileName | java.lang.String | Le nom complet du fichier avec le chemin. |
|
|  | isTraceEnabled | boolean | Spécifie si la journalisation au niveau trace est activée. |
|
|  | isDebugEnabled | boolean | Spécifie si la journalisation au niveau débogage est activée. |
|
|  | isWarningEnabled | boolean | Spécifie si la journalisation au niveau avertissement est activée. |
|
|  | isErrorEnabled | boolean | Spécifie si la journalisation au niveau erreur est activée. |
|

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


Écrit un message de trace dans la console.
Les messages de journal de trace fournissent des informations généralement utiles sur le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message de trace. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre de passage. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal de trace dans la console.
Les messages de journalisation de trace fournissent généralement des informations utiles sur le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'exception associée au message de journalisation de trace. |
|
|  | message | java.lang.String | Le message de journalisation de trace. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Vérifie si le niveau de trace est activé pour la journalisation.


**Returns:**
booléen -  vrai  si le niveau de trace est activé,  faux  sinon.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Écrit un message de journal de débogage dans la console.
Les messages de journalisation de débogage fournissent des informations sur les différents processus du flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message de journalisation de débogage. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal de débogage dans la console.
Les messages de journalisation de débogage fournissent des informations sur les différents processus du flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'exception associée au message de journalisation de débogage. |
|
|  | message | java.lang.String | Le message de journalisation de débogage. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Vérifie si le niveau de débogage est activé pour la journalisation.


**Returns:**
booléen -  vrai  si le niveau de débogage est activé,  faux  sinon.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Écrit un message de journal d'avertissement dans la console.
Les messages de journalisation d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message de journalisation d'avertissement. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal d'avertissement dans la console.
Les messages de journalisation d'avertissement fournissent des informations sur les événements inattendus et récupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'exception associée au message de journalisation d'avertissement. |
|
|  | message | java.lang.String | Le message de journalisation d'avertissement. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Vérifie si le niveau d'avertissement est activé pour la journalisation.


**Returns:**
booléen -  vrai  si le niveau d'avertissement est activé,  faux  sinon.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Écrit un message de journal d'erreur dans la console.
Les messages de journalisation d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Le message de journalisation d'erreur. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Écrit un message de journal d'erreur dans la console.
Les messages de journalisation d'erreur fournissent des informations sur les événements irrécupérables dans le flux de l'application.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | L'exception associée au message de journalisation d'erreur. |
|
|  | message | java.lang.String | Le message de journalisation d'erreur. |
|
|  | arguments | java.lang.Object[] | Les arguments à remplacer dans le message. Ils remplaceront les espaces réservés {} dans l'ordre où ils sont passés. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Vérifie si la journalisation de niveau erreur est activée.


**Returns:**
booléen -  vrai  si la journalisation au niveau d'erreur est activée,  faux  sinon.

