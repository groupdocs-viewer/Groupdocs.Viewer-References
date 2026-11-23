---
title: "DisableFontLicenseVerifications"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Отключает любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS."
type: docs
weight: 40
url: /ru/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

Отключает любые ограничения лицензии для всех шрифтов в текущем документе XPS/OXPS.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### Примечания

Многие операции с шрифтом не могут быть выполнены, если они запрещены лицензией этого шрифта. Например, некоторые шрифты нельзя встроить в PDF‑документ, если правила лицензии отключают встраивание для этого шрифта. Эта опция позволяет пропустить проверку этих правил.

Будьте осторожны, используя этот флаг. Когда он установлен, это означает, что человек, устанавливающий флаг, берёт на себя всю ответственность за возможные нарушения лицензий/законов. Таким образом, он действует на свой собственный риск. Настоятельно рекомендуется использовать этот флаг только тогда, когда вы полностью уверены, что не нарушаете авторское право. Значение по умолчанию — `false`.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### См. также

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
