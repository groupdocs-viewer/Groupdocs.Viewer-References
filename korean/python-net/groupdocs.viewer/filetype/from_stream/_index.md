---
title: "from_stream 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 서명을 읽어 파일 유형을 감지합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

파일 서명을 읽어 파일 유형을 감지합니다.

```python
def from_stream(cls, stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |

## from_stream {#stream-password}

파일 서명을 읽어 파일 유형을 감지합니다.

```python
def from_stream(cls, stream, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| password | `str` | 파일을 열기 위한 비밀번호. |

## from_stream {#stream-logger}

파일 서명을 읽어 파일 유형을 감지합니다.

```python
def from_stream(cls, stream, logger):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| logger | `ILogger` | 로거입니다. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

파일 서명을 읽어 파일 유형을 감지합니다.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 파일 스트림입니다. |
| password | `str` | 파일을 열기 위한 비밀번호. |
| logger | `ILogger` | 로거입니다. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### 참고
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
