---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "새 FileCache 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

새 FileCache 인스턴스를 초기화합니다.

```python
def __init__(self, cache_path):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cache_path | `str` | 문서 캐시가 저장될 상대 경로나 절대 경로. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 만약 `cache_path`가 None이면. |

## __init__ {#cache_path-cache_sub_folder}

FileCache 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cache_path | `str` | 문서 캐시가 저장될 상대 경로나 절대 경로. |
| cache_sub_folder | `str` | `cache_path`에 추가할 하위 폴더. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | 만약 `cache_sub_folder`가 None이면. |

### 참고
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
