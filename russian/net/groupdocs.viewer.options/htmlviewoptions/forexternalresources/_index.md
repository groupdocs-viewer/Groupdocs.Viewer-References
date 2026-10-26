---
title: "ForExternalResources"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует экземпляр класса HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions для рендеринга в HTML с внешними ресурсами."
type: docs
weight: 20
url: /ru/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с внешними ресурсами.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий поток, используемый для записи данных выходной страницы. |
| createResourceStream | CreateResourceStream | Метод, освобождающий поток, созданный методом *createPageStream*. |
| createResourceUrl | CreateResourceUrl | Метод, который создает URL для HTML‑ресурса. |

### Возвращаемое значение

Новый экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с внешними ресурсами.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *createResourceStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *createResourceUrl* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с внешними ресурсами.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий поток, используемый для записи данных выходной страницы. |
| createResourceStream | CreateResourceStream | Метод, который создает поток, используемый для записи данных выходного HTML‑ресурса. |
| createResourceUrl | CreateResourceUrl | Метод, который создает URL для HTML‑ресурса. |
| releasePageStream | ReleasePageStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному в параметр *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному в параметр *createResourceStream*. |

### Возвращаемое значение

Новый экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с внешними ресурсами.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *createPageStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *createResourceStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *createResourceUrl* равно null. |
| ArgumentNullException | Выбрасывается, когда *releasePageStream* равно null. |
| ArgumentNullException | Выбрасывается, когда *releaseResourceStream* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### См. также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с внешними ресурсами.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Фабрика, реализующая методы создания и освобождения выходного потока страницы. |
| resourceStreamFactory | IResourceStreamFactory | Фабрика, реализующая методы, необходимые для создания URL ресурса, создания и освобождения выходного потока HTML‑ресурса. |

### Возвращаемое значение

Новый экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions) для рендеринга в HTML с внешними ресурсами.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Выбрасывается, когда *pageStreamFactory* равно null. |
| ArgumentNullException | Выбрасывается, когда *resourceStreamFactory* равно null. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### См. также

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Примечания

Этот конструктор инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Выходные файлы будут помещены в текущий рабочий каталог приложения.

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### См. также

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Инициализирует экземпляр класса [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например 'page_{0}.html'. |
| resourceFilePathFormat | String | Формат пути к файлу ресурса, например 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Формат URL ресурса, например 'page_{0}/resource_{1}'. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *filePathFormat* равен null или пустой. |
| ArgumentException | Выбрасывается, когда *resourceFilePathFormat* равен null или пустой. |
| ArgumentException | Выбрасывается, когда *resourceUrlFormat* равен null или пустой. |

### Примечания

Для примера кода см. [документацию](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### См. также

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
