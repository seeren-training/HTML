# SEO

*  🔖 **Schema**
*  🔖 **Balisage**

___

## 📑 Schema

L'attribut universel itemtype définit l'URL du vocabulaire qui sera utilisé pour définir les propriétés des objets dans la structure de données.

> Google et les autres moteurs de recherche participent au vocabulaire défini par schema.org pour structurer les données. Ce vocabulaire définit un ensemble standard de types et de noms de propriétés. Par exemple MusicEvent indique un événement musical dont les propriétés startDate et location utilisées pour définir les détails du concert. Dans ce cas, l'URL http://schema.org/MusicEvent sera l'URL utilisée pour l'attribut itemtype et les propriétés startDate et location seront les propriétés utilisées, définies par http://schema.org/MusicEvent.

La première étape est d'identifier le schéma qui correspond à votre donnée.

[Schemas](http://schema.org/)

### 🏷️ **Utilisation**

L'attribut itemtype peut uniquement être défini pour les éléments qui ont un attribut itemscope.

```html
<div itemscope itemtype="http://schema.org/Product">

</div>
```

Dans l'exemple précédent, le bloc dérit un produit et poura utiliser les attributs du schéma Product pour expliciter la nature de son contenu.
___

## 📑 Balisage

L'attribut universel itemprop est utilisé afin d'ajouter des propriétés à un objet. C'est un attribut universel et chaque élément HTML peut donc avoir un attribut itemprop qui permettra de former un couple de nom et de valeur.

### 🏷️ **Utilisation**

Apres avoir identifié un  schéma, il faut se reporter à la liste des propriétées disponibles pour les appliquer sur des balises délimitant le contenu en rapport.

```html
<div itemscope itemtype="http://schema.org/Movie">
  <h1 itemprop="name">Avatar</h1>
  <span>Director:
    <span itemprop="director">James Cameron</span>
    (born August 16, 1954)
  </span>
  <span itemprop="genre">Science fiction</span>
  <a href="../movies/avatar-theatrical-trailer.html"
    itemprop="trailer">Trailer</a>
</div>
```

___

👨🏻‍💻 Manipulation

Utiliser les micro données pour expliciter le sens de votre contenu.

___