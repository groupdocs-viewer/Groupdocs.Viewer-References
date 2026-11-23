---
title: "View"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "전체 문서 페이지의 뷰를 생성합니다."
type: docs
weight: 90
url: /ko/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

전체 문서 페이지의 뷰를 생성합니다.

```csharp
public void View(ViewOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | ViewOptions | 뷰 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *options* 가 null인 경우 발생합니다. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 문서를 열기 위해 비밀번호가 필요할 때 발생합니다. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 지정된 비밀번호가 올바르지 않을 때 발생합니다. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 첨부 파일을 찾을 수 없는 경우 발생합니다. |

### 비고

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 또 보기

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

전체 문서 페이지의 뷰를 생성합니다.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | ViewOptions | 뷰 옵션입니다. |
| cancellationToken | CancellationToken | 현재 뷰 프로세스를 취소하기 위한 요청을 보내는 취소 토큰입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *options* 가 null인 경우 발생합니다. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 문서를 열기 위해 비밀번호가 필요할 때 발생합니다. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 지정된 비밀번호가 올바르지 않을 때 발생합니다. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 첨부 파일을 찾을 수 없는 경우 발생합니다. |

### 비고

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 또 보기

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

특정 문서 페이지의 뷰를 생성합니다.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | ViewOptions | 뷰 옵션입니다. |
| pageNumbers | Int32[] | 볼 페이지 번호입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *options* 가 null인 경우 발생합니다. |
| ArgumentNullException | *pageNumbers* 가 null인 경우 발생합니다. |
| ArgumentException | *pageNumbers* 가 비어 있는 경우 발생합니다. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 문서를 열기 위해 비밀번호가 필요할 때 발생합니다. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 지정된 비밀번호가 올바르지 않을 때 발생합니다. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 첨부 파일을 찾을 수 없는 경우 발생합니다. |

### 비고

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 또 보기

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

특정 문서 페이지의 뷰를 생성합니다.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | ViewOptions | 뷰 옵션입니다. |
| pageNumbers | CancellationToken | 볼 페이지 번호입니다. |
| cancellationToken | Int32[] | 처리 취소를 위한 취소 토큰입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *options* 가 null인 경우 발생합니다. |
| ArgumentNullException | *pageNumbers* 가 null인 경우 발생합니다. |
| ArgumentException | *pageNumbers* 가 비어 있는 경우 발생합니다. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 문서를 열기 위해 비밀번호가 필요할 때 발생합니다. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 지정된 비밀번호가 올바르지 않을 때 발생합니다. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 첨부 파일을 찾을 수 없는 경우 발생합니다. |

### 비고

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### 또 보기

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
