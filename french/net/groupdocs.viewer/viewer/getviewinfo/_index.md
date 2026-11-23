---
title: "GetViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie des informations sur la vue et des informations spécifiques au document."
type: docs
weight: 60
url: /fr/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Renvoie des informations sur la vue et des informations spécifiques au document.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ViewInfoOptions | Les options d'informations de vue. |

### Valeur de retour

Informations sur la vue et les informations spécifiques au document.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *options* est null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |

### Remarques

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Voir aussi

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Renvoie des informations sur la vue et des informations spécifiques au document.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ViewInfoOptions | Les options d'informations de vue. |
| cancellationToken | CancellationToken | Jeton d'annulation. |

### Valeur de retour

Informations sur la vue et les informations spécifiques au document.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Levée lorsque *options* est null. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lancé lorsque le mot de passe est requis pour ouvrir le document. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lancé lorsque le mot de passe spécifié est incorrect. |

### Remarques

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Voir aussi

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
