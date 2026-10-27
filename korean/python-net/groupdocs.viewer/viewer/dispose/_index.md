---
title: "dispose 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일 스트림과 관리되는 내부 리소스를 해제합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/viewer/dispose/
is_root: false
weight: 1010
---


## dispose

파일 스트림과 관리되는 내부 리소스를 해제합니다.

```python
def dispose(self):
    ...
```

### 예시

```python
from groupdocs.viewer import Viewer

viewer = Viewer("./sample.docx")
# 뷰어로 작업 수행
viewer.dispose()
```

### 참고
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
