---
title: "LoadOptions 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일을 열 때 사용되는 옵션."
type: docs
url: /ko/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

파일을 열 때 사용되는 옵션.

LoadOptions 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) 클래스의 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | 새 LoadOptions 인스턴스를 초기화합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | 이 속성은 [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), 및 [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) 파일에 대한 인코딩 감지를 활성화합니다. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | 텍스트 기반 파일이나 이메일 메시지(예: [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/))를 열 때 사용되는 인코딩입니다. 기본값은 `utf-8`입니다. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | 열 파일의 유형입니다. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | 암호화된 파일을 열기 위한 비밀번호입니다. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | 외부 리소스를 로드하기 위한 시간 제한입니다. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | 이 속성은 이미지와 같은 모든 외부 리소스의 로드를 비활성화하지만, [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/)에 나열된 리소스는 제외합니다. |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | 이 속성은 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도하도록 활성화합니다. 기본값은 False입니다. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | 이 속성이 `True`로 설정된 경우 로드해야 하는 외부 리소스에 해당하는 URL 조각 목록입니다 (`[`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/)`가 `True`일 때`). |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
