---
title: "Permissions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Определяет разрешения PDF‑документа."
type: docs
weight: 430
url: /ru/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

Определяет разрешения PDF‑документа.

```csharp
[Flags]
public enum Permissions
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| AllowAll | `0` | Разрешить печать, изменение и извлечение данных. |
| DenyPrinting | `1` | Запретить печать. |
| DenyModification | `2` | Запретить изменение содержимого, заполнение форм, добавление или изменение аннотаций. |
| DenyDataExtraction | `4` | Запретить извлечение текста и графики. |
| DenyAll | `7` | Запретить печать, изменение содержимого и извлечение данных. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
