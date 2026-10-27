---
title: "properti disable_font_license_verifications"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

Properti ini menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen XPS/OXPS saat ini.

Banyak operasi dengan font tidak dapat dijalankan jika dilarang oleh lisensi font. Misalnya, beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font tersebut. Opsi ini memungkinkan Anda melewatkan verifikasi aturan tersebut.

Berhati-hatilah saat menggunakan flag ini. Ketika flag ini diaktifkan, itu berarti orang yang mengatur flag ini mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi atau hukum. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hukum hak cipta. Nilai default adalah `False`.

Untuk contoh kode, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Lihat Juga
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
