---
title: "folder 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "폴더 이름 (예:"
type: docs
url: /ko/python-net/groupdocs.viewer.options/outlookoptions/folder/
is_root: false
weight: 2020
---


## folder property

렌더링할 폴더의 이름(예: Inbox, Sent Item 또는 Deleted Items).

Outlook 데이터 파일을 렌더링할 때, GroupDocs.Viewer는 파일에 포함된 모든 폴더(중첩 폴더 포함)의 메시지를 렌더링합니다. 이 속성을 사용하여 특정 폴더의 항목을 렌더링하십시오.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def folder(self):
    ...
@folder.setter
def folder(self, value):
    ...
```

### 참고
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
