---
title: Security
second_title: GroupDocs.Viewer for Java API Reference
description: Provides PDF document security options.
type: docs
weight: 27
url: /java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Provides PDF document security options.

The Security class encapsulates various settings and options that can be used to apply security measures to a PDF document in the GroupDocs.Viewer component. These options include password protection, permissions, and more.

Example usage:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Security()](#Security--) | Initializes a new instance of the  Security  class. |
## Methods

| Method | Description |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Gets the password required to open the PDF document. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Sets the password required to open the PDF document. |
| [getPermissionsPassword()](#getPermissionsPassword--) | Gets the password required to change permission settings. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Sets the password required to change permission settings. |
| [getPermissions()](#getPermissions--) | Gets the PDF document permissions such as printing, modification, and data extraction. |
| [setPermissions(int value)](#setPermissions-int-) | Sets the PDF document permissions such as printing, modification, and data extraction. |
### Security() {#Security--}
```
public Security()
```


Initializes a new instance of the  Security  class.

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Gets the password required to open the PDF document.

**Returns:**
java.lang.String - the document open password.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Sets the password required to open the PDF document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The document open password. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Gets the password required to change permission settings.

Using a permissions password, you can restrict printing, modification, and data extraction.

**Returns:**
java.lang.String - the permissions password.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Sets the password required to change permission settings.

Using a permissions password, you can restrict printing, modification, and data extraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The permissions password. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Gets the PDF document permissions such as printing, modification, and data extraction.

**Returns:**
int - the PDF document permissions.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Sets the PDF document permissions such as printing, modification, and data extraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The PDF document permissions. |

