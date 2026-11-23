---
title: "OutlookViewInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar vyinformation för en Outlook-datafil."
type: docs
weight: 20
url: /sv/nodejs-java/com.groupdocs.viewer.results/outlookviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface OutlookViewInfo extends ViewInfo
```

Representerar vyinformation för en Outlook-datafil.

OutlookViewInfo-gränssnittet definierar kontraktet för att komma åt och manipulera vyinformation för en Outlook-datafil i GroupDocs.Viewer-komponenten. Det tillhandahåller metoder för att hämta information såsom en lista över mappar och andra egenskaper.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is OutlookViewInfoImpl.*
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFolders()](#getFolders--) | Hämtar listan över mappar som finns i Outlook-datafilen. |
| [setFolders(List<String> list)](#setFolders-java.util.List-java.lang.String--) | Ställer in listan över mappar som finns i Outlook-datafilen. |
### getFolders() {#getFolders--}
```
public abstract List<String> getFolders()
```


Hämtar listan över mappar som finns i Outlook-datafilen.

**Returns:**
java.util.List<java.lang.String> - listan över mappar.
### setFolders(List<String> list) {#setFolders-java.util.List-java.lang.String--}
```
public abstract void setFolders(List<String> list)
```


Ställer in listan över mappar som finns i Outlook-datafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lista | java.util.List<java.lang.String> | listan över mappar. |

