---
title: Page
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Inizializza una nuova istanza diPagegroupdocs.viewer.results/page classe.
type: docs
weight: 10
url: /it/net/groupdocs.viewer.results/page/page/
---
## Page() {#constructor}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page()
```

### Guarda anche

* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page(int number, bool visible)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| number | Int32 | Il numero di pagina. |
| visible | Boolean | L'indicatore di visibilità della pagina. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*number* è minore o uguale a zero. |

### Guarda anche

* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page(int number, string name, bool visible)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| number | Int32 | Il numero di pagina. |
| name | String | Il foglio di lavoro o il nome della pagina. |
| visible | Boolean | L'indicatore di visibilità della pagina. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*number* è minore o uguale a zero. |

### Guarda anche

* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| number | Int32 | Il numero di pagina. |
| visible | Boolean | L'indicatore di visibilità della pagina. |
| width | Int32 | La larghezza della pagina in pixel durante la visualizzazione in formato JPG o PNG. |
| height | Int32 | L'altezza della pagina in pixel quando viene visualizzata come JPG o PNG. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*number* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*width* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*height* è minore o uguale a zero. |

### Guarda anche

* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| number | Int32 | Il numero di pagina. |
| name | String | Il foglio di lavoro o il nome della pagina. |
| visible | Boolean | L'indicatore di visibilità della pagina. |
| width | Int32 | La larghezza della pagina in pixel durante la visualizzazione in formato JPG o PNG. |
| height | Int32 | L'altezza della pagina in pixel quando viene visualizzata come JPG o PNG. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*number* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*width* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*height* è minore o uguale a zero. |

### Guarda anche

* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| number | Int32 | Il numero di pagina. |
| visible | Boolean | L'indicatore di visibilità della pagina. |
| width | Int32 | La larghezza della pagina in pixel durante la visualizzazione in formato JPG o PNG. |
| height | Int32 | L'altezza della pagina in pixel quando viene visualizzata come JPG o PNG. |
| lines | List`1 | Le righe contenute nella pagina durante la visualizzazione in formato JPG o PNG con Estrazione testo abilitata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*number* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*width* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*height* è minore o uguale a zero. |
| ArgumentNullException | Lanciato quando*lines* è zero. |

### Guarda anche

* class [Line](../../line)
* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Inizializza una nuova istanza di[`Page`](../../page) classe.

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| number | Int32 | Il numero di pagina. |
| name | String | Il foglio di lavoro o il nome della pagina. |
| visible | Boolean | L'indicatore di visibilità della pagina. |
| width | Int32 | La larghezza della pagina in pixel durante la visualizzazione in formato JPG o PNG. |
| height | Int32 | L'altezza della pagina in pixel quando viene visualizzata come JPG o PNG. |
| lines | List`1 | Le righe contenute nella pagina durante la visualizzazione in formato JPG o PNG con Estrazione testo abilitata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*number* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*width* è minore o uguale a zero. |
| ArgumentException | Lanciato quando*height* è minore o uguale a zero. |
| ArgumentNullException | Lanciato quando*lines* è zero. |

### Guarda anche

* class [Line](../../line)
* class [Page](../../page)
* spazio dei nomi [GroupDocs.Viewer.Results](../../page)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
