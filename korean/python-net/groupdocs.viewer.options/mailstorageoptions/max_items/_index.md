---
title: "max_items 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "렌더링할 최대 메시지 또는 항목 수."
type: docs
url: /ko/python-net/groupdocs.viewer.options/mailstorageoptions/max_items/
is_root: false
weight: 2020
---


## max_items property

렌더링할 최대 메시지 또는 항목 수.

메일 스토리지 데이터 파일은 크기가 클 수 있으며 모든 메시지를 가져오는 데 상당한 시간이 걸릴 수 있습니다. 이 속성은 렌더링되는 메시지 또는 항목의 최대 수를 제한합니다. 기본값은 0이며, 모든 메시지가 렌더링됩니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def max_items(self):
    ...
@max_items.setter
def max_items(self, value):
    ...
```

### 참고
* class [`MailStorageOptions`](/viewer/python-net/groupdocs.viewer.options/mailstorageoptions/)
