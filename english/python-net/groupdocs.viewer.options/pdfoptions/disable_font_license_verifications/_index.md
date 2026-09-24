---
title: disable_font_license_verifications property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property disables any license restrictions for all fonts in the current XPS/OXPS document."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

The property disables any license restrictions for all fonts in the current XPS/OXPS document.

Many operations with fonts cannot be executed if they are prohibited by the font's license. For example, some fonts cannot be embedded into a PDF document if license rules disable embedding for that font. This option allows you to skip verification of these rules.

Be careful when using this flag. When it is set, it means that the person who sets this flag takes all responsibility for possible license or law violations. It is strongly recommended to use this flag only when you are fully confident that you are not breaking copyright law. The default value is `False`.

For a code example, see the documentation at https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

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
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
