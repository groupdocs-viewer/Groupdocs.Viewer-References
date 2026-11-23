---
title: "Classe PresentationFontInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le metainformazioni e i dati binari di un font da un documento Presentation caricato in un'istanza di Viewer."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Rappresenta metainformazioni e dati binari di un carattere da un documento Presentation caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Il carattere è utilizzato nel contenuto del documento e può essere incorporato nel documento o installato nel sistema operativo in cui gira il visualizzatore.

Il tipo PresentationFontInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Serializza queste informazioni sul carattere come una regola @font-face e le scrive nel writer di testo specificato. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Il contenuto di questo font come array di byte. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Il nome della famiglia del carattere, senza stile; mai None o stringa vuota. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Il formato di questo carattere. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | La proprietà indica se il font è incorporato nel documento e caricato nell'istanza [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), oppure è un font di sistema (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Lo stile del font — può essere Regular, Bold, Italic o Bold Italic. |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
