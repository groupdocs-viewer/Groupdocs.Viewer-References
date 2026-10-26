---
title: "IAuxDisposable"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Расширяет стандартный интерфейс IDisposable, позволяя получить текущее состояние объекта и подписаться на событие освобождения"
type: docs
weight: 20
url: /ru/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

Расширяет стандартный интерфейс IDisposable, позволяет получить текущее состояние объекта и подписаться на событие освобождения.

```csharp
public interface IAuxDisposable : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | Указывает, освобожден ли ресурс (`true`) или нет (`false`) |

## События

| Имя | Описание |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | Происходит, когда объект освобождается, сразу после успешного завершения освобождения ресурсов |

### См. также

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
