---
title: "الترخيص"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر طرقًا لترخيص المكوّن وإلغاء قفل وظائفه الكاملة."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن وإلغاء قفل وظائفه الكاملة.

تسمح لك فئة **License** بتطبيق ترخيص صالح على مكوّن **GroupDocs.Viewer**، مما يتيح لك استخدام جميع الميزات وإزالة أي قيود تقييم.

مثال على الاستخدام:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [License()](#License--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | يقوم بترخيص المكوّن. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | يقوم بترخيص المكوّن. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | يقوم بترخيص المكوّن. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | يقوم بترخيص المكوّن. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


يقوم بترخيص المكوّن.

يوضح المثال التالي كيفية تعيين ترخيص بتمرير InputStream لملف الترخيص.

لمزيد من المعلومات حول الترخيص، يرجى الرجوع إلى [الأسئلة الشائعة حول ترخيص GroupDocs][]. يمكنك أيضًا العثور على معلومات مفصلة حول ترخيص **GroupDocs.Viewer** في وثائق [قيود التقييم والترخيص][].

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseStream | java.io.InputStream | دفق الترخيص. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


يقوم بترخيص المكوّن.

يضبط الترخيص للمكوّن باستخدام مسار الترخيص المحدد.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licensePath | java.nio.file.Path | مسار الترخيص. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


يقوم بترخيص المكوّن.

يجب استدعاء هذه الطريقة قبل استخدام أي وظيفة.

مثال على الاستخدام:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licensePath | java.lang.String | مسار الترخيص أو عنوان URL. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


يقوم بترخيص المكوّن.

يجب استدعاء هذه الطريقة قبل استخدام أي وظيفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseUri | java.net.URL | معرف URI للترخيص. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
