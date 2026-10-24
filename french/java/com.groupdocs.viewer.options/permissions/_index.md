---
title: "Permissions"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Définit les autorisations des documents PDF."
type: docs
weight: 24
url: /fr/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Définit les autorisations des documents PDF.


La classe Permissions fournit des constantes qui représentent différentes autorisations
qui peuvent être appliquées à un document PDF dans le composant GroupDocs.Viewer.
Ces autorisations contrôlent les actions qui peuvent être effectuées sur le document PDF,
telles que l'impression, la copie de texte, la modification d'annotations, et plus encore.


Exemple d'utilisation :

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Champs

| Champ | Description |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Autoriser l'impression, la modification et l'extraction de données. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Refuser l'impression. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Refuser la modification du contenu, le remplissage de formulaires, l'ajout ou la modification d'annotations. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Refuser l'extraction de texte et de graphiques. |
|
|  | [DENY_ALL](#DENY-ALL) | Refuser l'impression, la modification et l'extraction de données. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Autoriser l'impression, la modification et l'extraction de données.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Refuser l'impression.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Refuser la modification du contenu, le remplissage de formulaires, l'ajout ou la modification d'annotations.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Refuser l'extraction de texte et de graphiques.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Refuser l'impression, la modification et l'extraction de données.


