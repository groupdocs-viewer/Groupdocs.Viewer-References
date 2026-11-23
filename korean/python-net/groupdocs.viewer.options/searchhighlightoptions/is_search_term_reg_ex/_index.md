---
title: "is_search_term_reg_ex 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "검색어를 정규식으로 처리할지 텍스트 리터럴로 처리할지를 나타내는 속성입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/searchhighlightoptions/is_search_term_reg_ex/
is_root: false
weight: 2030
---


## is_search_term_reg_ex property

이 속성은 검색어를 정규식으로 처리할지 텍스트 리터럴로 처리할지를 나타냅니다. 기본값은 False이며, 텍스트 리터럴로 처리합니다.

True인 경우, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/)은 .NET Regex 패턴으로 해석됩니다.

False인 경우, [`SearchHighlightOptions.search_term`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/search_term/)은 문서에서 텍스트 리터럴로 검색됩니다.

### Definition:
```python
@property
def is_search_term_reg_ex(self):
    ...
@is_search_term_reg_ex.setter
def is_search_term_reg_ex(self, value):
    ...
```

### 참고
* class [`SearchHighlightOptions`](/viewer/python-net/groupdocs.viewer.options/searchhighlightoptions/)
