---
title: "FontStyles"
second_title: "Αναφορά API του GroupDocs.Viewer for .NET"
description: "Αναπαριστά 4 πιθανά στυλ της γραμματοσειράς που χρησιμοποιείται στο έγγραφο Regular, Bold, Italic ή Bold Italic"
type: docs
weight: 810
url: /el/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

Αντιπροσωπεύει 4 πιθανές μορφές της γραμματοσειράς, που χρησιμοποιούνται στο έγγραφο: Regular, Bold, Italic ή Bold Italic

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | Δημιουργεί ένα στιγμιότυπο [`FontStyles`](../fontstyles) από τις καθορισμένες σημαίες bold και italic |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | Δείχνει εάν αυτό το στιγμιότυπο [`FontStyles`](../fontstyles) έχει ενεργοποιημένη τη σημαία **bold** (`true`) ή απενεργοποιημένη (`false`) |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | Δείχνει εάν αυτό το στιγμιότυπο [`FontStyles`](../fontstyles) έχει ενεργοποιημένη τη σημαία **italic** (`true`) ή απενεργοποιημένη (`false`) |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | Όνομα αυτού του στυλ γραμματοσειράς |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | Δείχνει εάν αυτό το στιγμιότυπο [`FontStyles`](../fontstyles) είναι ίσο με το καθορισμένο |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | Δείχνει εάν αυτό το στιγμιότυπο [`FontStyles`](../fontstyles) είναι ίσο με το καθορισμένο χωρίς μετατροπή |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | Επιστρέφει έναν κωδικό hash-code αυτού του στιγμιότυπου |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | Επιστρέφει το όνομα αυτού του στυλ γραμματοσειράς, ίδιο με το [`Name`](./name) |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | Προσπαθεί να αναλύσει τη συγκεκριμένη ακατέργαστη συμβολοσειρά ως όνομα στυλ γραμματοσειράς |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | Συνδυάζει (συγχωνεύει) δύο καθορισμένα στυλ γραμματοσειράς και παράγει νέο προκύπτον στυλ γραμματοσειράς, όπου οι σημαίες συγχωνεύονται (ένωση) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | Ελέγχει εάν δύο τιμές [`FontStyles`](../fontstyles) είναι ίσες |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | Μετατρέπει το καθορισμένο στιγμιότυπο [`FontStyles`](../fontstyles) στο ισοδύναμο οκτάδα (8-bit bitfield) στο δεκαδικό εύρος [0..3] |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | Ελέγχει εάν δύο τιμές [`FontStyles`](../fontstyles) δεν είναι ίσες |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | Αφαιρεί το δεύτερο (αφαιρετέο) καθορισμένο στυλ γραμματοσειράς από το πρώτο (μειωτέο) καθορισμένο στυλ γραμματοσειράς και παράγει νέο προκύπτον στυλ γραμματοσειράς, όπου εμφανίζονται μόνο εκείνες οι σημαίες από το πρώτο τελεστή που δεν βρίσκονται στον δεύτερο τελεστή (διαφορά) |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Στυλ γραμματοσειράς Bold (μόνο bold, χωρίς italic) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | Στυλ γραμματοσειράς BoldItalic (bold και italic μαζί) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Στυλ γραμματοσειράς Italic (μόνο italic, χωρίς bold) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Στυλ γραμματοσειράς Regular, προεπιλεγμένη τιμή (χωρίς bold και italic) |

### Παρατηρήσεις

Αμετάβλητο struct με βολικό API και λειτουργίες συνδυασμού

### Δείτε επίσης

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από το xmldocmd για το GroupDocs.Viewer.dll -->
