---
title: "свойство disable_font_license_verifications"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство отключает любые лицензионные ограничения для всех шрифтов в текущем документе XPS/OXPS."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

Свойство отключает любые лицензионные ограничения для всех шрифтов в текущем документе XPS/OXPS.

Многие операции с шрифтами не могут быть выполнены, если они запрещены лицензией шрифта. Например, некоторые шрифты нельзя встроить в PDF‑документ, если правила лицензии запрещают встраивание этого шрифта. Эта опция позволяет пропустить проверку этих правил.

Будьте осторожны при использовании этого флага. Когда он установлен, это означает, что человек, устанавливающий этот флаг, берёт на себя всю ответственность за возможные нарушения лицензий или законов. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторское право. Значение по умолчанию — `False`.

Для примера кода см. документацию по адресу https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
