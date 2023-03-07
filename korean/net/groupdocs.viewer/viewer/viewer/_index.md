---
title: Viewer
second_title: .NET API 참조용 GroupDocs.Viewer
description: 의 새 인스턴스를 초기화합니다.Viewergroupdocs.viewer/viewer 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| getLoadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |
| ArgumentNullException | 언제 던져*getLoadOptions* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| settings | ViewerSettings | 뷰어 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| getLoadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |
| settings | ViewerSettings | 뷰어 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*getFileStream* null입니다. |
| ArgumentNullException | 언제 던져*getLoadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| leaveOpen | Boolean | 진실 Viewer 개체가 삭제된 후 스트림을 열어 두려면; 그렇지 않으면,거짓. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| loadOptions | LoadOptions | 문서 로드 옵션. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| loadOptions | LoadOptions | 문서 로드 옵션. |
| leaveOpen | Boolean | 진실 Viewer 개체가 삭제된 후 스트림을 열어 두려면; 그렇지 않으면,거짓. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| settings | ViewerSettings | 뷰어 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| settings | ViewerSettings | 뷰어 설정입니다. |
| leaveOpen | Boolean | 진실 Viewer 개체가 삭제된 후 스트림을 열어 두려면; 그렇지 않으면,거짓. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| loadOptions | LoadOptions | 문서 로드 옵션. |
| settings | ViewerSettings | 뷰어 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| loadOptions | LoadOptions | 문서 로드 옵션. |
| settings | ViewerSettings | 뷰어 설정입니다. |
| leaveOpen | Boolean | 진실 Viewer 개체가 삭제된 후 스트림을 열어 두려면; 그렇지 않으면,거짓. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*stream* null입니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 언제 던져*filePath* null이거나 비어 있습니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |
| settings | ViewerSettings | 뷰어 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 언제 던져*filePath* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또한보십시오

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |
| loadOptions | LoadOptions | 파일을 여는 데 사용된 옵션입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 언제 던져*filePath* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

의 새 인스턴스를 초기화합니다.[`Viewer`](../../viewer) 클래스.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |
| loadOptions | LoadOptions | 파일을 여는 데 사용된 옵션입니다. |
| settings | ViewerSettings | 뷰어 설정입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 언제 던져*filePath* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*loadOptions* null입니다. |
| ArgumentNullException | 언제 던져*settings* null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Viewer에서 지원하는 파일 유형에 대한 추가 정보: [GroupDocs.Viewer에서 지원하는 문서 형식](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET용 GroupDocs.Viewer 기능에 대한 추가 정보: [개발자 가이드](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* .NET용 GroupDocs.Viewer: 를 사용하여 타사 저장소에서 암호화된 문서를 로드하고 파일을 보는 방법에 대해 자세히 알아보십시오.[GroupDocs.Viewer로 문서를 로드하고 보는 방법](https://docs.groupdocs.com/display/viewernet/Loading)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 네임스페이스 [GroupDocs.Viewer](../../viewer)
* 집회 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
