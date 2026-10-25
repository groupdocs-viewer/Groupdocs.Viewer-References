---
title: "ForSplitSheetIntoPages"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions क्लास का एक उदाहरण आरंभ करता है शीट को पृष्ठों में रेंडर करने के लिए।"
type: docs
weight: 50
url: /hi/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

शीट को पृष्ठों में रेंडर करने के लिए [`SpreadsheetOptions`](../../spreadsheetoptions) क्लास का एक उदाहरण आरंभ करता है।

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| countRowsPerPage | Int32 | प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की संख्या। |

### वापसी मान

शीट को पृष्ठों में रेंडर करने के लिए [`SpreadsheetOptions`](../../spreadsheetoptions) क्लास का नया उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *countRowsPerPage* शून्य या उससे कम हो तो फेंका जाता है। |

### टिप्पणियाँ

विवरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### संबंधित देखें

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

शीट को पृष्ठों में रेंडर करने के लिए [`SpreadsheetOptions`](../../spreadsheetoptions) क्लास का एक उदाहरण आरंभ करता है।

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| countRowsPerPage | Int32 | प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की संख्या। |
| countColumnsPerPage | Int32 | प्रत्येक पृष्ठ में शामिल करने के लिए स्तंभों की संख्या। |

### वापसी मान

शीट को पृष्ठों में रेंडर करने के लिए [`SpreadsheetOptions`](../../spreadsheetoptions) क्लास का नया उदाहरण।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *countRowsPerPage* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब *countColumnsPerPage* शून्य या उससे कम हो तो फेंका जाता है। |

### टिप्पणियाँ

विवरण के लिए, देखें [दस्तावेज़](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### संबंधित देखें

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
