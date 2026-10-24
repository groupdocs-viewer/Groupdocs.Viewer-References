---
title: "Sécurité"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des options de sécurité pour les documents PDF."
type: docs
weight: 29
url: /fr/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Fournit des options de sécurité pour les documents PDF.


La classe Security encapsule divers paramètres et options qui peuvent être utilisés pour appliquer des mesures de sécurité
à un document PDF dans le composant GroupDocs.Viewer. Ces options incluent la protection par mot de passe,
les autorisations, et plus encore.
Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


Exemple d'utilisation :

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

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
|  | [Security()](#Security--) | Initialise une nouvelle instance de |
Sécurité
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Obtient le mot de passe requis pour ouvrir le document PDF. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Définit le mot de passe requis pour ouvrir le document PDF. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | Obtient le mot de passe requis pour modifier les paramètres d'autorisation. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Définit le mot de passe requis pour modifier les paramètres d'autorisation. |
|
|  | [getPermissions()](#getPermissions--) | Obtient les autorisations du document PDF telles que l'impression, la modification et l'extraction de données. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | Définit les autorisations du document PDF telles que l'impression, la modification et l'extraction de données. |
|
### Security() {#Security--}
```
public Security()
```


Initialise une nouvelle instance de
Sécurité
classe.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Obtient le mot de passe requis pour ouvrir le document PDF.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - le mot de passe d'ouverture du document.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Définit le mot de passe requis pour ouvrir le document PDF.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le mot de passe d'ouverture du document. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Obtient le mot de passe requis pour modifier les paramètres d'autorisation.


En utilisant un mot de passe d'autorisations, vous pouvez restreindre l'impression, la modification et l'extraction de données.
Utilisez un mot de passe d'autorisations pour restreindre l'impression, la modification et l'extraction de données. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - le mot de passe d'autorisations.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Définit le mot de passe requis pour modifier les paramètres d'autorisation.


En utilisant un mot de passe d'autorisations, vous pouvez restreindre l'impression, la modification et l'extraction de données.
Utilisez un mot de passe d'autorisations pour restreindre l'impression, la modification et l'extraction de données. Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le mot de passe d'autorisations. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Obtient les autorisations du document PDF telles que l'impression, la modification et l'extraction de données.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - les autorisations du document PDF.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Définit les autorisations du document PDF telles que l'impression, la modification et l'extraction de données.


Pour un exemple de code, voir la [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Les autorisations du document PDF. |
|

