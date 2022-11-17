---
title: View
second_title: GroupDocs.Viewer för .NET API-referens
description: Skapar vy över alla dokumentsidor.
type: docs
weight: 70
url: /sv/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Skapar vy över alla dokumentsidor.

```csharp
public void View(ViewOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*options* är inget. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när lösenordet som angavs är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Läs mer**

* Mer om olika visningsalternativ följer den här guiden: [Hur man anpassar dokumentvisningsutdata med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Skapar vy över alla dokumentsidor.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |
| cancellationToken | CancellationToken | Avbokningstoken för att skicka en begäran om att avbryta aktuell visningsprocess. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*options* är inget. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när lösenordet som angavs är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Läs mer**

* Mer om olika visningsalternativ följer den här guiden: [Hur man anpassar dokumentvisningsutdata med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Skapar vy av specifika dokumentsidor.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |
| pageNumbers | Int32[] | Sidnumren att se. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*options* är inget. |
| ArgumentNullException | Kastas när*pageNumbers* är inget. |
| ArgumentException | Kastas när*pageNumbers* är tom. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när lösenordet som angavs är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Läs mer**

* Mer om olika visningsalternativ följer den här guiden: [Hur man anpassar dokumentvisningsutdata med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Skapar vy av specifika dokumentsidor.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewOptions | Visningsalternativen. |
| pageNumbers | CancellationToken | Sidnumren att se. |
| cancellationToken | Int32[] | Avbokningstoken för att avbryta bearbetning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*options* är inget. |
| ArgumentNullException | Kastas när*pageNumbers* är inget. |
| ArgumentException | Kastas när*pageNumbers* är tom. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när lösenordet som angavs är felaktigt. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Kastas när bilagan inte kunde hittas. |

### Anmärkningar

**Läs mer**

* Mer om olika visningsalternativ följer den här guiden: [Hur man anpassar dokumentvisningsutdata med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Se även

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
