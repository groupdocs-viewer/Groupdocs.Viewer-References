---
title: GetViewInfo
second_title: GroupDocs.Viewer för .NET API-referens
description: Returnerar information om visnings och dokumentspecifik information.
type: docs
weight: 50
url: /sv/net/groupdocs.viewer/viewer/getviewinfo/
---
## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Returnerar information om visnings- och dokumentspecifik information.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewInfoOptions | Alternativen för visa information. |

### Returvärde

Information om att visa och dokumentera specifik information.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*options* är inget. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när lösenordet som angavs är felaktigt. |

### Anmärkningar

**Läs mer**

* Läs mer om dokument - filtyp, antal sidor och andra formatspecifika egenskaper: [Hur man får filinformation med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Se även

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Returnerar information om visnings- och dokumentspecifik information.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ViewInfoOptions | Alternativen för visa information. |
| cancellationToken | CancellationToken | Avbokningstoken. |

### Returvärde

Information om att visa och dokumentera specifik information.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*options* är inget. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Kastas när lösenord krävs för att öppna dokumentet. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Kastas när lösenordet som angavs är felaktigt. |

### Anmärkningar

**Läs mer**

* Läs mer om dokument - filtyp, antal sidor och andra formatspecifika egenskaper: [Hur man får filinformation med GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Se även

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namnutrymme [GroupDocs.Viewer](../../viewer)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
