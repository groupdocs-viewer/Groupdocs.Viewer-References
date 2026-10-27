---
title: "Classe SpreadsheetFontInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Incapsula le metainformazioni e i dati binari di un font da un documento di foglio di calcolo caricato in un'istanza di Viewer."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Incapsula metainformazioni e dati binari di un carattere da un documento spreadsheet caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). I documenti spreadsheet non possono contenere caratteri incorporati, quindi un carattere restituito da [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) viene installato nel sistema operativo in cui gira il visualizzatore.

Il tipo SpreadsheetFontInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Serializza le informazioni sul carattere come una regola @font-face e le scrive nel writer di testo specificato. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Il set di caratteri di questo font. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Il colore di questo font. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Il contenuto di questo font come array di byte. Se sono disponibili solo le metainformazioni su questo font e il suo contenuto binario non è disponibile, la proprietà restituisce None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Il nome della famiglia del font, senza stile, non è mai nullo o una stringa vuota. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Il formato di questo carattere. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Il font ha una singola barratura. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Il font è sottolineato. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Lo stile di questo font — può essere Regular, Bold, Italic o Bold Italic. |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
