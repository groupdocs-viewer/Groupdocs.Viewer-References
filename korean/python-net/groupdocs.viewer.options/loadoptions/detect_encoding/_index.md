---
title: "detect_encoding 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 FileType.txt, FileType.csv 및 FileType.tsv 파일에 대한 인코딩 감지를 가능하게 합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/
is_root: false
weight: 2010
---


## detect_encoding property

이 속성은 [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), 및 [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) 파일에 대한 인코딩 감지를 활성화합니다.

인코딩을 감지할 수 없는 경우, 기본 [`LoadOptions.encoding`](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/)이 사용됩니다. 코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def detect_encoding(self):
    ...
@detect_encoding.setter
def detect_encoding(self, value):
    ...
```

### 참고
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
