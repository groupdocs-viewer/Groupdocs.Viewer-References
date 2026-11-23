---
title: "Image2DFormat"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αντιπροσωπεύει τις πιο κοινές μορφές 2D εικόνων, που υποστηρίζουν τόσο raster όσο και vector μορφές."
type: docs
weight: 960
url: /el/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

Αναπαριστά τις πιο κοινές μορφές 2D εικόνων, υποστηρίζει τόσο raster όσο και vector μορφές.

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | Τύπος εικόνας BMP |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | Τύπος διανυσματικής εικόνας EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | Τύπος εικόνας GIF |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | Τύπος εικόνας ICON |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | Τύπος εικόνας JPEG |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | Τύπος εικόνας PNG |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | Τύπος διανυσματικής εικόνας SVG |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | Τύπος raster εικόνας TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | Απροσδιόριστος τύπος εικόνας - ειδική τιμή, η οποία δεν θα έπρεπε να εμφανίζεται κανονικά |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | Τύπος διανυσματικής εικόνας WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | Επέκταση αρχείου (χωρίς τον αρχικό χαρακτήρα τελείας) ενός συγκεκριμένου τύπου εικόνας σε πεζά. Για την τιμή [`Undefined`](./undefined) επιστρέφει τη συμβολοσειρά 'undefined'. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | Δείχνει εάν αυτή η συγκεκριμένη μορφή είναι διανυσματική (`true`) ή ραστερ (`false`) |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | Κωδικός MIME ενός συγκεκριμένου τύπου εικόνας ως συμβολοσειρά. Για τον τύπο Undefined επιστρέφει μια συμβολοσειρά 'unsefined'. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | Επιστρέφει ένα επίσημο όνομα αυτού του μορφότυπου εικόνας. Ποτέ δεν επιστρέφει NULL. Εάν η παρουσία δεν είναι κατεστραμμένη, δεν ρίχνει ποτέ εξαίρεση. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | Επιστρέφει την τιμή ImageFormat, η οποία είναι ισοδύναμη με την επέκταση του ονόματος αρχείου, η οποία εξάγεται από το καθορισμένο όνομα αρχείου |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | Επιστρέφει την τιμή [`Image2DFormat`](../image2dformat), η οποία είναι ισοδύναμη με τον καθορισμένο κωδικό MIME |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | Καθορίζει εάν αυτή η παρουσία είναι ίση με την καθορισμένη "[`Image2DFormat`](../image2dformat)" παρουσία |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | Καθορίζει εάν αυτή η παρουσία είναι ίση με το καθορισμένο μη μετατρεπόμενο αντικείμενο, το οποίο προφανώς είναι μια άλλη "[`Image2DFormat`](../image2dformat)" παρουσία |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού, ο οποίος είναι ένας αμετάβλητος αριθμός για αυτή τη συγκεκριμένη παρουσία |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | Επιστρέφει την ιδιότητα [`Name`](./name) |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | Ορίζει εάν δύο συγκεκριμένες παρουσίες [`Image2DFormat`](../image2dformat) είναι ίσες |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | Ορίζει εάν δύο συγκεκριμένες παρουσίες [`Image2DFormat`](../image2dformat) δεν είναι ίσες |

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
