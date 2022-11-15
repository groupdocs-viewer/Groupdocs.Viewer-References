---
title: ReleasePageStream
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Releases stream qui a été instancié par la méthode associée àCreatePageStream./createpagestream délégué.
type: docs
weight: 200
url: /fr/net/groupdocs.viewer.interfaces/releasepagestream/
---
## ReleasePageStream delegate

Releases stream qui a été instancié par la méthode associée à[`CreatePageStream`](../createpagestream) délégué.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de la page. |
| pageStream | Stream | Le flux créé par la méthode associée à[`CreatePageStream`](../createpagestream) déléguer. |

### Voir également

* espace de noms [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->