---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "외부 리소스를 사용하여 HTML로 렌더링하기 위해 HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions 클래스의 인스턴스를 초기화합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

외부 리소스를 사용하여 HTML로 렌더링하기 위해 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 인스턴스를 초기화합니다.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| createResourceStream | CreateResourceStream | *createPageStream* 메서드에 의해 생성된 스트림을 해제하는 메서드입니다. |
| createResourceUrl | CreateResourceUrl | HTML 리소스의 URL을 생성하는 메서드입니다. |

### 반환 값

외부 리소스를 사용하여 HTML로 렌더링하기 위한 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 새 인스턴스입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *createPageStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *createResourceStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *createResourceUrl*이 null인 경우 발생합니다. |

### 비고

코드 예제는 [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)를 확인하십시오.

### 또 보기

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

외부 리소스를 사용하여 HTML로 렌더링하기 위해 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 인스턴스를 초기화합니다.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| createResourceStream | CreateResourceStream | 출력 HTML 리소스 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드. |
| createResourceUrl | CreateResourceUrl | HTML 리소스의 URL을 생성하는 메서드입니다. |
| releasePageStream | ReleasePageStream | *createPageStream* 매개변수에 전달된 대리자에 할당된 메서드가 만든 스트림을 해제하는 메서드. |
| releaseResourceStream | ReleaseResourceStream | *createResourceStream* 매개변수에 전달된 대리자에 할당된 메서드가 만든 스트림을 해제하는 메서드. |

### 반환 값

외부 리소스를 사용하여 HTML로 렌더링하기 위한 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 새 인스턴스입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *createPageStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *createResourceStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *createResourceUrl*이 null인 경우 발생합니다. |
| ArgumentNullException | *releasePageStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *releaseResourceStream*이 null인 경우 발생합니다. |

### 비고

코드 예제는 [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)를 확인하십시오.

### 또 보기

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

외부 리소스를 사용하여 HTML로 렌더링하기 위해 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 인스턴스를 초기화합니다.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 출력 페이지 스트림을 생성하고 해제하는 메서드를 구현하는 팩터리. |
| resourceStreamFactory | IResourceStreamFactory | 리소스 URL을 생성하고, 출력 HTML 리소스 스트림을 인스턴스화 및 해제하는 데 필요한 메서드를 구현하는 팩터리. |

### 반환 값

외부 리소스를 사용하여 HTML로 렌더링하기 위한 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 새 인스턴스입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *pageStreamFactory*가 null인 경우 발생합니다. |
| ArgumentNullException | *resourceStreamFactory*가 null인 경우 발생합니다. |

### 비고

코드 예제는 [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)를 확인하십시오.

### 또 보기

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

[`HtmlViewOptions`](../../htmlviewoptions) 클래스의 인스턴스를 초기화합니다.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### 비고

이 생성자는 [`HtmlViewOptions`](../../htmlviewoptions) 클래스의 인스턴스를 초기화합니다.

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

출력 파일은 애플리케이션의 현재 작업 디렉터리에 배치됩니다.

코드 예제는 [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)를 확인하십시오.

### 또 보기

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) 클래스의 인스턴스를 초기화합니다.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | String | 파일 경로 형식 예: 'page_{0}.html'. |
| resourceFilePathFormat | String | 리소스 파일 경로 형식 예: 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | 리소스 URL 형식 예: 'page_{0}/resource_{1}'. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | *filePathFormat*이 null이거나 비어 있는 경우 발생합니다. |
| ArgumentException | *resourceFilePathFormat*이 null이거나 비어 있는 경우 발생합니다. |
| ArgumentException | *resourceUrlFormat*이 null이거나 비어 있을 때 발생합니다. |

### 비고

코드 예제는 [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)를 확인하십시오.

### 또 보기

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
