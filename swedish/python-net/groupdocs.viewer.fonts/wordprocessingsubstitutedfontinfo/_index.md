---
title: "WordProcessingSubstitutedFontInfo klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Inkapslar metainformation och binär data för ett teckensnitt från ett WordProcessing-dokument, som ursprungligen inte används i det laddade Viewer-instansdokumentet, men fungerar som ett ersättningsteckensnitt för de som…"
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Inkapslar metainformation och binär data för ett teckensnitt från ett WordProcessing-dokument, som ursprungligen inte används i det laddade [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)-instansdokumentet, men fungerar som ett ersättningsteckensnitt för de som inte kan hittas på målmaskinen. Ersatta teckensnitt finns endast för WordProcessing-formatfamiljen.

Oföränderlig struct. Dess instanser skapas och returneras av den offentliga API:n [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) och bör normalt inte skapas av användaren. För detaljer, se dokumentationen: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

WordProcessingSubstitutedFontInfo-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Serialiserar teckensnittsinfo som en @font-face-atregel och skriver den till den angivna textskrivaren. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Returnerar en felsökningssträng som innehåller teckensnittsinformation i formatet "original-name -> substituted-name style, format". |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Innehållet i det ersatta teckensnittet som en bytearray. Det är aldrig None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Familjenamnet för det ersatta teckensnittet, utan stil. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Formatet för detta ersatta (inte ursprungliga) teckensnitt. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Familjenamnet för det ursprungliga teckensnittet, som inte kan hittas på en målmaskin, utan stil. Är aldrig null eller en tom sträng. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Stilen för det ursprungliga teckensnittet — kan vara Regular, Bold, Italic eller Bold Italic. |

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
