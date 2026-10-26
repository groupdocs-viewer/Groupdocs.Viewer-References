---
title: "PngViewOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса PngViewOptionsgroupdocs.viewer.options/pngviewoptions."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

Инициализирует экземпляр класса [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, который создает поток, используемый для записи данных выходных страниц. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Инициализирует экземпляр класса [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, который создает поток, используемый для записи данных выходных страниц. |
| releasePageStream | ReleasePageStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному параметру *createPageStream*. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *releasePageStream* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Инициализирует экземпляр класса [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Фабрика, реализующая методы создания и освобождения выходного потока страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *pageStreamFactory* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### См. также

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Инициализирует экземпляр класса [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions()
```

### Примечания

Этот конструктор инициализирует экземпляр [`PngViewOptions`](../../pngviewoptions) с форматом пути к файлу "p_{0}.png" для выходных файлов. Выходные файлы размещаются в текущем рабочем каталоге приложения.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### См. также

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Инициализирует экземпляр класса [`PngViewOptions`](../../pngviewoptions).

```csharp
public PngViewOptions(string filePathFormat)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например 'page_{0}.png'. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *filePathFormat* равен null или пустой. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png).

### См. также

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
