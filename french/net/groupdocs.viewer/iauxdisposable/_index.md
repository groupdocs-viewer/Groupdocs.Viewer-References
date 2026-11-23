---
title: "IAuxDisposable"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Étend l'interface standard IDisposable, permet d'obtenir l'état actuel d'un objet et de s'abonner à l'événement de libération."
type: docs
weight: 20
url: /fr/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

Étend l’interface standard IDisposable, permet d’obtenir l’état actuel d’un objet et de s’abonner à l’événement de libération.

```csharp
public interface IAuxDisposable : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | Indique si une ressource est déjà libérée (`true`) ou non (`false`). |

## Événements

| Nom | Description |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | Se produit lorsque l'objet est libéré, juste après que la libération des ressources soit terminée avec succès. |

### Voir aussi

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
