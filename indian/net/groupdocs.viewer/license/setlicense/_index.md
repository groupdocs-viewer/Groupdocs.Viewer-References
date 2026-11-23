---
title: "SetLicense"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "घटक को लाइसेंस देता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(Stream licenseStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseStream | Stream | लाइसेंस स्ट्रीम। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | *licenseStream* null होने पर फेंका जाता है। |

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि लाइसेंस फ़ाइल की स्ट्रीम पास करके लाइसेंस कैसे सेट किया जाए।

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### संबंधित देखें

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

घटक को लाइसेंस देता है।

```csharp
public void SetLicense(string licensePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licensePath | String | लाइसेंस फ़ाइल पथ। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *licensePath* null या खाली स्ट्रिंग होने पर फेंका जाता है। |

### उदाहरण

निम्नलिखित उदाहरण दिखाता है कि लाइसेंस फ़ाइल के पथ को पास करके लाइसेंस कैसे सेट किया जाए।

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### संबंधित देखें

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
