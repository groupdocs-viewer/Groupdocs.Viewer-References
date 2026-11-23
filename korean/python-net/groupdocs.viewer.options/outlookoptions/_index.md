---
title: "OutlookOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Outlook 데이터 파일을 렌더링하기 위한 옵션을 포함합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Outlook 데이터 파일을 렌더링하기 위한 옵션을 포함합니다.

자세한 내용은 GroupDocs 문서를 참조하십시오.

OutlookOptions 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### 속성
| 속성 | 설명 |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | 보낸 사람 또는 수신자별로 메시지를 필터링하는 데 사용되는 이메일 주소. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | 렌더링할 폴더의 이름(예: Inbox, Sent Item 또는 Deleted Items). |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | 하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | 메시지를 필터링하는 데 사용되는 키워드. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # 폴더당 렌더링되는 항목 수를 제한합니다.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
