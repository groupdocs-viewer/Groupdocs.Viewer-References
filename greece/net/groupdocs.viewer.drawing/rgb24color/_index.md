---
title: "Rgb24Color"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αναπαριστά χρώμα 24-bit σε μορφή RGB με 8 bits για κάθε κανάλι Κόκκινο Πράσινο Μπλε. Δεν υποστηρίζει διαφάνεια."
type: docs
weight: 970
url: /el/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

Αναπαριστά χρώμα 24-bit σε μορφή RGB, με 8 bits για κάθε κανάλι (Red, Green, Blue). Δεν υποστηρίζει διαφάνεια.

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | Επιστρέφει το μέρος blue του χρώματος ως 8-bit μη υπογεγραμμένο ακέραιο [0..255] |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | Επιστρέφει το μέρος green του χρώματος ως 8-bit μη υπογεγραμμένο ακέραιο [0..255] |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | Δείχνει αν αυτή η παρουσία [`Rgb24Color`](../rgb24color) είναι προεπιλεγμένη (Μαύρο) - όλα τα 3 κανάλια είναι ορισμένα στο 0. |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | Επιστρέφει το κόκκινο μέρος του χρώματος ως 8-bit ακέραιο χωρίς πρόσημο [0..255] |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | Δημιουργεί μία τιμή [`Rgb24Color`](../rgb24color) από τα καθορισμένα κανάλια Κόκκινο, Πράσινο, Μπλε |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | Ελέγχει αυτό το χρώμα με το καθορισμένο χρώμα [`Argb32Color`](../argb32color) για ισότητα |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | Ελέγχει αυτό το χρώμα με το καθορισμένο μη μετατρεπόμενο |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | Ελέγχει αυτό το χρώμα με το καθορισμένο χρώμα [`Rgb24Color`](../rgb24color) για ισότητα |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | Επιστρέφει τη φωτεινότητα/λαμπρότητα Hue-Saturation-Lightness (HSL) για αυτήν την παρουσία [`Rgb24Color`](../rgb24color). |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | Επιστρέφει έναν κωδικό κατακερματισμού που ορίζει το τρέχον χρώμα. Δεν είναι συμβατό με το GetHashCode |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | Επιστρέφει την τιμή απόχρωσης Hue-Saturation-Lightness (HSL), σε μοίρες, για αυτό το αντικείμενο [`Rgb24Color`](../rgb24color). Εάν R == G == B, η απόχρωση είναι άσχετη και η επιστρεφόμενη τιμή είναι 0. |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | Ο κορεσμός Hue-Saturation-Lightness (HSL) για αυτό το αντικείμενο [`Rgb24Color`](../rgb24color). |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | Επιστρέφει την τιμή ARGB αυτού του αντικειμένου [`Rgb24Color`](../rgb24color), συμβατή με το Color. |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | Επιστρέφει αυτό το χρώμα σε δεκαεξαδική αναπαράσταση συμβολοσειράς. |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | Σειριοποιεί αυτό το αντικείμενο [`Rgb24Color`](../rgb24color) στη σημειογραφία συνάρτησης CSS 'rgb'. |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | Σειριοποιεί αυτό το αντικείμενο [`Rgb24Color`](../rgb24color) στη μορφή 'rgb(r, g, b)'. |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | Συγκρίνει δύο χρώματα [`Rgb24Color`](../rgb24color) και επιστρέφει μια boolean τιμή που υποδεικνύει εάν τα δύο ταιριάζουν. (2 τελεστές) |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | Συγκρίνει δύο χρώματα [`Rgb24Color`](../rgb24color) και επιστρέφει μια boolean τιμή που υποδεικνύει εάν τα δύο δεν ταιριάζουν. (2 τελεστές) |

## Άλλα μέλη

| Όνομα | Περιγραφή |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | Περιέχει όλα τα "γνωστά χρώματα", που έχουν σταθερό μοναδικό όνομα και τιμή στο πρότυπο CSS |

### Παρατηρήσεις

Αυτός ο τύπος έχει σχεδιαστεί ώστε να είναι χρήσιμος για (αλλά όχι περιορισμένο σε) λειτουργίες CSS. Δείτε περισσότερα: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Δείτε επίσης

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
