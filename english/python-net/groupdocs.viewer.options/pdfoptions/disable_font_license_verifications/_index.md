---
title: disable_font_license_verifications property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 50
---

## disable_font_license_verifications property


Disables any license restrictions for all fonts in the current XPS/OXPS document.

### Remarks 


Many operations with font cannot be executed if they are prohibited by license of this font. For example, some font cannot be embedded into PDF document if license rules disable embedding for this font. This option allows you to skip verification of these rules.




Be careful when using this flag. When it is set, it means that person who sets this flag, takes all responsibility of possible license/law violations on himself. So he takes it on its own risk. It is strongly recommended to use this flag only when you are fully confident that you are not breaking the copyright law. The default value is `false`.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).
### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
