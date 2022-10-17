---
title: ForExternalResources
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Инициализирует новый экземплярHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions класс для рендеринга в HTML с внешними ресурсами.
type: docs
weight: 20
url: /ru/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Инициализирует новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс для рендеринга в HTML с внешними ресурсами.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| createResourceStream | CreateResourceStream | Метод, который выпускает поток, созданный*createPageStream* метод. |
| createResourceUrl | CreateResourceUrl | Метод, создающий URL-адрес для HTML-ресурса. |

### Возвращаемое значение

Новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс для рендеринга в HTML с помощью внешних ресурсов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*createPageStream* нулевой. |
| ArgumentNullException | Брошен, когда*createResourceStream* нулевой. |
| ArgumentNullException | Брошен, когда*createResourceUrl* нулевой. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../htmlviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Инициализирует новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс для рендеринга в HTML с внешними ресурсами.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| createResourceStream | CreateResourceStream | Метод, создающий экземпляр потока, используемый для записи выходных данных ресурса HTML. |
| createResourceUrl | CreateResourceUrl | Метод, создающий URL-адрес для HTML-ресурса. |
| releasePageStream | ReleasePageStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному в*createPageStream* параметр. |
| releaseResourceStream | ReleaseResourceStream | Метод, который освобождает поток, созданный методом, назначенным делегату, переданному в*createResourceStream* параметр. |

### Возвращаемое значение

Новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс для рендеринга в HTML с помощью внешних ресурсов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*createPageStream* нулевой. |
| ArgumentNullException | Брошен, когда*createResourceStream* нулевой. |
| ArgumentNullException | Брошен, когда*createResourceUrl* нулевой. |
| ArgumentNullException | Брошен, когда*releasePageStream* нулевой. |
| ArgumentNullException | Брошен, когда*releaseResourceStream* нулевой. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../htmlviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Инициализирует новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс для рендеринга в HTML с внешними ресурсами.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Фабрика, которая реализует методы для создания и выпуска потока выходных страниц. |
| resourceStreamFactory | IResourceStreamFactory | Фабрика, которая реализует методы, необходимые для создания URL-адреса ресурса, создания экземпляра и выпуска выходного потока ресурсов HTML. |

### Возвращаемое значение

Новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс для рендеринга в HTML с помощью внешних ресурсов.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*pageStreamFactory* нулевой. |
| ArgumentNullException | Брошен, когда*resourceStreamFactory* нулевой. |

### Смотрите также

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../htmlviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Инициализирует новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Примечания

Этот конструктор инициализирует новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) - с "p_{0}.html" в качестве формата пути к выходным HTML-файлам; - с "p_{0}_{1}" в качестве формата пути к выходным файлам HTML-ресурсов; - с " p_{0}_{1}" в качестве формата URL для HTML-ресурсов; Выходные файлы будут помещены в текущую рабочую директорию приложения.

### Смотрите также

* class [HtmlViewOptions](../../htmlviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../htmlviewoptions)
* сборка [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Инициализирует новый экземпляр[`HtmlViewOptions`](../../htmlviewoptions) класс.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например, «page_{0}.html». |
| resourceFilePathFormat | String | Формат пути к файлу ресурса, например, «page_{0}/resource_{1}». |
| resourceUrlFormat | String | Формат URL-адреса ресурса, например «page_{0}/resource_{1}». |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*filePathFormat* является нулевым или пустым. |
| ArgumentException | Брошен, когда*resourceFilePathFormat* является нулевым или пустым. |
| ArgumentException | Брошен, когда*resourceUrlFormat* является нулевым или пустым. |

### Смотрите также

* class [HtmlViewOptions](../../htmlviewoptions)
* пространство имен [GroupDocs.Viewer.Options](../../htmlviewoptions)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
