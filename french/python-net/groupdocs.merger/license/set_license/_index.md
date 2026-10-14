---
title: "set_license méthode"
second_title: "Références d'API GroupDocs.Merger pour Python via .NET"
description: 
type: docs
url: /fr/python-net/groupdocs.merger/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Appliquer une licence au processus actuel.

```python
def set_license(self, license_source):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| license_source |  | Soit un chemin de chaîne vers un fichier ``.lic`` ou un objet de type fichier lisible qui fournit les octets de licence. Les entrées de type fichier sont écrites dans un fichier temporaire avant d'être transmises au pont. |

| Lève | Description |
| :- | :- |
| `TypeError` | Si ``license_source`` n'est ni un chemin de chaîne ni un objet de type fichier lisible. |

### Voir aussi
* class [`License`](/merger/python-net/groupdocs.merger/license/)
