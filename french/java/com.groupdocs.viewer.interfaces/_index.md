---
title: "com.groupdocs.viewer.interfaces"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Le package fournit des interfaces pour instancier et libérer le document de sortie ainsi que ses ressources."
type: docs
weight: 17
url: /fr/java/com.groupdocs.viewer.interfaces/
---

Le package fournit des interfaces pour instancier et libérer le document de sortie ainsi que ses ressources.


Ces interfaces sont utilisées pour gérer la création et la libération des flux et des URL associés au fichier de sortie, aux pages et aux ressources HTML.

Les principales interfaces de ce paquet sont :

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


Pour plus de détails sur l'utilisation de ces interfaces et la personnalisation du document de sortie ainsi que la gestion des ressources dans GroupDocs.Viewer,
Veuillez vous référer à la [Documentation GroupDocs.Viewer](../https://docs.groupdocs.com/viewer/java/).



## Interfaces

| Interface | Description |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Représente une interface qui instancie un flux utilisé pour écrire les données du fichier de sortie. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Représente une interface qui instancie un flux utilisé pour écrire les données de la page de sortie. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Représente une interface qui instancie un flux utilisé pour écrire les données de la ressource HTML de sortie. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Représente une interface qui crée une URL pour une ressource HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Déclare une interface pour lire un flux de fichier. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Définit les méthodes requises pour instancier et libérer un flux de fichier de sortie. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Définit les méthodes requises pour instancier et libérer un flux de page de sortie. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Libère une interface qui a été instanciée par la méthode associée à l'interface CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Libère un flux qui a été instancié par la méthode associée à l'interface CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Libère un flux qui a été instancié par la méthode associée à l'interface CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Définit les méthodes requises pour créer une URL de ressource, instancier et libérer un flux de ressource HTML de sortie. |
