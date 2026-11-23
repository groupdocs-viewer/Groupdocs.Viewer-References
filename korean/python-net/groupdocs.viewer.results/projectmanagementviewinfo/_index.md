---
title: "ProjectManagementViewInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "MS Project 문서에 대한 보기 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

MS Project 문서에 대한 보기 정보를 나타냅니다.

ProjectManagementViewInfo 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | 새 [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | 새 ProjectManagementViewInfo 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | 프로젝트가 완료될 날짜와 시간입니다. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | 프로젝트가 시작된 날짜와 시간입니다. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 파일의 유형입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 볼 페이지 목록입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 예시

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
`ProjectManagementViewInfo`를 사용하는 작업 가이드:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
