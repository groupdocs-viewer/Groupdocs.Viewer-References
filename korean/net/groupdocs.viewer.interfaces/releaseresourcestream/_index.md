---
title: ReleaseResourceStream
second_title: .NET API 참조용 GroupDocs.Viewer
description: 연결된 메서드에 의해 인스턴스화된 스트림을 해제합니다.CreateResourceStream./createresourcestream 대리자.
type: docs
weight: 210
url: /ko/net/groupdocs.viewer.interfaces/releaseresourcestream/
---
## ReleaseResourceStream delegate

연결된 메서드에 의해 인스턴스화된 스트림을 해제합니다.[`CreateResourceStream`](../createresourcestream) 대리자.

```csharp
public delegate void ReleaseResourceStream(int pageNumber, Resource resource, 
    Stream resourceStream);
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 페이지 번호입니다. |
| resource | Resource | 글꼴, 스타일, 이미지 또는 그래픽과 같은 HTML 리소스입니다. |
| resourceStream | Stream | 연결된 메서드에 의해 생성된 스트림[`CreateResourceStream`](../createresourcestream) 대리자. |

### 또한보십시오

* class [Resource](../../groupdocs.viewer.results/resource)
* 네임스페이스 [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* 집회 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->