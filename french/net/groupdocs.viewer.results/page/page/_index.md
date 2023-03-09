---
title: Page
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Initialise la nouvelle instance dePagegroupdocs.viewer.results/page classe.
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/page/page/
---
## Page() {#constructor}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page()
```

### Voir également

* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page(int number, bool visible)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| number | Int32 | Le numéro de page. |
| visible | Boolean | L'indicateur de visibilité de la page. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*number* est inférieur ou égal à zéro. |

### Voir également

* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page(int number, string name, bool visible)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| number | Int32 | Le numéro de page. |
| name | String | Le nom de la feuille de calcul ou de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*number* est inférieur ou égal à zéro. |

### Voir également

* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| number | Int32 | Le numéro de page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| width | Int32 | La largeur de la page en pixels lors de l'affichage au format JPG ou PNG. |
| height | Int32 | La hauteur de la page en pixels lors de l'affichage au format JPG ou PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*number* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*width* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*height* est inférieur ou égal à zéro. |

### Voir également

* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| number | Int32 | Le numéro de page. |
| name | String | Le nom de la feuille de calcul ou de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| width | Int32 | La largeur de la page en pixels lors de l'affichage au format JPG ou PNG. |
| height | Int32 | La hauteur de la page en pixels lors de l'affichage au format JPG ou PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*number* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*width* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*height* est inférieur ou égal à zéro. |

### Voir également

* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| number | Int32 | Le numéro de page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| width | Int32 | La largeur de la page en pixels lors de l'affichage au format JPG ou PNG. |
| height | Int32 | La hauteur de la page en pixels lors de l'affichage au format JPG ou PNG. |
| lines | List`1 | Les lignes contenues par la page lors de l'affichage au format JPG ou PNG avec l'extraction de texte activée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*number* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*width* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*height* est inférieur ou égal à zéro. |
| ArgumentNullException | Jeté quand*lines* est nul. |

### Voir également

* class [Line](../../line)
* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Initialise la nouvelle instance de[`Page`](../../page) classe.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| number | Int32 | Le numéro de page. |
| name | String | Le nom de la feuille de calcul ou de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| width | Int32 | La largeur de la page en pixels lors de l'affichage au format JPG ou PNG. |
| height | Int32 | La hauteur de la page en pixels lors de l'affichage au format JPG ou PNG. |
| lines | List`1 | Les lignes contenues par la page lors de l'affichage au format JPG ou PNG avec l'extraction de texte activée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Jeté quand*number* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*width* est inférieur ou égal à zéro. |
| ArgumentException | Jeté quand*height* est inférieur ou égal à zéro. |
| ArgumentNullException | Jeté quand*lines* est nul. |

### Voir également

* class [Line](../../line)
* class [Page](../../page)
* espace de noms [GroupDocs.Viewer.Results](../../page)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
