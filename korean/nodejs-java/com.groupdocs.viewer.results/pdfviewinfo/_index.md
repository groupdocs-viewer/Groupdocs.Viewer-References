---
title: "PdfViewInfo"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "PDF 문서에 대한 보기 정보를 나타냅니다."
type: docs
weight: 22
url: /ko/nodejs-java/com.groupdocs.viewer.results/pdfviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface PdfViewInfo extends ViewInfo
```

PDF 문서에 대한 보기 정보를 나타냅니다.

PdfViewInfo 인터페이스는 GroupDocs.Viewer 구성 요소에서 PDF 문서에 대한 보기 정보를 액세스하고 조작하기 위한 계약을 정의합니다. 이 인터페이스는 인쇄 허용과 같은 정보를 검색하는 메서드 및 기타 속성을 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     final PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is PdfViewInfoImpl.*
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isPrintingAllowed()](#isPrintingAllowed--) | 문서 인쇄가 허용되는지 확인합니다. |
| [setPrintingAllowed(boolean allowPrinting)](#setPrintingAllowed-boolean-) | 문서 인쇄 허용 여부를 설정합니다. |
### isPrintingAllowed() {#isPrintingAllowed--}
```
public abstract boolean isPrintingAllowed()
```


문서 인쇄가 허용되는지 확인합니다.

**Returns:**
boolean - 인쇄가 허용되면 true, 허용되지 않으면 false.
### setPrintingAllowed(boolean allowPrinting) {#setPrintingAllowed-boolean-}
```
public abstract void setPrintingAllowed(boolean allowPrinting)
```


문서 인쇄 허용 여부를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| allowPrinting | boolean | true는 인쇄를 허용하고, false는 그렇지 않습니다. |

