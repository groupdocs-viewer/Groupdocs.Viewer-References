---
title: "ArchiveViewInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "아카이브 파일에 대한 보기 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

아카이브 파일에 대한 보기 정보를 나타냅니다.

ArchiveViewInfo 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | 새 인스턴스 [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | 새 ArchiveViewInfo 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | 아카이브 파일에 포함된 폴더입니다. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 파일의 유형입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 볼 페이지 목록입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 예시

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
`ArchiveViewInfo`를 사용하는 작업 가이드:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
