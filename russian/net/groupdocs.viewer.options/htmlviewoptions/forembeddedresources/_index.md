---
title: "ForEmbeddedResources"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions для рендеринга в HTML с встроенными ресурсами."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий поток, используемый для записи данных выходной страницы. |

### Возвращаемое значение

Новый экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий поток, используемый для записи данных выходной страницы. |
| releasePageStream | ReleasePageStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному в параметр *createPageStream*. |

### Возвращаемое значение

Новый экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *releasePageStream* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Фабрика, реализующая методы создания и освобождения выходного потока страницы. |

### Возвращаемое значение

Новый экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с встроенными ресурсами.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *pageStreamFactory* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### См. также

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### См. также

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например 'page_{0}.html'. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *filePathFormat* равен null или пустой. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### См. также

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
