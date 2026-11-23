---
title: "ViewerLogger"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Journaliseur global du visualiseur."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Journaliseur global du visualiseur.


Le
ViewerLogger
La classe fournit des fonctionnalités pour consigner des messages dans un journal intégré ou défini par l'utilisateur.
Elle sert de journal global pour le module viewer et peut être utilisée pour consigner divers événements et messages.


Exemple d'utilisation :

````

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
````


***Note:** The 
ViewerLogger
La classe peut être configurée pour utiliser une implémentation de journal personnalisé en appelant la méthode [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger#setLogger-ILogger-).
Par défaut, elle utilise le journal intégré fourni par le module viewer.*

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
|  | [getLogger()](#getLogger--) | Obtient l'instance du journal qui sera utilisée pour consigner les messages. |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Définit l'instance du journal qui sera utilisée pour consigner les messages. |
|
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
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
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


Vérifie si le niveau de trace est activé pour la journalisation.


**Returns:**
booléen -  vrai  si le niveau de trace est activé,  faux  sinon.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
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
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


Vérifie si le niveau de débogage est activé pour la journalisation.


**Returns:**
booléen -  vrai  si le niveau de débogage est activé,  faux  sinon.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
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
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


Vérifie si le niveau d'avertissement est activé pour la journalisation.


**Returns:**
booléen -  vrai  si le niveau d'avertissement est activé,  faux  sinon.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
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
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


Vérifie si la journalisation de niveau erreur est activée.


**Returns:**
booléen -  vrai  si la journalisation au niveau d'erreur est activée,  faux  sinon.

### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Obtient l'instance du journal qui sera utilisée pour consigner les messages.
L'instance du logger peut être utilisée pour consigner des messages de différents niveaux tels que trace, debug, warning et error.


**Returns:**
com.groupdocs.foundation.logging.ILogger - l'instance du logger.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Définit l'instance du journal qui sera utilisée pour consigner les messages.
L'instance du logger peut être utilisée pour consigner des messages de différents niveaux tels que trace, debug, warning et error.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | logger | com.groupdocs.foundation.logging.ILogger | L'instance du logger à définir. |
|

