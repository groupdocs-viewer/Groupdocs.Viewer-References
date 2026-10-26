---
title: "Security"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "PDF 문서 보안 옵션을 제공합니다."
type: docs
weight: 29
url: /ko/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF 문서 보안 옵션을 제공합니다.

Security 클래스는 GroupDocs.Viewer 구성 요소에서 PDF 문서에 보안 조치를 적용하는 데 사용할 수 있는 다양한 설정 및 옵션을 캡슐화합니다. 이러한 옵션에는 비밀번호 보호, 권한 및 기타 기능이 포함됩니다. 자세한 내용은 [documentation][].

예시 사용법:

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


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Security()](#Security--) | Security 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDF 문서를 열기 위해 필요한 비밀번호를 가져옵니다. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDF 문서를 열기 위해 필요한 비밀번호를 설정합니다. |
| [getPermissionsPassword()](#getPermissionsPassword--) | 권한 설정을 변경하기 위해 필요한 비밀번호를 가져옵니다. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | 권한 설정을 변경하기 위해 필요한 비밀번호를 설정합니다. |
| [getPermissions()](#getPermissions--) | PDF 문서 권한(인쇄, 수정 및 데이터 추출 등)을 가져옵니다. |
| [setPermissions(int value)](#setPermissions-int-) | PDF 문서 권한(인쇄, 수정 및 데이터 추출 등)을 설정합니다. |
### Security() {#Security--}
```
public Security()
```


Security 클래스의 새 인스턴스를 초기화합니다.

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDF 문서를 열기 위해 필요한 비밀번호를 가져옵니다.

코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - 문서 열기 비밀번호.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDF 문서를 열기 위해 필요한 비밀번호를 설정합니다.

코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 문서 열기 비밀번호. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


권한 설정을 변경하기 위해 필요한 비밀번호를 가져옵니다.

권한 비밀번호를 사용하면 인쇄, 수정 및 데이터 추출을 제한할 수 있습니다. 권한 비밀번호를 사용하여 인쇄, 수정 및 데이터 추출을 제한합니다. 코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - 권한 비밀번호.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


권한 설정을 변경하기 위해 필요한 비밀번호를 설정합니다.

권한 비밀번호를 사용하면 인쇄, 수정 및 데이터 추출을 제한할 수 있습니다. 권한 비밀번호를 사용하여 인쇄, 수정 및 데이터 추출을 제한합니다. 코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String | 권한 비밀번호. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


PDF 문서 권한(인쇄, 수정 및 데이터 추출 등)을 가져옵니다.

코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - PDF 문서 권한.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


PDF 문서 권한(인쇄, 수정 및 데이터 추출 등)을 설정합니다.

코드 샘플은 [documentation][]을(를) 확인하십시오.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int | PDF 문서 권한. |

