---
title: ForExternalResources
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: Initializes new instance of HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions class for rendering into HTML with external resources.
type: docs
weight: 20
url: /python-net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Initializes new instance of [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with external resources.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| createResourceStream | CreateResourceStream | The method that releases stream created by *createPageStream* method. |
| createResourceUrl | CreateResourceUrl | The method that creates URL for HTML resource. |

### Return Value

New instance of [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with external resources.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *createPageStream* is null. |
| ArgumentNullException | Thrown when *createResourceStream* is null. |
| ArgumentNullException | Thrown when *createResourceUrl* is null. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Initializes new instance of [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with external resources.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| createResourceStream | CreateResourceStream | The method that instantiates stream used to write output HTML resource data. |
| createResourceUrl | CreateResourceUrl | The method that creates URL for HTML resource. |
| releasePageStream | ReleasePageStream | The method that releases stream created by method assigned to delegate that passed to *createPageStream* parameter. |
| releaseResourceStream | ReleaseResourceStream | The method that releases stream created by method assigned to delegate that passed to *createResourceStream* parameter. |

### Return Value

New instance of [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with external resources.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *createPageStream* is null. |
| ArgumentNullException | Thrown when *createResourceStream* is null. |
| ArgumentNullException | Thrown when *createResourceUrl* is null. |
| ArgumentNullException | Thrown when *releasePageStream* is null. |
| ArgumentNullException | Thrown when *releaseResourceStream* is null. |

### See Also

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

Initializes new instance of [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with external resources.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | The factory which implements methods for creating and releasing output page stream. |
| resourceStreamFactory | IResourceStreamFactory | The factory which implements methods that are required for creating resource URL, instantiating and releasing output HTML resource stream. |

### Return Value

New instance of [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with external resources.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *pageStreamFactory* is null. |
| ArgumentNullException | Thrown when *resourceStreamFactory* is null. |

### See Also

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Initializes new instance of [`HtmlViewOptions`](../../htmlviewoptions) class.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Remarks

This constructor initializes new instance of [`HtmlViewOptions`](../../htmlviewoptions) - with "p_{0}.html" as file path format for the output HTML files; - with "p_{0}_{1}" as file path format for the output HTML-resource files; - with "p_{0}_{1}" as URL format for HTML-resources; The output files will be placed into current working directory of the application.

### See Also

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Initializes new instance of [`HtmlViewOptions`](../../htmlviewoptions) class.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'page_{0}.html'. |
| resourceFilePathFormat | String | The resource file path format e.g. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | The resource URL format e.g. 'page_{0}/resource_{1}'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *filePathFormat* is null or empty. |
| ArgumentException | Thrown when *resourceFilePathFormat* is null or empty. |
| ArgumentException | Thrown when *resourceUrlFormat* is null or empty. |

### See Also

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.viewer.dll -->
