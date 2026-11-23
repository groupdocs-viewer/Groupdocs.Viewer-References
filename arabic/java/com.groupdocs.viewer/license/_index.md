---
title: "الترخيص"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر طرقًا لترخيص المكوّن وإلغاء قفل وظائفه الكاملة."
type: docs
weight: 10
url: /ar/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

يوفر طرقًا لترخيص المكوّن وإلغاء قفل وظائفه الكاملة.


تسمح لك فئة License بتطبيق ترخيص صالح على مكوّن GroupDocs.Viewer، مما يتيح لك الاستفادة من جميع الميزات وإزالة أي قيود تقييم.


مثال على الاستخدام:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [License()](#License--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | يُرخص المكوّن. |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | يُرخص المكوّن. |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | يُرخص المكوّن. |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | يُرخص المكوّن. |
|
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


يُرخص المكوّن.


المثال التالي يوضح كيفية تعيين ترخيص بتمرير InputStream لملف الترخيص.


لمزيد من المعلومات حول الترخيص، يرجى الرجوع إلى
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
يمكنك أيضًا العثور على معلومات مفصلة حول ترخيص GroupDocs.Viewer في
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | دفق الترخيص. |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


يُرخص المكوّن.


يضبط الترخيص للمكوّن باستخدام مسار الترخيص المحدد.


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | مسار الترخيص. |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


يُرخص المكوّن.


يجب استدعاء هذه الطريقة قبل استخدام أي وظيفة.


مثال على الاستخدام:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licensePath | java.lang.String | مسار الترخيص أو URL. |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


يُرخص المكوّن.


يجب استدعاء هذه الطريقة قبل استخدام أي وظيفة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | licenseUri | java.net.URL | URI الترخيص. |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
