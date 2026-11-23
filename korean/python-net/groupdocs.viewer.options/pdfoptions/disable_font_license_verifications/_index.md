---
title: "disable_font_license_verifications 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 현재 XPS/OXPS 문서의 모든 글꼴에 대한 라이선스 제한을 비활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

이 속성은 현재 XPS/OXPS 문서의 모든 글꼴에 대한 라이선스 제한을 비활성화합니다.

글꼴에 대한 많은 작업은 해당 글꼴의 라이선스에 의해 금지된 경우 실행할 수 없습니다. 예를 들어, 라이선스 규정이 해당 글꼴의 임베딩을 비활성화하면 일부 글꼴을 PDF 문서에 삽입할 수 없습니다. 이 옵션을 사용하면 이러한 규정의 검증을 건너뛸 수 있습니다.

이 플래그를 사용할 때는 주의하십시오. 플래그가 설정되면 해당 플래그를 설정한 사람이 라이선스 또는 법 위반에 대한 모든 책임을 진다는 의미입니다. 저작권법을 위반하지 않음에 대해 완전히 확신할 때만 이 플래그를 사용하는 것이 강력히 권장됩니다. 기본값은 `False`입니다.

코드 예제는 https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files 에 있는 문서를 참조하십시오.

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
