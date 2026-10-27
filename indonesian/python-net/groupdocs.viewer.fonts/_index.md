---
title: "groupdocs.viewer.fonts"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Konfigurasi pemuatan dan substitusi font."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Konfigurasi pemuatan dan substitusi font.

### Kelas
| Kelas | Deskripsi |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Mewakili folder yang berisi font TrueType. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Menyediakan metode untuk bekerja dengan sumber guna mencari font TrueType. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Mewakili 4 gaya kemungkinan dari font, yang digunakan dalam dokumen: Regular, Bold, Italic, atau Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Mewakili antarmuka umum untuk semua font yang dapat diekstrak dari semua keluarga format dokumen yang didukung: PDF, WordProcessing, Spreadsheet, dan Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Mengkapsulkan metadata dan data biner dari font PDF yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), yang dapat disematkan dalam dokumen atau diinstal pada sistem operasi tempat GroupDocs.Viewer berjalan. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Mewakili metainfo dan data biner dari font dalam dokumen Presentation yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Font tersebut digunakan dalam konten dokumen dan dapat disematkan dalam dokumen atau diinstal pada sistem operasi tempat viewer berjalan. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Mengkapsulkan metainfo dan data biner dari font dalam dokumen spreadsheet yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Dokumen spreadsheet tidak dapat memiliki font yang disematkan, sehingga font yang dikembalikan oleh [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) diinstal pada sistem operasi tempat viewer berjalan. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Mengkapsulkan metainfo dan data biner dari font dalam dokumen WordProcessing yang dimuat ke dalam instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Mengkapsulkan metainfo dan data biner dari satu font dalam dokumen WordProcessing, yang awalnya tidak digunakan dalam dokumen instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) yang dimuat, tetapi berfungsi sebagai font substitusi bagi yang tidak dapat ditemukan pada mesin target. Font substitusi hanya ada untuk keluarga format WordProcessing. |

### Enumerasi
| Enum | Deskripsi |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Mewakili antarmuka penanda untuk sumber font. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
