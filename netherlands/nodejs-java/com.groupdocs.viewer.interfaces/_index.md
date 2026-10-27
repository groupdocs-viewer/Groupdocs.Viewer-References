---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Het pakket biedt interfaces voor het instantieren en vrijgeven van het uitvoerdocument en de bijbehorende bronnen."
type: docs
weight: 15
url: /nl/nodejs-java/com.groupdocs.viewer.interfaces/
---

Het pakket biedt interfaces voor het instantieren en vrijgeven van het uitvoerdocument en de bijbehorende bronnen.

Deze interfaces worden gebruikt om het aanmaken en vrijgeven van streams en URL's die gekoppeld zijn aan het uitvoerbestand, pagina's en HTML-bronnen te beheren.

De belangrijkste interfaces in dit pakket zijn:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

Voor meer details over het werken met deze interfaces en het aanpassen van de verwerking van het uitvoerdocument en resources in GroupDocs.Viewer, raadpleeg de [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Stelt een interface voor die een stream instantieert die wordt gebruikt om uitvoerbestandsgegevens te schrijven. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Stelt een interface voor die een stream instantieert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Stelt een interface voor die een stream instantieert die wordt gebruikt om uitvoer-HTML-resourcegegevens te schrijven. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Stelt een interface voor die een URL maakt voor een HTML-resource. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Declareert een interface voor het lezen van een bestandsstream. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Definieert methoden die nodig zijn voor het instantieren en vrijgeven van een uitvoerbestandsstream. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Definieert de methoden die nodig zijn voor het instantieren en vrijgeven van een uitvoerpagina‑stream. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Geeft een interface vrij die is geïnstantieerd door de methode die gekoppeld is aan de CreateFileStream‑interface. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Geeft een stream vrij die is geïnstantieerd door de methode die gekoppeld is aan de CreatePageStream‑interface. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Geeft een stream vrij die is geïnstantieerd door de methode die gekoppeld is aan de CreateResourceStream‑interface. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Definieert de methoden die nodig zijn voor het maken van een resource‑URL, het instantieren en vrijgeven van een uitvoer‑HTML‑resource‑stream. |
