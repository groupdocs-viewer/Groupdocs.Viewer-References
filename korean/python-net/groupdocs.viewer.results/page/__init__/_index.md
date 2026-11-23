---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Page의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

새 인스턴스 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

새 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 인스턴스를 초기화합니다.

```python
def __init__(self, number, visible):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| number | `int` | 페이지 번호입니다. |
| visible | `bool` | 페이지 가시성 표시기. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `number`가 0 이하인 경우. |

## __init__ {#number-name-visible}

새 Page 인스턴스를 초기화합니다.

```python
def __init__(self, number, name, visible):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| number | `int` | 페이지 번호입니다. |
| name | `str` | 워크시트 또는 페이지 이름입니다. |
| visible | `bool` | 페이지 가시성 표시기. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `number`가 0 이하인 경우. |

## __init__ {#number-visible-width-height}

새 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 인스턴스를 초기화합니다.

```python
def __init__(self, number, visible, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| number | `int` | 페이지 번호입니다. |
| visible | `bool` | 페이지 가시성 표시기. |
| width | `int` | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀). |
| height | `int` | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `height`가 0 이하인 경우. |

## __init__ {#number-name-visible-width-height}

새 인스턴스 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)를 초기화합니다.

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| number | `int` | 페이지 번호입니다. |
| name | `str` | 워크시트 또는 페이지 이름입니다. |
| visible | `bool` | 페이지 가시성 표시기. |
| width | `int` | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀). |
| height | `int` | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `height`가 0 이하인 경우. |

## __init__ {#number-visible-width-height-lines}

새 인스턴스 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)를 초기화합니다.

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| number | `int` | 페이지 번호입니다. |
| visible | `bool` | 페이지 가시성 표시기. |
| width | `int` | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀). |
| height | `int` | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)입니다. |
| lines | `List[Line]` | 텍스트 추출이 활성화된 상태에서 JPG 또는 PNG로 볼 때 페이지에 포함된 라인입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `lines`가 None인 경우. |

## __init__ {#number-name-visible-width-height-lines}

새 인스턴스 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)를 초기화합니다.

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| number | `int` | 페이지 번호입니다. |
| name | `str` | 워크시트 또는 페이지 이름입니다. |
| visible | `bool` | 페이지 가시성 표시기. |
| width | `int` | JPG 또는 PNG로 볼 때 페이지의 너비(픽셀). |
| height | `int` | JPG 또는 PNG로 볼 때 페이지의 높이(픽셀)입니다. |
| lines | `List[Line]` | 텍스트 추출이 활성화된 상태에서 JPG 또는 PNG로 볼 때 페이지에 포함된 라인입니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `lines`가 None인 경우. |

### 참고
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
