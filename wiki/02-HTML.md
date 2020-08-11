# HTML

*  🔖 **Document**
*  🔖 **Balises**
*  🔖 **Structures**
*  🔖 **Formulaires**

___

## 📑 Document

🔗 [HTML](https://fr.wikipedia.org/wiki/Hypertext_Markup_Language)

Un document exprimé en `HyperText Markup Language` utilise une structure sémantique composée de balises. Actuellement la `version 5` ne relie pas sa sémantique à une version d'un `Document Type Definition` et reste donc ouvert à l'utilisation de balises personnalisées.

Il faut faire l'analogie avec le protocole HTTP et un document HTML. Un document HTML possède une structure imposée.

* Nom de fichier
* Doctype
* Head
* Body

#### Nom de fichier

Correspondant à l'url, un fichier possède l'extension `.html` et son nommage de fait en minuscule sans caractères spéciaux. Par défaut le fichier `index.html` est lu par le serveur en l’absence d'url pointant sur un fichier précis.

#### Doctype

Sans lien vers le `dtd`, ce doctype indique une `version 5`. Le document est déclaré par une balise `html`.

```html
<!DOCTYPE html>
<html></html>
```

#### Head

La balise head contient des informations supplémentaires, le titre, le charset, des liens et autres meta données.

```html
<!DOCTYPE html>
<html>
    <head></head>
</html>
```

#### Body

La balise body contient l'information destinée à l'affichage.

```html
<!DOCTYPE html>
<html>
    <head></head>
    <body></body>
</html>
```

___

## 📑 Balises

### 🏷️ **Définition**

Les balises indiquent au navigateur comment afficher le document, certaines balises permettent d'intégrer différents médias comme des images, des vidéos ou des musiques parmi le texte de la page. Il existe deux types de balises.

* Fermante: contiennent de l'information

```html
<div></div>
```

* Auto fermante: ne contiennent pas d’information. En HTML le `/` de fin est facultatif.

```html
<br/>
```

Les balises possèdent une mise en forme par défaut qu'il faut connaître pour maîtriser la mise en forme du document. Elle ont un sens sémantique et il y a des règles les concernant, comme ne pas mettre un paragraphe dans un titre. l'utilisation de chaque balise demande une recherche sur son intégration et sa sémantique.

### 🏷️ **Attributs**

Une balise peut posséder des attributs. Entre les chevrons un attribut possède ou non une valeur. Ils peuvent avoir un impact sur la mise en forme ou la fonctionnalité de la balise, ou servir uniquement de point de repère pour les styliser.

```html
<div class="container"></div>
```

L'ensemble des balises possèdent des attributs communs et certaines des attributs plus particuliers qui les concerne.

```html
<img src="mon-image.jpg"></div>
```

### 🏷️ **Reference**

* `<!--...-->`: Defines a comment
* `<!DOCTYPE>`:	Defines the document type
* `<a>`: Defines a hyperlink
* `<abbr>`: Defines an abbreviation or an acronym
* `<acronym>`: Not supported in HTML5. Use * `<abbr> instead.
Defines an acronym
* `<address>`: Defines contact information for the author/owner of a document
* `<applet>`: Not supported in HTML5. Use * `<embed> or * `<object> instead.
Defines an embedded applet
* `<area>`: Defines an area inside an image-map
* `<article>`: Defines an article
* `<aside>`: Defines content aside from the page content
* `<audio>`: Defines embedded sound content
* `<b>`: Defines bold text
* `<base>`: Specifies the base URL/target for all relative URLs in a document
* `<basefont>`: Not supported in HTML5. Use CSS instead.
Specifies a default color, size, and font for all text in a document
* `<bdi>`: Isolates a part of text that might be formatted in a different direction from other text outside it
* `<bdo>`: Overrides the current text direction
* `<big>`: Not supported in HTML5. Use CSS instead.
Defines big text
* `<blockquote>`: Defines a section that is quoted from another source
* `<body>`: Defines the document's body
* `<br>`: Defines a single line break
* `<button>`: Defines a clickable button
* `<canvas>`: Used to draw graphics, on the fly, via scripting (usually JavaScript)
* `<caption>`: Defines a table caption
* `<center>`: Not supported in HTML5. Use CSS instead.
Defines centered text
* `<cite>`: Defines the title of a work
* `<code>`: Defines a piece of computer code
* `<col>`: Specifies column properties for each column within a * `<colgroup> element 
* `<colgroup>`: Specifies a group of one or more columns in a table for formatting
* `<data>`: Adds a machine-readable translation of a given content
* `<datalist>`: Specifies a list of pre-defined options for input controls
* `<dd>`: Defines a description/value of a term in a description list
* `<del>`: Defines text that has been deleted from a document
* `<details>`: Defines additional details that the user can view or hide
* `<dfn>`: Specifies a term that is going to be defined within the content
* `<dialog>`: Defines a dialog box or window
* `<dir>`: Not supported in HTML5. Use `<ul>` instead.
Defines a directory list
* `<div>`: Defines a section in a document
* `<dl>`: Defines a description list
* `<dt>`: Defines a term/name in a description list
* `<em>`: Defines emphasized text 
* `<embed>`: Defines a container for an external application
* `<fieldset>`: Groups related elements in a form
* `<figcaption>`: Defines a caption for a `<figure>` element
* `<figure>`: Specifies self-contained content
* `<font>`: Not supported in HTML5. Use CSS instead.
Defines font, color, and size for text
* `<footer>`: Defines a footer for a document or section
* `<form>`: Defines an HTML form for user input
* `<frame>`: Not supported in HTML5.
Defines a window (a frame) in a frameset
* `<frameset>`: Not supported in HTML5.
Defines a set of frames
* `<h1> to <h6>`: Defines HTML headings
* `<head>`: Contains metadata/information for the document
* `<header>`: Defines a header for a document or section
* `<hr>`: Defines a thematic change in the content
* `<html>`: Defines the root of an HTML document
* `<i>`: Defines a part of text in an alternate voice or mood
* `<iframe>`: Defines an inline frame
* `<img>`: Defines an image
* `<input>`: Defines an input control
* `<ins>`: Defines a text that has been inserted into a document
* `<kbd>`: Defines keyboard input
* `<label>`: Defines a label for an `<input>` element
* `<legend>`: Defines a caption for a `<fieldset>` element
* `<li>`: Defines a list item
* `<link>`: Defines the relationship between a document and an external resource (most used to link to style sheets)
* `<main>`: Specifies the main content of a document
* `<map>`: Defines an image-map
* `<mark>`: Defines marked/highlighted text
* `<meta>`: Defines metadata about an HTML document
* `<meter>`: Defines a scalar measurement within a known range (a gauge)
* `<nav>`: Defines navigation links
* `<noframes>`: Not supported in HTML5.
Defines an alternate content for users that do not support frames
* `<noscript>`: Defines an alternate content for users that do not support client-side scripts
* `<object>`: Defines a container for an external application
* `<ol>`: Defines an ordered list
* `<optgroup>`: Defines a group of related options in a drop-down list
* `<option>`: Defines an option in a drop-down list
* `<output>`: Defines the result of a calculation
* `<p>`: Defines a paragraph
* `<param>`: Defines a parameter for an object
* `<picture>`: Defines a container for multiple image resources
* `<pre>`: Defines preformatted text
* `<progress>`: Represents the progress of a task
* `<q>`: Defines a short quotation
* `<rp>`: Defines what to show in browsers that do not support ruby annotations
* `<rt>`: Defines an explanation/pronunciation of characters (for East Asian typography)
* `<ruby>`: Defines a ruby annotation (for East Asian typography)
* `<s>`: Defines text that is no longer correct
* `<samp>`: Defines sample output from a computer program
* `<script>`: Defines a client-side script
* `<section>`: Defines a section in a document
* `<select>`: Defines a drop-down list
* `<small>`: Defines smaller text
* `<source>`: Defines multiple media resources for media elements (* `<video> and * `<audio>)
* `<span>`: Defines a section in a document
* `<strike>`: Not supported in HTML5. Use `<del>` or `<s>` instead.
Defines strikethrough text
* `<strong>`: Defines important text
* `<style>`: Defines style information for a document
* `<sub>`: Defines subscripted text
* `<summary>`: Defines a visible heading for a `<details>` element
* `<sup>`: Defines superscripted text
* `<svg>`: Defines a container for SVG graphics
* `<table>`: Defines a table
* `<tbody>`: Groups the body content in a table
* `<td>`: Defines a cell in a table
* `<template>`: Defines a container for content that should be hidden when the page loads
* `<textarea>`: Defines a multiline input control (text area)
* `<tfoot>`: Groups the footer content in a table
* `<th>`: Defines a header cell in a table
* `<thead>`: Groups the header content in a table
* `<time>`: Defines a specific time (or datetime)
* `<title>`: Defines a title for the document
* `<tr>`: Defines a row in a table
* `<track>`: Defines text tracks for media elements (`<video>` and * `<audio>`)
* `<tt>`: Not supported in HTML5. Use CSS instead.
Defines teletype text
* `<u>`: Defines some text that is unarticulated and styled differently from normal text
* `<ul>`: Defines an unordered list
* `<var>`: Defines a variable
* `<video>`: Defines embedded video content
* `<wbr>`: Defines a possible line-break

___

## 📑 Structures

Nous pouvons séparer les balises en deux catégories, les structurantes et les non structurantes.

### 🏷️ **Non structurante**

#### Head

Dans le head elles représentent des information additionnelles.

* **Meta**: possède généralement `name` et `content` pour définir le type de la meta et la valeur associée. S'utilise également avec d'autres attributs comme le `charset`.

```html
<meta charset="utf-8" />
```

```html
<meta name="description" content="La description de la page." />
```

* **Title**: Affiche le titre de la page dans l'onglet du navigateur

```html
<title>Ma page web</title>
```

* **Link**: utilise `rel` pour déterminer le type de relation avec le média chargé avec `href`.

```html
<link type="text/css" rel="stylesheet" href="mon-style.css" />
```

* **Script**: utilise `src` pour charger le média.

```html
<script type="text/javascript" src="mon-script.js"></script>
```

#### Body

Dans le body généralement elles structurent du texte en permettant une découpe en ligne comme du gras, un lien. Elles sont de tyle `inline`. 

* **Span**: sectione un texte afin d'appliquer un repère pour le css, javascript ou autre.

```html
Ceci est <span class="rouge">ma première</span> page web
```

* **A**: crée des liens, utilise href pour définir la cible, target pour décider de l'emplacement de l'ouverture de la cible.

```html
<a href="http://google.com" targer="_blank">Google</a>
```

* **Img**: utilise src pour charger le média et alt pour un texte alternatif si le média n'est pas chargé.

```html
<img src="mon-image.jpg" alt="Mon image" />
```

* **Strong**: définit un texte comme important.

```html
Ceci est <strong>ma première page web</strong>
```

___

👨🏻‍💻 Manipulation

Complétez le fichier `index.html` pour y ajouter des balises utiles pour le head. Reliez votre document à un fichier `app.css` et `app.js` situés dans des dossiers `/js` et `/css` eux même situés dans un dossier `/assets`.

___

### 🏷️ **Structurantes**

elles structurent le document, impose un retour à la ligne et possède une sémantique indiquant qu'un contenu sous thématique est regroupé. Elles sont de type `block`.

#### HTML5

Cette version apporte de nouvelles balises.

```html
<body>
    <header>
        <nav></nav>
    </header>
    <main>
        <h1>Titre</h1>
        <section>
            <h2>Sous titre</h2>
            <article></article>
        </section>
    </main>
    <footer>
    </footer>
</body>
```

Au lieu de séparer les blocs avec des `div` ne possédant pas de sens sémantique, les balises HTML5 permettent de séparer le contenu principal ou d'identifier un élément de navigation.

#### Titres

Les titres sont de 6 niveaux, de `h1` à `h6`.

```html
<h1>Principal Title</h1>
```

#### Pargraphe

Il est important pour une problématique de référencement d'avoir décalré un titre avant de déclarer du contenu dans un paragraphe.

```html
<p>Paragraphe</p>
```

#### Listes

Les listes non ordonnées peuvent s'`encapsuler` . Une `liste` possède un `élément de liste` et n'autorise pas d'autres éléments de type block à part une autre liste.

```html
<ul>
    <li>First Item</li>
    <li>Second Item</li>
    <li>
        Sub List
        <ul>
            <li>First Item</li>
        </ul>
    </li>
<ul>
```

#### Tableaux

Ils permettent une mise en forme sommaire mais utile, largement utilisés avant l'apparition du CSS. Il est possible de faire glisser visuelment une cellule sur pluieurs colonnes ou lignes en utilisant leur attributs.

```html
<table>
    <thead>
        <tr>
            <th>Nom</th>
            <th>Compétence</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Mathieu</td>
            <td>C++</td>
        </tr>
    </tbody>
</table> 
```
___

👨🏻‍💻 Manipulation

Complétez le fichier `index.html` pour y ajouter du contenu en utilisant les balises adaptées, une entête avec une navigation vers les futures pages, un contenu principal et un footer. Cette page représente votre `Product Vision`. C'est un travail individuel.

___

## 📑 Formulaires

🔗 [Formulaires](https://developer.mozilla.org/fr/docs/Web/HTML/Element#Formulaires)

Les éléments qui receuille des données doivent être contenu dans un formulaire.

* **Form**: utilise `method` pour définir la méthode HTTP de communicaiton et `action` pour cibler la page qui est responsable du traitement de l'information envoyée.

```html
<form method="post" action=""></form>
```

### 🏷️ **Elements**

Les éléments du formulaire recuille les données ou déclenchent l'envoie de ce dernier. Pour que la valeur d'un élément soit envoyée il faut que l'élément possède une valeur à son attribut `name`.

#### 🔗 [Input](https://developer.mozilla.org/fr/docs/Web/HTML/Element/Input)

Pour réculter un texte sur une ligne, une date, une couleur, un interval, un mail, un numéro de téléhpone ete autre, la balise `input` se déclinera avec son attribut `type` et d'autres complémentaires.

```html
<input type="text" placeholder="Votre pseudo" name="my-pseudo"/>
```

```html
<input type="phone" name="my-phone"/>
```

Un input peut déclancher l'envoie d'unformulaire s'il est cliqué et possède le type `submit`. Il est possible d'envoyer le formulaire en utilisant également la balise `button`.

```html
<input type="submit"/>
```

#### 🔗 [Textarea](https://developer.mozilla.org/fr/docs/Web/HTML/Element/Textarea)

Pour récolter du texte su plusieurs lignes la balise `textarea` est utilisée accompagnée d'attributs de mise en forme.

```html
<textarea rows="10" cols="50" name="my-text">Vous pouvez écrire ici.</textarea>
```

#### 🔗 [Select](https://developer.mozilla.org/fr/docs/Web/HTML/Element/select)

Pour fournir une liste d'options la balise `select` est utilisée accompagnée de balise `option`. La balise `option` utilise l'attribut `value` pour représenter la valeur en rapport avec l'option. Il est possible de rouper les options.

```html
<select name="my-select">
    <option value="a">Dog</option>
    <option value="b">Cat</option>
</select>
```

### 🏷️ **Labels**

Un label permet à l'utilisateur de relier une information descriptive avec un élément du formulaire et une accesskey. En cliquant sur un label relié à un élément l'utilisateur se retrouve en mode saisie dans cet élément.

```html
<label for="my-phone">Phone number</label>
<input id="my-phone" type="phone" name="my-phone"/>
```
___

👨🏻‍💻 Manipulation

Complétez le fichier `index.html` pour y ajouter un ou des formulaires en fonction de votre cas de figure. Une barre de recherche, un abonement news letter ou un formulaire de contact.

___