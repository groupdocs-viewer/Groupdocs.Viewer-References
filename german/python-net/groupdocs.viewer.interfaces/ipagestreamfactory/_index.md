---
title: "IPageStreamFactory Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Das Interface definiert die Methoden, die zum Instanziieren und Freigeben von Ausgabeseiten-Streams erforderlich sind."
type: docs
url: /de/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/
is_root: false
weight: 60
---


## IPageStreamFactory class

Das Interface definiert die Methoden, die zum Instanziieren und Freigeben von Ausgabeseiten-Streams erforderlich sind.

Der Typ IPageStreamFactory stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [create_page_stream](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/#page_number) | Erstellt den Stream, der zum Schreiben der Ausgabeseitendaten verwendet wird. |
| [create_page_stream_int32](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream_int32/) |  |
| [release_page_stream](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/#page_number-page_stream) | Gibt den durch die Methode [`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) erstellten Stream frei. |
| [release_page_stream_int32](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream_int32/) |  |
| [release_page_stream_stream](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream_stream/) |  |
| [release_page_stream_streams](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream_streams/) |  |

### Siehe auch
* module [`groupdocs.viewer.interfaces`](/viewer/python-net/groupdocs.viewer.interfaces/)
