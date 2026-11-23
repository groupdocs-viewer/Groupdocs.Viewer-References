---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 Attachment 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

[`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)의 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

새 Attachment 인스턴스를 초기화합니다.

```python
def __init__(self, file_name, file_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | `str` | 첨부 파일 이름. |
| file_path | `str` | 첨부 파일의 상대 경로(예: "folder/file.docx") 또는 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치할 때의 파일 이름. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_path`가 None이거나 비어 있는 경우. |

## __init__ {#id-file_name-file_path-size}

Attachment 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| id | `str` | 첨부 파일의 고유 식별자(단일 파일 컨텍스트에서). |
| file_name | `str` | 첨부 파일 이름. |
| file_path | `str` | 첨부 파일의 상대 경로(예: `folder/file.docx`) 또는 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치할 때의 파일 이름. |
| size | `int` | 첨부 파일의 크기(바이트 단위). |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_path`가 null이거나 비어 있는 경우. |

## __init__ {#id-file_name-file_path-file_type-size}

Attachment 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| id | `str` | 첨부 파일의 고유 식별자(단일 파일 컨텍스트에서). |
| file_name | `str` | 첨부 파일 이름. |
| file_path | `str` | 첨부 파일의 상대 경로(예: `folder/file.docx`) 또는 파일이 아카이브 루트, 이메일 메시지 또는 데이터 파일에 위치할 때의 파일 이름. |
| file_type | `FileType` | 첨부 파일 유형. |
| size | `int` | 첨부 파일의 크기(바이트 단위). |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `file_type`가 null인 경우. |

### 참고
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
