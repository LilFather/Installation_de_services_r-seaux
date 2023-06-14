
Rapport Intermédiaire SAE R2.03
===

---

__Auteur__ : Mirey Kellian - TAS Atilla
__Contact__ : kellian.mirey.etu@univ-lille.fr - atilla.tas.etu@univ-lille.fr

Présentation rapport
---

Le rapport consiste à décrire notre installation d'une machine virtuelle avec Debian 11 comme système d'exploitation, MATE comme environnement graphique, et 2 utilisateurs : root et user. Puis une installation automatisée en modifiant le
fichier de pré-configuration. Et pour finir une installation de Gitea et une
utilisation simple de ce dernier.
Le rapport regroupe ensuite les réponses de culture informatique et par rapport à notre machine auxquelles nous avons répondu, ainsi que quelques informations à
propos la distribution Debian et quelques questions préliminaires sur Gitea.

Commandes de conversion
---

Convertir du markdown au pdf:

```bash
pandoc rapport_final.md -o rapport_final.pdf --from markdown --template eisvogel --listings --number-sections --filter pandoc-latex-environment
```

Convertir du markdown au html:

```bash
pandoc -s -o rapport.html rapport.md
```
