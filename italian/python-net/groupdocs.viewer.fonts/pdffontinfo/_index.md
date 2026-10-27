---
title: "Classe PdfFontInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Incapsula i metadati e i dati binari di un carattere PDF caricato in un'istanza di Viewer, che può essere incorporato nel documento o installato sul sistema operativo su cui gira GroupDocs.Viewer."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Incapsula i metadati e i dati binari di un carattere PDF caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), che può essere incorporato nel documento o installato sul sistema operativo in cui gira GroupDocs.Viewer.

Il tipo PdfFontInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Serializza queste informazioni sul carattere come una regola @font-face e le scrive nel writer di testo specificato. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Il contenuto di questo carattere come array di byte, o None se sono disponibili solo i metadati e il contenuto binario non è disponibile. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Il nome della famiglia del carattere, senza stile; mai None o stringa vuota. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Il formato di questo carattere. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | La proprietà indica se il carattere è incorporato nel documento PDF e caricato nell'istanza di Viewer (`True`), o no. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | La proprietà indica se questo carattere è presente (installato) nel sistema operativo in cui è in esecuzione GroupDocs.Viewer. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Lo stile del carattere; può essere Regular, Bold, Italic o Bold Italic. |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
