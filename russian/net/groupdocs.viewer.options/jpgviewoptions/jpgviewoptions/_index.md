---
title: "JpgViewOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

Инициализирует экземпляр класса [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, который создает поток, используемый для записи данных выходных страниц. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Инициализирует экземпляр класса [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

Инициализирует экземпляр класса [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Фабрика, реализующая методы создания и освобождения выходного потока страницы. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *pageStreamFactory* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### См. также

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

Инициализирует экземпляр класса [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions()
```

### Примечания

Этот конструктор инициализирует экземпляр [`JpgViewOptions`](../../jpgviewoptions) с \"p_{0}.jpg\" в качестве формата пути к файлам для выходных файлов. Выходные файлы помещаются в текущий рабочий каталог приложения.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### См. также

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

Инициализирует экземпляр класса [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(string filePathFormat)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например, 'page_{0}.jpg'. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *filePathFormat* равен null или пустой. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### См. также

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
