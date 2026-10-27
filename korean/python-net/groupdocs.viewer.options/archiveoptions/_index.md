---
title: "ArchiveOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "아카이브 파일 렌더링 옵션을 포함합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

아카이브 파일 렌더링 옵션을 포함합니다.

ArchiveOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) 클래스의 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | 표시되는 아카이브 파일 이름입니다. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | 렌더링될 폴더입니다. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
