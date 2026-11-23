---
title: "طريقة from_stream"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يكشف عن نوع الملف بقراءة توقيع الملف."
type: docs
url: /ar/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

يكشف عن نوع الملف بقراءة توقيع الملف.

```python
def from_stream(cls, stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |

## from_stream {#stream-password}

يكشف عن نوع الملف بقراءة توقيع الملف.

```python
def from_stream(cls, stream, password):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| password | `str` | كلمة المرور لفتح الملف. |

## from_stream {#stream-logger}

يكشف عن نوع الملف بقراءة توقيع الملف.

```python
def from_stream(cls, stream, logger):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| logger | `ILogger` | المسجل. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

يكشف عن نوع الملف بقراءة توقيع الملف.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | `io.RawIOBase` | دفق الملف. |
| password | `str` | كلمة المرور لفتح الملف. |
| logger | `ILogger` | المسجل. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### انظر أيضًا
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
