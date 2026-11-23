---
title: "Classe WordProcessingFontInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Incapsula i metadati e i dati binari di un font da un documento WordProcessing caricato in un'istanza di Viewer."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Incapsula metainformazioni e dati binari di un carattere da un documento WordProcessing caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Struttura immutabile.

Le sue istanze sono prodotte e restituite dall'API pubblica di [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) e normalmente non dovrebbero essere create dall'utente.

Per i dettagli, vedere la documentazione: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Il tipo WordProcessingFontInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Serializza le informazioni sul carattere come una regola @font-face e le scrive nel writer di testo specificato. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Restituisce informazioni di debug su questi dati del font secondo il modello seguente: "nome stile, incorporato/sistema, formato". |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Il nome alternativo della famiglia del font. Se mancante, restituisce una stringa vuota. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Il set di caratteri di questo font. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Il contenuto di questo font come array di byte. Se sono disponibili solo i metadati del font e il contenuto binario non è disponibile, la proprietà restituisce None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Il nome della famiglia del carattere, senza stile; mai None o stringa vuota. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Il formato di questo carattere. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | La proprietà indica se questo font è incorporato nel documento, caricato nell'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), oppure è un font di sistema (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Lo stile del font — può essere Regular, Bold, Italic o Bold Italic. |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
