---
title: ForEmbeddedResources
second_title: GroupDocs.Viewer for .NET API Reference
description: Initializes an instance of the HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions class for rendering into HTML with embedded resources.
type: docs
weight: 10
url: /net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---
## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Initializes an instance of the [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with embedded resources.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |

### Return Value

New instance of the [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with embedded resources.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *createPageStream* is null. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### See Also

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Initializes an instance of the [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with embedded resources.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| releasePageStream | ReleasePageStream | The method that releases stream created by method assigned to delegate that passed to *createPageStream* parameter. |

### Return Value

New instance of the [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with embedded resources.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *createPageStream* is null. |
| ArgumentNullException | Thrown when *releasePageStream* is null. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### See Also

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Initializes an instance of the [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with embedded resources.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | The factory which implements methods for creating and releasing output page stream. |

### Return Value

New instance of the [`HtmlViewOptions`](../../htmlviewoptions) class for rendering into HTML with embedded resources.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *pageStreamFactory* is null. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### See Also

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Initializes an instance of the [`HtmlViewOptions`](../../htmlviewoptions) class.

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### See Also

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Initializes an instance of the [`HtmlViewOptions`](../../htmlviewoptions) class.

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'page_{0}.html'. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *filePathFormat* is null or empty. |

### Remarks

For the code example, see the [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### See Also

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
