---
title: "Classe FontStyles"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta 4 possibili stili del carattere, utilizzati nel documento: Regular, Bold, Italic o Bold Italic."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

Rappresenta 4 possibili stili del carattere, utilizzati nel documento: Regular, Bold, Italic o Bold Italic.

Struct immutabile con API comoda e operazioni di combinazione.

Il tipo FontStyles espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | Inizializza un'istanza di FontStyles dai flag bold e italic specificati. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Indica se questa istanza di FontStyles è uguale all'istanza specificata. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Indica se questa istanza di [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) è uguale all'oggetto non convertito specificato. |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | Restituisce un codice hash di questa istanza. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | Restituisce il nome di questo stile di carattere, identico a [`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/). |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | Tenta di analizzare la stringa grezza specificata come nome di uno stile di carattere. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | La proprietà indica se questa istanza di [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) ha il flag grassetto abilitato (`True`) o disabilitato (`False`). |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | Lo stato del flag corsivo di questa istanza di [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/); `True` se abilitato, `False` se disabilitato. |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | Il nome di questo stile di carattere. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | Stile di carattere regolare, valore predefinito (senza grassetto e corsivo) |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | Stile di carattere grassetto (solo grassetto, senza corsivo) |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | Stile di carattere corsivo (solo corsivo, senza grassetto) |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | Stile di carattere BoldItalic (grassetto e corsivo insieme) |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
