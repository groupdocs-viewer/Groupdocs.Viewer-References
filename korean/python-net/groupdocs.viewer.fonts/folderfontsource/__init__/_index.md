---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "FolderFontSource의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

새 인스턴스를 초기화합니다 [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| folder_path | `str` | TrueType 글꼴이 포함된 폴더의 경로. |
| search_option | `SearchOption` | 현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지 지정합니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `folder_path`가 None인 경우. |
| `FileNotFoundError` | `folder_path`에 지정된 경로를 찾을 수 없는 경우. |

### 예시

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 렌더링을 위해 글꼴 소스를 등록합니다
FontSettings.set_font_sources(src1, src2)

# 작업이 끝나면 소스 누수를 방지하기 위해 재설정합니다
FontSettings.reset_font_sources()
```

### 참고
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
