---
title: "FontSettings 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "TrueType 글꼴을 찾기 위해 소스와 작업하는 메서드를 제공합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

TrueType 글꼴을 찾기 위해 소스와 작업하는 메서드를 제공합니다.

FontSettings 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | 이전에 설정된 폰트 소스를 재설정합니다. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | 문서를 렌더링할 때 TrueType 폰트를 찾을 소스를 설정합니다. |

### 예시

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 다양한 인수 형태를 사용하여 폰트 소스를 설정합니다(내부적으로 평탄화됨).
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# 등록된 모든 폰트 소스를 지웁니다.
FontSettings.reset_font_sources()
```

### 참고
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
