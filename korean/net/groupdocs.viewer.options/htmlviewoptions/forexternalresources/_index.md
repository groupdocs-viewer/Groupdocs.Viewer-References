---
title: ForExternalResources
second_title: .NET API 참조용 GroupDocs.Viewer
description: 의 새 인스턴스를 초기화합니다.HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.
type: docs
weight: 20
url: /ko/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| createResourceStream | CreateResourceStream | 에 의해 생성된 스트림을 해제하는 방법*createPageStream* 방법. |
| createResourceUrl | CreateResourceUrl | HTML 리소스에 대한 URL을 생성하는 메서드입니다. |

### 반환 값

새 인스턴스[`HtmlViewOptions`](../../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*createPageStream* null입니다. |
| ArgumentNullException | 언제 던져*createResourceStream* null입니다. |
| ArgumentNullException | 언제 던져*createResourceUrl* null입니다. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 집회 [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| createResourceStream | CreateResourceStream | 출력 HTML 리소스 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 메서드입니다. |
| createResourceUrl | CreateResourceUrl | HTML 리소스에 대한 URL을 생성하는 메서드입니다. |
| releasePageStream | ReleasePageStream | 에 전달된 대리자에게 할당된 메서드에 의해 생성된 스트림을 해제하는 메서드*createPageStream* 매개변수. |
| releaseResourceStream | ReleaseResourceStream | 에 전달된 대리자에게 할당된 메서드에 의해 생성된 스트림을 해제하는 메서드*createResourceStream* 매개변수. |

### 반환 값

새 인스턴스[`HtmlViewOptions`](../../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*createPageStream* null입니다. |
| ArgumentNullException | 언제 던져*createResourceStream* null입니다. |
| ArgumentNullException | 언제 던져*createResourceUrl* null입니다. |
| ArgumentNullException | 언제 던져*releasePageStream* null입니다. |
| ArgumentNullException | 언제 던져*releaseResourceStream* null입니다. |

### 또한보십시오

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 집회 [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 출력 페이지 스트림을 만들고 해제하기 위한 메서드를 구현하는 팩터리입니다. |
| resourceStreamFactory | IResourceStreamFactory | 리소스 URL 생성, 출력 HTML 리소스 스트림 인스턴스화 및 릴리스에 필요한 메서드를 구현하는 팩터리입니다. |

### 반환 값

새 인스턴스[`HtmlViewOptions`](../../htmlviewoptions) 외부 리소스를 사용하여 HTML로 렌더링하기 위한 클래스입니다.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*pageStreamFactory* null입니다. |
| ArgumentNullException | 언제 던져*resourceStreamFactory* null입니다. |

### 또한보십시오

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 집회 [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../../htmlviewoptions) 클래스.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### 비고

이 생성자는 다음의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../../htmlviewoptions) - 출력 HTML 파일의 파일 경로 형식으로 "p_{0}.html" 사용; - 출력 HTML 리소스 파일의 파일 경로 형식으로 "p_{0}_{1}" 사용; - " 사용 p_{0}_{1}" HTML 리소스의 URL 형식으로; 출력 파일은 애플리케이션의 현재 작업 디렉토리에 배치됩니다.

### 또한보십시오

* class [HtmlViewOptions](../../htmlviewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 집회 [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

의 새 인스턴스를 초기화합니다.[`HtmlViewOptions`](../../htmlviewoptions) 클래스.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePathFormat | String | 파일 경로 형식(예: 'page_{0}.html'). |
| resourceFilePathFormat | String | 리소스 파일 경로 형식(예: 'page_{0}/resource_{1}'). |
| resourceUrlFormat | String | 리소스 URL 형식(예: 'page_{0}/resource_{1}'). |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 언제 던져*filePathFormat* null이거나 비어 있습니다. |
| ArgumentException | 언제 던져*resourceFilePathFormat* null이거나 비어 있습니다. |
| ArgumentException | 언제 던져*resourceUrlFormat* null이거나 비어 있습니다. |

### 또한보십시오

* class [HtmlViewOptions](../../htmlviewoptions)
* 네임스페이스 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 집회 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
