---
title: "EmailOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des messages électroniques."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Fournit des options pour le rendu des messages électroniques.

La classe EmailOptions encapsule divers paramètres et réglages qui peuvent être utilisés pour contrôler le rendu des messages électroniques dans le composant GroupDocs.Viewer.

Pour plus de détails, voir la [documentation][].

Exemple d'utilisation :

```

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | Initialise une nouvelle instance de la classe  EmailOptions  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Obtient le format de l'heure pour les valeurs de date et d'heure. |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Obtient le format de l'heure pour les valeurs de date et d'heure. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Obtient le décalage du fuseau horaire pour le message. |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Obtient le décalage en minutes du fuseau horaire pour le message. |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Obtient le décalage du fuseau horaire pour le message. |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Obtient le décalage en minutes du fuseau horaire pour le message. |
| [getPageSize()](#getPageSize--) | Obtient la taille de la page de sortie. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Obtient la taille de la page de sortie. |
| [getFieldTextMap()](#getFieldTextMap--) | Récupère le mappage entre les champs du message électronique et leurs représentations textuelles. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Définit le mappage entre les champs du message électronique et leurs représentations textuelles. |
| [equals(Object o)](#equals-java.lang.Object-) | Remplace la méthode equals() de la classe Object. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Remplace la méthode toString() de la classe Object. |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Initialise une nouvelle instance de la classe  EmailOptions  . Ce constructeur est utilisé pour créer une nouvelle instance de la classe  EmailOptions  avec les paramètres par défaut.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Obtient le format de l'heure pour les valeurs de date et d'heure.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - le format de l'heure pour les valeurs de date et d'heure.
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Obtient le format de l'heure pour les valeurs de date et d'heure.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | Le format de l'heure pour les valeurs de date et d'heure. |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Obtient le décalage du fuseau horaire pour le message.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - le décalage du fuseau horaire.
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Obtient le décalage en minutes du fuseau horaire pour le message.

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - le décalage du fuseau horaire.
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Obtient le décalage du fuseau horaire pour le message.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | Le décalage du fuseau horaire. |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Obtient le décalage en minutes du fuseau horaire pour le message.

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| offsetMinutes | int | Le décalage du fuseau horaire. |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Obtient la taille de la page de sortie.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Obtient la taille de la page de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | La taille de la page. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Récupère le mappage entre les champs du message électronique et leurs représentations textuelles.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - le mappage entre les champs du message électronique et leurs représentations textuelles.
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Définit le mappage entre les champs du message électronique et leurs représentations textuelles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | Le mappage entre les champs des messages électroniques et leurs représentations textuelles. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Remplace la méthode equals() de la classe Object.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'objet à comparer. |

**Returns:**
boolean - vrai si les objets sont égaux, faux sinon.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcule la valeur du code de hachage pour cet objet. Le code de hachage est basé sur l'état interne de l'objet et est utilisé dans les structures de données basées sur le hachage telles que les tables de hachage et les ensembles de hachage.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - la valeur du code de hachage pour cet objet.
### toString() {#toString--}
```
public String toString()
```


Remplace la méthode toString() de la classe Object.

**Returns:**
java.lang.String - une représentation sous forme de chaîne de l'objet.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Renvoie une représentation sous forme de chaîne de cet objet.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| style | org.apache.commons.lang3.builder.ToStringStyle | Le ToStringStyle à utiliser pour générer la représentation sous forme de chaîne. |

**Returns:**
java.lang.String - une représentation sous forme de chaîne de cet objet en utilisant le ToStringStyle spécifié.
