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
