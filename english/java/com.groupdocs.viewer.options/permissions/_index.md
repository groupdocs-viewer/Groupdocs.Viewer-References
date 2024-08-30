---
title: Permissions
second_title: GroupDocs.Viewer for Java API Reference
description: Defines PDF document permissions.
type: docs
weight: 24
url: /java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Defines PDF document permissions.

The Permissions class provides constants that represent different permissions that can be applied to a PDF document in the GroupDocs.Viewer component. These permissions control the actions that can be performed on the PDF document, such as printing, copying text, modifying annotations, and more.

Example usage:

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
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
| [Permissions()](#Permissions--) |  |
## Fields

| Field | Description |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | Allow printing, modification, and data extraction. |
| [DENY_PRINTING](#DENY-PRINTING) | Deny printing. |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | Deny content modification, filling in forms, adding or modifying annotations. |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Deny text and graphics extraction. |
| [DENY_ALL](#DENY-ALL) | Deny printing, modification, and data extraction. |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Allow printing, modification, and data extraction.

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Deny printing.

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Deny content modification, filling in forms, adding or modifying annotations.

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Deny text and graphics extraction.

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Deny printing, modification, and data extraction.

