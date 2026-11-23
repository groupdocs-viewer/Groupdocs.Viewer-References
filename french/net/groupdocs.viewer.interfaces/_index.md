---
title: "GroupDocs.Viewer.Interfaces"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "L'espace de noms fournit des interfaces pour instancier et libérer le document de sortie et ses ressources."
type: docs
weight: 60
url: /fr/net/groupdocs.viewer.interfaces/
---

L'espace de noms fournit des interfaces pour instancier et libérer le document de sortie et ses ressources.

## Classes

| Classe | Description |
| --- | --- |
| [CreateFileStream](./createfilestream) | Représente la méthode qui instancie le flux utilisé pour écrire les données du fichier de sortie. |
| [CreatePageStream](./createpagestream) | Représente la méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| [CreateResourceStream](./createresourcestream) | Représente la méthode qui instancie le flux utilisé pour écrire les données de la ressource HTML de sortie. |
| [CreateResourceUrl](./createresourceurl) | Représente la méthode qui crée l'URL pour la ressource HTML. |
| [ReleaseFileStream](./releasefilestream) | Libère le flux qui a été instancié par la méthode associée au délégué [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream). |
| [ReleasePageStream](./releasepagestream) | Libère le flux qui a été instancié par la méthode associée au délégué [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream). |
| [ReleaseResourceStream](./releaseresourcestream) | Libère le flux qui a été instancié par la méthode associée au délégué [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream). |
## Interfaces

| Interface | Description |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Définit les méthodes requises pour instancier et libérer le flux du fichier de sortie. |
| [IPageStreamFactory](./ipagestreamfactory) | Définit les méthodes requises pour instancier et libérer le flux de la page de sortie. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Définit les méthodes requises pour créer l'URL de la ressource, instancier et libérer le flux de la ressource HTML de sortie. |

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
