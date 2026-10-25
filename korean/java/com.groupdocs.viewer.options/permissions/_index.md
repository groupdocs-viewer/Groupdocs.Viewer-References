---
title: "Permissions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PDF 문서 권한을 정의합니다."
type: docs
weight: 24
url: /ko/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

PDF 문서 권한을 정의합니다.


Permissions 클래스는 다양한 권한을 나타내는 상수를 제공합니다.
이는 GroupDocs.Viewer 구성 요소에서 PDF 문서에 적용될 수 있습니다.
이러한 권한은 PDF 문서에서 수행할 수 있는 작업을 제어합니다.
예를 들어 인쇄, 텍스트 복사, 주석 수정 등입니다.


사용 예시:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | 인쇄, 수정 및 데이터 추출을 허용합니다. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | 인쇄를 금지합니다. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | 콘텐츠 수정, 양식 입력, 주석 추가 또는 수정을 금지합니다. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | 텍스트 및 그래픽 추출을 금지합니다. |
|
|  | [DENY_ALL](#DENY-ALL) | 인쇄, 수정 및 데이터 추출을 금지합니다. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


인쇄, 수정 및 데이터 추출을 허용합니다.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


인쇄를 금지합니다.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


콘텐츠 수정, 양식 입력, 주석 추가 또는 수정을 금지합니다.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


텍스트 및 그래픽 추출을 금지합니다.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


인쇄, 수정 및 데이터 추출을 금지합니다.


