---
title: Connaissance de base de Vue.js
summary: >-
  Dans cet article, nous aborderons certaines connaissances de base et certains
  termes que nous rencontrerons souvent lors de l’apprentissage de Vue.js.
tags:
  - Vue
date: 2019-08-14T21:45:41.407Z
---
![Vue js](/uploads/vue-instant-search.png "Vue js")

[Vue.js](https://vuejs.org/) , "The Progressive JavaScript Framework", est un Frameworkjavascript qui nous aide à créer un site Web / une application nécessitant beaucoup d'interaction, généralement dans le forme d'une application de page unique. Vue.js a récemment un écho assez rapide parmi les développeurs web et les développeurs Javascript en raison de la facilité d'apprentissage et de mise en œuvre.

Dans cet article, nous aborderons certaines connaissances de base et certains termes que nous rencontrerons souvent lors de l’apprentissage de Vue.js.

1. **Composants Vue** 

Vue.js, comme d’autres frameworks Javascript modernes, supporte également le concept de composant. Chaque disposition de bloc est considérée comme un composant indépendant et possède son propre style et sa propre fonctionnalité, de sorte qu’il est facile de les réutiliser par chaque page de notre site Web. Chacun de ces composants sera ensuite organisé en blocs interdépendants et créera une vue complète d'une page Web.

L'utilisation de composants signifie que nous allons créer une balise personnalisée dans notre modèle HTML. Les composants de Vue.js peuvent être créés simplement avec le code suivant:

```javascript
Vue.component('todo-item', {
  template: '<li>This is a todo</li>'
})
```

À partir de la définition ci-dessus, nous pouvons utiliser ces composants dans les modèles HTML d'une manière non moins facile, comme suit:

```html
<ol>
  <todo-item></todo-item>
</ol>
```

2. **Liaison de données dans Vue**

Vue.js est en effet très inspiré par AngularJS en termes de liaisons de données, c’est pourquoi il est très facile d’apprendre Vue.js quand nous avons déjà appris AngularJS. Si dans AngularJS, nous connaissons ng-bind, dans Vue.js, nous savons v: bind, voici quelques liaisons de données dans Vue.js:

1. Relier les données en vue

Vue.js utilise la syntaxe {{}} comme indiqué dans l'image ci-dessus. Avec la syntaxe, cela signifie que nous souhaitons afficher les données existantes de notre code Javascript dans le HTML.

```html
<div id="app">
  {{ message }}
</div>
```

2. Liaison d'attribut

Comme mentionné précédemment, dans Vue.js, nous utilisons v-bind pour lier au HTML. Donc, si nous regardons l'image ci-dessus, nous voulons ajouter le titre de l'attribut à la plage en utilisant des données dynamiques à partir de JavaScript. En principe, v-bind peut être appliqué à divers attributs en HTML afin que nous puissions rencontrer de nombreuses variantes de v-bind comme v-bind: src, v-bind: classe, v-bind: alt, etc. Vue.js fournit également des raccourcis nous permettant de définir v-bind en HTML en supprimant la partie v-bind, afin que nous puissions utiliser des raccourcis tels que: title,: src,: class,: alt, etc.

```html
<div id="app-2">
  <span v-bind:title="message">
    Hover your mouse over me for a few seconds
    to see my dynamically bound title!
  </span>
</div>
```

3. Liaison de données bidirectionnelle

Comme AngularJS, Vue.js fournit également une fonctionnalité de liaison de données bidirectionnelle, ce qui signifie que toute modification de Javascript affectera la vue HTML et inversement, les modifications apportées à la vue HTML affecteront ou modifieront également la valeur de Javascript. Dans Vue.js, nous utilisons v-model pour effectuer des liaisons bidirectionnelles généralement attachées à un élément HTML, comme l'image suivante:

```html
<div id="app-6">
  <p>{{ message }}</p>
  <input v-model="message">
</div>
```

4. Liaison à un événement

Pour appeler un événement que nous avons créé en Javascript, Vue.js utilise v-on dans le modèle HTML suivi du hook d’événement à ajouter. Nous pouvons donc utiliser diverses variantes de v-on, telles que v-on: clic, v-on: flou, v-on: focus, v-on: keyup, etc.

```html
<div id="example-3">
  <button v-on:click="say('hi')">Say hi</button>
  <button v-on:click="say('what')">Say what</button>
</div>
```

```javascript
new Vue({
  el: '#example-3',
  methods: {
    say: function (message) {
      alert(message)
    }
  }
})
```

Vue.js fournit également un raccourci pour faire cette liaison d'événement en utilisant @, afin que nous puissions abréger des choses telles que: @click, @ blur, @ focus, etc.
