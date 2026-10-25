---
title: "FromStream"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।"
type: docs
weight: 2000
url: /hi/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```csharp
public static FileType FromStream(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |

### संबंधित देखें

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```csharp
public static FileType FromStream(Stream stream, string password)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| password | String | फ़ाइल खोलने के लिए पासवर्ड। |

### संबंधित देखें

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| लॉगर | ILogger | लॉगर। |

### वापसी मान

फ़ाइल प्रकार लौटाता है यदि इसे सफलतापूर्वक पहचाना गया हो, अन्यथा डिफ़ॉल्ट [`Unknown`](../unknown) फ़ाइल प्रकार लौटाता है।

### संबंधित देखें

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| password | String | फ़ाइल खोलने के लिए पासवर्ड। |
| लॉगर | ILogger | लॉगर। |

### वापसी मान

फ़ाइल प्रकार लौटाता है यदि इसे सफलतापूर्वक पहचाना गया हो, अन्यथा डिफ़ॉल्ट [`Unknown`](../unknown) फ़ाइल प्रकार लौटाता है।

### संबंधित देखें

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
