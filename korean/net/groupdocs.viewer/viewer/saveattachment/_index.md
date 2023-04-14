---
title: SaveAttachment
second_title: .NET API 참조용 GroupDocs.Viewer
description: 첨부 파일을 다음에 저장합니다.destination 스트림.
type: docs
weight: 60
url: /ko/net/groupdocs.viewer/viewer/saveattachment/
---
## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

첨부 파일을 다음에 저장합니다.*destination* 스트림.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| attachment | Attachment | 첨부 파일. |
| destination | Stream | 쓰기 가능한 스트림. |
| cancellationToken | CancellationToken | 취소 토큰. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*attachment* null입니다. |
| ArgumentNullException | 언제 던져*destination* null입니다. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 문서를 여는 데 비밀번호가 필요한 경우 발생합니다. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 지정된 비밀번호가 잘못된 경우 발생합니다. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 첨부 파일을 찾을 수 없을 때 발생합니다. |

### 비고

**더 알아보기**

* C#: 에서 문서 첨부 파일 가져오기에 대해 자세히 알아보기[GroupDocs.Viewer를 사용하여 문서 첨부 목록을 가져오는 방법](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* C#에서 문서 첨부 파일 저장에 대해 자세히 알아보기: [GroupDocs.Viewer를 사용하여 문서 첨부 파일을 저장하는 방법](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### 또한보십시오

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## SaveAttachment(Attachment, Stream) {#saveattachment}

첨부 파일을 다음에 저장합니다.*destination* 스트림.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| attachment | Attachment | 첨부 파일. |
| destination | Stream | 쓰기 가능한 스트림. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*attachment* null입니다. |
| ArgumentNullException | 언제 던져*destination* null입니다. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 문서를 여는 데 비밀번호가 필요한 경우 발생합니다. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 지정된 비밀번호가 잘못된 경우 발생합니다. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 첨부 파일을 찾을 수 없을 때 발생합니다. |

### 비고

**더 알아보기**

* C#: 에서 문서 첨부 파일 가져오기에 대해 자세히 알아보기[GroupDocs.Viewer를 사용하여 문서 첨부 목록을 가져오는 방법](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* C#에서 문서 첨부 파일 저장에 대해 자세히 알아보기: [GroupDocs.Viewer를 사용하여 문서 첨부 파일을 저장하는 방법](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### 또한보십시오

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->