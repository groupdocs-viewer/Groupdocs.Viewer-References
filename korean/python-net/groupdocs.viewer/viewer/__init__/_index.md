---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Viewer 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---


## __init__ {#get_file_stream}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다.

자세히 보기

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 메서드. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `get_file_stream`가 None일 때 발생합니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다.

```python
def __init__(self, get_file_stream, get_load_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 메서드. |
| get_load_options | `Func[LoadOptions]` | 문서 로드 옵션을 반환하는 메서드. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `get_load_options`가 None일 때 발생합니다. |
| `Remarks` | - GroupDocs.Viewer에서 지원하는 파일 형식에 대한 자세한 내용: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats - .NET용 GroupDocs.Viewer 기능에 대한 자세한 내용: https://docs.groupdocs.com/display/viewernet/Developer+Guide - .NET용 GroupDocs.Viewer로 암호화된 문서를 로드하고 타사 스토리지에서 파일을 보는 방법에 대한 자세한 내용: https://docs.groupdocs.com/display/viewernet/Loading |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#get_file_stream-settings}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, get_file_stream, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 메서드. |
| settings | `ViewerSettings` | Viewer 설정. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 None일 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#get_file_stream-get_load_options-settings}

새 Viewer 인스턴스를 초기화합니다.

추가 정보:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, get_file_stream, get_load_options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| get_file_stream | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 호출 가능 객체. |
| get_load_options | `Func[LoadOptions]` | 문서 로드 옵션을 반환하는 호출 가능 객체. |
| settings | `ViewerSettings` | Viewer 설정. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `stream`이 None일 때 발생합니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-leave_open}

새 Viewer 인스턴스를 초기화합니다.

자세히 보기:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, leave_open):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| leave_open | `bool` | Viewer 객체가 폐기된 후 스트림을 열어 두려면 True; 그렇지 않으면 False. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `stream`이 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def quick_example():
    """Render a DOCX document to HTML — the hello‑world example."""
    with Viewer("./sample.docx") as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    quick_example()
```

## __init__ {#stream-load_options}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다.

자세히 보기:

- More about file types supported by GroupDocs.Viewer: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats>
- More about GroupDocs.Viewer for .NET features: <https://docs.groupdocs.com/display/viewernet/Developer+Guide>
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: <https://docs.groupdocs.com/display/viewernet/Loading>

```python
def __init__(self, stream, load_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| load_options | `LoadOptions` | 문서 로드 옵션. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `load_options`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-leave_open}

새 Viewer 인스턴스를 초기화합니다.

```python
def __init__(self, stream, load_options, leave_open):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| load_options | `LoadOptions` | 문서 로드 옵션. |
| leave_open | `bool` | Viewer 객체가 폐기된 후 스트림을 열어 두려면 True; 그렇지 않으면 False. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `load_options`가 None인 경우. |
| `Remarks` | - GroupDocs.Viewer에서 지원하는 파일 형식에 대한 자세한 내용: <https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats> - .NET용 GroupDocs.Viewer 기능에 대한 자세한 내용: <https://docs.groupdocs.com/display/viewernet/Developer+Guide> - .NET용 GroupDocs.Viewer로 암호화된 문서를 로드하고 타사 스토리지의 파일을 보는 방법에 대한 자세한 내용: <https://docs.groupdocs.com/display/viewernet/Loading> |

### 예시

```python
import io
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream, loadOptions=None, leaveOpen=False)
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings}

새 Viewer 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, stream, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| settings | `ViewerSettings` | Viewer 설정. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-settings-leave_open}

새 Viewer 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

```python
def __init__(self, stream, settings, leave_open):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| settings | `ViewerSettings` | Viewer 설정. |
| leave_open | `bool` | Viewer 객체가 폐기된 후 스트림을 열어 두려면 True; 그렇지 않으면 False. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 None일 때. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#stream-load_options-settings}

새 Viewer 인스턴스를 초기화합니다.

생성자는 파일 스트림(`io.RawIOBase`)이 필요하며 선택적으로 문서 로드 옵션 및 Viewer 설정을 허용합니다.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| load_options | `LoadOptions` | 문서 로드 옵션. |
| settings | `ViewerSettings` | Viewer 설정. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `stream`, `load_options` 또는 `settings`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer

# 파일을 바이너리 스트림으로 열고 Viewer를 생성합니다.
with open("sample.docx", "rb") as file_stream:
    viewer = Viewer(file_stream)
    # Viewer를 사용합니다, 예: HTML로 렌더링
    # ...
```

## __init__ {#stream-load_options-settings-leave_open}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다.

자세히 보기:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: https://docs.groupdocs.com/display/viewernet/Loading

```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| load_options | `LoadOptions` | 문서 로드 옵션. |
| settings | `ViewerSettings` | Viewer 설정. |
| leave_open | `bool` | Viewer 객체가 폐기된 후 스트림을 열어 두려면 True; 그렇지 않으면 False. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 렌더링할 파일의 경로. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_path`가 None이거나 비어 있는 경우. |

### 예시

```python
from groupdocs.viewer import Viewer

# 문서 경로로 Viewer를 초기화합니다.
with Viewer("./sample.docx") as viewer:
    # viewer가 문서를 렌더링할 준비가 되었습니다.
    pass
```

## __init__ {#file_path-settings}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 클래스의 인스턴스를 초기화합니다.

자세히 보기:

- More about file types supported by GroupDocs.Viewer: https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats
- More about GroupDocs.Viewer for .NET features: https://docs.groupdocs.com/display/viewernet/Developer+Guide

```python
def __init__(self, file_path, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 렌더링할 파일의 경로. |
| settings | `ViewerSettings` | Viewer 설정. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 null인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options}

새 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: Document formats supported by GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: Developer Guide (https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: How to load and view document with GroupDocs.Viewer (https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 렌더링할 파일의 경로. |
| load_options | `LoadOptions` | 파일을 여는 데 사용되는 옵션. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `load_options`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## __init__ {#file_path-load_options-settings}

새 Viewer 인스턴스를 초기화합니다.

- More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
- More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
- More about loading encrypted documents and viewing files from third‑party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_path | `str` | 렌더링할 파일의 경로. |
| load_options | `LoadOptions` | 파일을 여는 데 사용되는 옵션. |
| settings | `ViewerSettings` | Viewer 설정. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `settings`가 None인 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
