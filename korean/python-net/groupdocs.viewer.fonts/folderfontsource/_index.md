---
title: "FolderFontSource 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "TrueType 글꼴을 포함하는 폴더를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

TrueType 글꼴을 포함하는 폴더를 나타냅니다.

FolderFontSource 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | 새 인스턴스를 초기화합니다 [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | 현재 FolderFontSource가 지정된 FolderFontSource 객체와 동일한지 확인합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | 현재 FolderFontSource가 지정된 객체와 동일한지 확인합니다. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | 현재 [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) 객체의 해시 코드를 반환합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | TrueType 글꼴이 포함된 폴더의 경로입니다. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | 현재 폴더만 검색할지, 현재 폴더와 모든 하위 폴더를 검색할지 지정하는 검색 옵션입니다. |

### 예시

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# 모든 하위 폴더를 검색하는 글꼴 소스를 생성합니다.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
