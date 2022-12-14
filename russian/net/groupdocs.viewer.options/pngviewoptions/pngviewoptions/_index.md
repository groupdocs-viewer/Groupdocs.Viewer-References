---
title: PngViewOptions
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Инициализирует новый экземплярPngViewOptionsgroupdocs.viewer.options/pngviewoptions класс.
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---
## PngViewOptions(CreatePageStream) {#constructor_1}

Инициализирует новый экземпляр[`PngViewOptions`](../../pngviewoptions) класс.

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*createPageStream* нулевой. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../pngviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Инициализирует новый экземпляр[`PngViewOptions`](../../pngviewoptions) класс.

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| releasePageStream | ReleasePageStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному в*createPageStream* параметр. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*createPageStream* нулевой. |
| ArgumentNullException | Брошен, когда*releasePageStream* нулевой. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../pngviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Инициализирует новый экземпляр[`PngViewOptions`](../../pngviewoptions) класс.

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Фабрика, которая реализует методы для создания и выпуска потока выходных страниц. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*pageStreamFactory* нулевой. |

### Смотрите также

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../pngviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Инициализирует новый экземпляр[`PngViewOptions`](../../pngviewoptions) класс.

```csharp
public PngViewOptions()
```

### Примечания

Этот конструктор инициализирует новый экземпляр[`PngViewOptions`](../../pngviewoptions) с "p_{0}.png" в качестве формата пути к выходным файлам. Выходные файлы будут помещены в текущий рабочий каталог приложения.

### Смотрите также

* class [PngViewOptions](../../pngviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../pngviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Инициализирует новый экземпляр[`PngViewOptions`](../../pngviewoptions) класс.

```csharp
public PngViewOptions(string filePathFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например, «page_{0}.png». |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*filePathFormat* является нулевым или пустым. |

### Смотрите также

* class [PngViewOptions](../../pngviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../pngviewoptions)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
