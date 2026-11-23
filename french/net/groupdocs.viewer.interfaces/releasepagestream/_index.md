---
title: "ReleasePageStream"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Libère le flux qui a été instancié par la méthode associée au délégué CreatePageStream./createpagestream."
type: docs
weight: 710
url: /fr/net/groupdocs.viewer.interfaces/releasepagestream/
---

## ReleasePageStream delegate

Libère le flux qui a été instancié par la méthode associée au délégué [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de la page. |
| pageStream | Stream | Le flux créé par la méthode associée au délégué [`CreatePageStream`](../createpagestream). |

### Voir aussi

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
