---
title: "뷰어"
second_title: "GroupDocs.Viewer for .NET API 참조"
description: "Viewergroupdocs.viewer/viewer 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *getFileStream*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| getLoadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *getFileStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *getLoadOptions*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *getFileStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| getFileStream | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| getLoadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *getFileStream*이 null인 경우 발생합니다. |
| ArgumentNullException | *getLoadOptions*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| leaveOpen | Boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true, 그렇지 않으면 false. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| loadOptions | LoadOptions | 문서 로드 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |
| ArgumentNullException | *loadOptions*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| loadOptions | LoadOptions | 문서 로드 옵션입니다. |
| leaveOpen | Boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true, 그렇지 않으면 false. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |
| ArgumentNullException | *loadOptions*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |
| leaveOpen | Boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true, 그렇지 않으면 false. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| loadOptions | LoadOptions | 문서 로드 옵션입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |
| ArgumentNullException | *loadOptions*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 파일 스트림입니다. |
| loadOptions | LoadOptions | 문서 로드 옵션입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |
| leaveOpen | Boolean | Viewer 객체가 해제된 후 스트림을 열어 두려면 true, 그렇지 않으면 false. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *stream*이 null인 경우 발생합니다. |
| ArgumentNullException | *loadOptions*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(string filePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | *filePath*이 null이거나 비어 있는 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | *filePath*이 null이거나 비어 있는 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 또 보기

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |
| loadOptions | LoadOptions | 파일을 열 때 사용되는 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | *filePath*이 null이거나 비어 있는 경우 발생합니다. |
| ArgumentNullException | *loadOptions*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

[`Viewer`](../../viewer) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 렌더링할 파일의 경로입니다. |
| loadOptions | LoadOptions | 파일을 열 때 사용되는 옵션입니다. |
| settings | ViewerSettings | Viewer 설정입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | *filePath*이 null이거나 비어 있는 경우 발생합니다. |
| ArgumentNullException | *loadOptions*이 null인 경우 발생합니다. |
| ArgumentNullException | *settings*이 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 또 보기

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
