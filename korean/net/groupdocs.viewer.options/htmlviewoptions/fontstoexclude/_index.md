---
title: FontsToExclude
second_title: .NET API 참조용 GroupDocs.Viewer
description: HTML 문서에서 제외할 글꼴 이름 목록입니다.
type: docs
weight: 40
url: /ko/net/groupdocs.viewer.options/htmlviewoptions/fontstoexclude/
---
## HtmlViewOptions.FontsToExclude property

HTML 문서에서 제외할 글꼴 이름 목록입니다.

```csharp
public List<string> FontsToExclude { get; set; }
```

### 비고

이 옵션은 프리젠테이션에만 지원됩니다. HTML 문서에 추가된 글꼴은 출력 보기의 안정성을 향상시키고 동시에 렌더링 결과의 크기를 증가시킵니다. 이 옵션을 사용하면 안정성과 출력 크기 사이에서 절충안을 찾을 수 있습니다. 널리 사용되고 대부분의 시스템에 설치되는 글꼴 이름 을 포함합니다. 이 속성은 다음 경우에만 활성화됩니다.[`ExcludeFonts`](../excludefonts) 옵션이 비활성화되었습니다.

### 또한보십시오

* class [HtmlViewOptions](../../htmlviewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 집회 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
