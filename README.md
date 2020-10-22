# my-vue-cli-app

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

# Cours de Vue

### Les composants

Les composants monofichiers  permettent de créer des éléments HTML personnalisés qui encapsulent leur comportement d'une manière facilement maintenable. Ils constituent l'une des meilleures caractéristiques de Vue et peuvent être identifiés par leur extension .vue. Ils sont composés de trois blocs primaires :

Script - où vit votre JavaScript ;
Template - où vit votre HTML ;
Style - où vit votre CSS.

```vue.js
<script>
export default {
	name: 'HomeLink'
}
</script>

<template>
	<a href="/">Accueil</a> 
</template>

<style>
	a {
		text-decoration: none;
	}
</style>
```

Les composants monofichiers permettent d'encapsuler notre logique, notre contenu et nos styles de façon à faciliter leur maintenance et leur évolution. On tirera également parti des meilleures pratiques, puisque le processus de construction séparera notre code en packages corrects au moment du build.
