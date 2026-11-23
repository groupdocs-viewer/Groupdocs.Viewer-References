---
title: "GroupDocs.Viewer.Interfaces"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Это пространство имён предоставляет интерфейсы для создания и освобождения выходного документа и его ресурсов."
type: docs
weight: 60
url: /ru/net/groupdocs.viewer.interfaces/
---

Это пространство имён предоставляет интерфейсы для создания и освобождения выходного документа и его ресурсов.

## Классы

| Класс | Описание |
| --- | --- |
| [CreateFileStream](./createfilestream) | Представляет метод, который создает поток, используемый для записи данных выходного файла. |
| [CreatePageStream](./createpagestream) | Представляет метод, который создает поток, используемый для записи данных выходной страницы. |
| [CreateResourceStream](./createresourcestream) | Представляет метод, который создает поток, используемый для записи данных выходного HTML‑ресурса. |
| [CreateResourceUrl](./createresourceurl) | Представляет метод, который создает URL для HTML‑ресурса. |
| [ReleaseFileStream](./releasefilestream) | Освобождает поток, который был создан методом, связанным с делегатом [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream). |
| [ReleasePageStream](./releasepagestream) | Освобождает поток, который был создан методом, связанным с делегатом [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream). |
| [ReleaseResourceStream](./releaseresourcestream) | Освобождает поток, который был создан методом, связанным с делегатом [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream). |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Определяет методы, необходимые для создания и освобождения потока выходного файла. |
| [IPageStreamFactory](./ipagestreamfactory) | Определяет методы, необходимые для создания и освобождения потока выходной страницы. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Определяет методы, необходимые для создания URL ресурса, создания и освобождения потока выходного HTML‑ресурса. |

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
