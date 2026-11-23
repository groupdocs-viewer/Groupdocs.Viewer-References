---
title: "propriété disable_font_license_verifications"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "La propriété désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

La propriété désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel.

De nombreuses opérations avec les polices ne peuvent pas être exécutées si elles sont interdites par la licence de la police. Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation pour cette police. Cette option vous permet d'ignorer la vérification de ces règles.

Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui le définit assume l'entière responsabilité des éventuelles violations de licence ou de la loi. Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement sûr de ne pas enfreindre le droit d'auteur. La valeur par défaut est `False`.

Pour un exemple de code, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Voir aussi
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
