---
title: "Κλάση Tile"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά την περιοχή σχεδίασης."
type: docs
url: /el/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Αναπαριστά την περιοχή σχεδίασης.

Για λεπτομέρειες, δείτε την τεκμηρίωση στη διεύθυνση https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Ο τύπος Tile εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Επιστρέφει τη συντεταγμένη X του υψηλότερου δεξιού σημείου στο σχέδιο όπου τελειώνει το tile. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Επιστρέφει τη συντεταγμένη Y του υψηλότερου δεξιού σημείου στο σχέδιο όπου τελειώνει το tile. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | Το ύψος του tile σε εικονοστοιχεία. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | Η συντεταγμένη X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | Η συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | Το πλάτος του tile σε εικονοστοιχεία. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions, Tile

with Viewer("sample.dwg") as viewer:
    view_info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    width = view_info.pages[0].width
    height = view_info.pages[0].height

    columns, rows = 2, 2
    tile_width = width / columns
    tile_height = height / rows

    view_options = HtmlViewOptions.for_embedded_resources(
        "output/drawing_tile_{0}.html"
    )
    for i in range(columns):
        for j in range(rows):
            tile = Tile(i * tile_width, j * tile_height, tile_width, tile_height)
            view_options.cad_options.tiles.append(tile)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
