---
title: "groupdocs.viewer.fonts"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Configurazione del caricamento e della sostituzione dei font."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Configurazione del caricamento e della sostituzione dei font.

### Classi
| Classe | Descrizione |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Rappresenta la cartella che contiene i font TrueType. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Rappresenta 4 possibili stili del carattere, utilizzati nel documento: Regular, Bold, Italic o Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Rappresenta un'interfaccia comune per tutti i caratteri che possono essere estratti da tutte le famiglie supportate di formati di documento: PDF, WordProcessing, Spreadsheet e Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Incapsula i metadati e i dati binari di un carattere PDF caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), che può essere incorporato nel documento o installato sul sistema operativo in cui gira GroupDocs.Viewer. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Rappresenta metainformazioni e dati binari di un carattere da un documento Presentation caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Il carattere è utilizzato nel contenuto del documento e può essere incorporato nel documento o installato nel sistema operativo in cui gira il visualizzatore. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Incapsula metainformazioni e dati binari di un carattere da un documento spreadsheet caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). I documenti spreadsheet non possono contenere caratteri incorporati, quindi un carattere restituito da [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) viene installato nel sistema operativo in cui gira il visualizzatore. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Incapsula metainformazioni e dati binari di un carattere da un documento WordProcessing caricato in un'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Incapsula metainformazioni e dati binari di un carattere da un documento WordProcessing, che originariamente non è utilizzato nel documento dell'istanza di [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) caricata, ma funge da carattere di sostituzione per quelli che non possono essere trovati sulla macchina di destinazione. I caratteri sostituiti esistono solo per la famiglia di formati WordProcessing. |

### Enumerazioni
| Enum | Descrizione |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Rappresenta un'interfaccia marker per le font di origine. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
