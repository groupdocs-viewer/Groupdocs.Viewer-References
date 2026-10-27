---
title: "set_font_sources 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "문서를 렌더링할 때 TrueType 폰트를 찾을 소스를 설정합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

문서를 렌더링할 때 TrueType 폰트를 찾을 소스를 설정합니다.

이 메서드는 개별 [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) 객체, 해당 객체들의 리스트, 또는 두 가지가 혼합된 모든 조합을 허용합니다; 모든 입력은 적용되기 전에 단일 리스트로 평탄화됩니다. 문자열 경로는 그대로 전달되며 문자 단위로 분할되지 않습니다.

```python
def set_font_sources(cls, font_sources):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | 폰트 소스. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `font_sources`가 None인 경우. |

### 예시

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 가변 인자
FontSettings.set_font_sources(src1, src2)
# 단일 리스트
FontSettings.set_font_sources([src1, src2])
# 여러 리스트 (평탄화됨)
FontSettings.set_font_sources([src1], [src2])
# 혼합 — 또한 평탄화됨
FontSettings.set_font_sources([src1, src2], src2)
```

### 참고
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
