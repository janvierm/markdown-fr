# Titres

Comme nous avons commencé à écrire un document markdown, nous avons besoin d'ajouter un titre et quelques sous-titres.

Markdown supporte deux styles de titres, Setext et atx.

Les titres de style Setext sont "soulignés" par des signes égal (pour les titres de niveau 1) et des tirets (pour les titres de niveau 2. Par exemple ):

```
Ceci est un titre H1
=============

Ceci est un titre H2
-------------
```

Cela fonctionne avec n'importe quel nombre de = ou -.

Les titres de style atx utilisent de 1 à 6 caractères dièse au début de la ligne, correspondant aux niveaux de titre 1-6. Par exemple :

```
# Ceci est un titre H1

## Ceci est un titre H2

###### Ceci est un titre H6
```

Vous pouvez éventuellement "fermer" les titres de style atx. C'est purement cosmétique : vous pouvez utiliser cette méthode si vous pensez que le rendu est meilleur. Pas besoin d'utiliser le même nombre de caractères dièse avant ou après le titre. (Le nombre de dièses au début déterminent le niveau du titre.) :

```
# Ceci est un titre H1 #

## Ceci est un titre H2 ##

### Ceci est un titre H3 ######
```


---

Voilà un quiz à propos des titres markdown.

Sélectionnez les titres valides :
- [x] `# bonjour`
- [ ] `#bonjour`

> Les titres ont besoin d'un espace entre le dièse et le texte.

Sélectionnez les titres valides :
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Seulement "=" et "-" sont acceptés pour souligner un titre.

---
