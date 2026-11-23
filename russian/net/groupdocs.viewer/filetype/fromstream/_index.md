---
title: "FromStream"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Определяет тип файла, считывая сигнатуру файла."
type: docs
weight: 2000
url: /ru/net/groupdocs.viewer/filetype/fromstream/
---

## FromStream(Stream) {#fromstream}

Определяет тип файла, считывая сигнатуру файла.

```csharp
public static FileType FromStream(Stream stream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| поток | Поток | Поток файла. |

### См. также

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string) {#fromstream_2}

Определяет тип файла, считывая сигнатуру файла.

```csharp
public static FileType FromStream(Stream stream, string password)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| поток | Поток | Поток файла. |
| password | String | Пароль для открытия файла. |

### См. также

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, ILogger) {#fromstream_1}

Определяет тип файла, считывая сигнатуру файла.

```csharp
public static FileType FromStream(Stream stream, ILogger logger)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| поток | Поток | Поток файла. |
| logger | ILogger | Логгер. |

### Возвращаемое значение

Возвращает тип файла, если он был успешно определён, иначе возвращает тип файла по умолчанию [`Unknown`](../unknown).

### См. также

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## FromStream(Stream, string, ILogger) {#fromstream_3}

Определяет тип файла, считывая сигнатуру файла.

```csharp
public static FileType FromStream(Stream stream, string password, ILogger logger)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| поток | Поток | Поток файла. |
| password | String | Пароль для открытия файла. |
| logger | ILogger | Логгер. |

### Возвращаемое значение

Возвращает тип файла, если он был успешно определён, иначе возвращает тип файла по умолчанию [`Unknown`](../unknown).

### См. также

* interface [ILogger](../../../groupdocs.viewer.logging/ilogger)
* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
