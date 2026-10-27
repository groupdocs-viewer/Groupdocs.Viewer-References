---
title: "max_items_in_folder 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수."
type: docs
url: /ko/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

하나의 폴더에서 렌더링할 수 있는 최대 메시지 또는 항목 수.

Outlook 데이터 파일은 크기가 클 수 있으며 모든 메시지를 가져오는 데 상당한 시간이 걸릴 수 있습니다. 이 속성은 렌더링되는 메시지 또는 항목의 최대 수를 제한합니다. 기본값은 `50`입니다. 모든 메시지를 렌더링하려면 값을 `0`으로 설정하십시오.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### 참고
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
