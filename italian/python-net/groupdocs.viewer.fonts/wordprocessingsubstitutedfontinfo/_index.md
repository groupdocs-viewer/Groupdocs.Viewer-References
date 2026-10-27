---
title: "Classe WordProcessingSubstitutedFontInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Incapsula le informazioni di metadati e i dati binari di un carattere da un documento WordProcessing, che originariamente non è utilizzato nel documento dell'istanza Viewer caricata, ma serve come carattere di sostituzione per quelli che…"
type: docs
url: /it/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Incapsula metainformazioni e dati binari di un carattere da un documento WordProcessing, che originariamente non è utilizzato nel documento dell'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) caricata, ma funge da carattere di sostituzione per quelli che non possono essere trovati sulla macchina di destinazione. I caratteri sostituiti esistono solo per la famiglia di formati WordProcessing.

Struttura immutabile. Le sue istanze sono prodotte e restituite dall'API pubblica [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) e normalmente non dovrebbero essere create dall'utente. Per ulteriori dettagli, consultare la documentazione: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Il tipo WordProcessingSubstitutedFontInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Serializza le informazioni sul carattere come una regola @font-face e le scrive nel writer di testo specificato. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Restituisce una stringa di debug contenente le informazioni sul carattere nel formato "original-name -> substituted-name style, format". |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Il contenuto del carattere sostituito come array di byte. Non è mai None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Il nome della famiglia del carattere sostituito, senza stile. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Il formato di questo carattere sostituito (non originale). |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Il nome della famiglia del carattere originale, che non può essere trovato su una macchina target, senza stile. Non è mai nullo o una stringa vuota. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Lo stile del carattere originale — può essere Regular, Bold, Italic o Bold Italic. |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
