---
title: "License"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "구성 요소에 라이선스를 부여하고 전체 기능을 활성화하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

구성 요소에 라이선스를 부여하고 전체 기능을 활성화하는 메서드를 제공합니다.

License 클래스는 유효한 라이선스를 GroupDocs.Viewer 구성 요소에 적용할 수 있게 하여 모든 기능을 활용하고 평가 제한을 제거할 수 있게 합니다.

예시 사용법:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | 구성 요소에 라이선스를 적용합니다. |
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


구성 요소에 라이선스를 적용합니다.

다음 예제는 라이선스 파일의 InputStream을 전달하여 라이선스를 설정하는 방법을 보여줍니다.

라이선스에 대한 자세한 정보는 [GroupDocs Licensing FAQ][]을(를) 참조하십시오. 또한 [Evaluation Limitations and Licensing][] 문서에서 GroupDocs.Viewer 라이선스에 대한 자세한 정보를 찾을 수 있습니다.

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseStream | java.io.InputStream | 라이선스 스트림입니다. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


구성 요소에 라이선스를 적용합니다.

지정된 라이선스 경로를 사용하여 구성 요소의 라이선스를 설정합니다.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licensePath | java.nio.file.Path | 라이선스 경로입니다. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


구성 요소에 라이선스를 적용합니다.

이 메서드는 모든 기능을 사용하기 전에 호출되어야 합니다.

예시 사용법:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licensePath | java.lang.String | 라이선스 경로 또는 URL입니다. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


구성 요소에 라이선스를 적용합니다.

이 메서드는 모든 기능을 사용하기 전에 호출되어야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseUri | java.net.URL | 라이선스 URI. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
