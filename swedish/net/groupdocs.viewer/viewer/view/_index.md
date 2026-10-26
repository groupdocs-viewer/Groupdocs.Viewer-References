---
title: "View"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Skapar en vy av alla dokumentsidor."
type: docs
weight: 90
url: /sv/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Skapar en vy av alla dokumentsidor.

```csharp
public void View(ViewOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *options* är null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när ett lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när det angivna lösenordet är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Skapar en vy av alla dokumentsidor.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |
| cancellationToken | CancellationToken | Avbokningstoken för att skicka en begäran om att avbryta den aktuella visningsprocessen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *options* är null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när ett lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när det angivna lösenordet är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Skapar en vy av specifika dokumentsidor.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |
| pageNumbers | Int32[] | Sidnumren att visa. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *options* är null. |
| ArgumentNullException | Kastas när *pageNumbers* är null. |
| ArgumentException | Kastas när *pageNumbers* är tom. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när ett lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när det angivna lösenordet är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Skapar en vy av specifika dokumentsidor.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |
| pageNumbers | CancellationToken | Sidnumren att visa. |
| cancellationToken | Int32[] | Avbokningstoken för att avbryta bearbetning. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *options* är null. |
| ArgumentNullException | Kastas när *pageNumbers* är null. |
| ArgumentException | Kastas när *pageNumbers* är tom. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när ett lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när det angivna lösenordet är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
