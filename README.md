# Hugo templates - website gilets-jaunes-71_dot_fr
---

Pour générer le site web (dans le dossier "public/" par défaut), éditer le fichier config.toml qui se trouve à la racine puis exécuter : 
```
hugo
```

Pour afficher un aperçu du site en utilisant le server web inclu avec Hugo :
```
hugo server
```

Les layouts utilisés pour la création du site sont dans le dossier "themes" du répertoire racine. Le chemin exact : 
```
./gj71/themes/hugo-creative-theme/layouts
```

Le fichier "index.html" est utilisé par défaut par Hugo pour générer chacune des pages du site. Celui-ci inclu différents layouts présents dans le sous-dossier "partials/". Les noms des fichiers sont généralement explicites (nav.html, head.html, ...).   

D'autres fichiers intéressants (stylesheet, js, img, ...) sont présents dans le dossier :  
```
./gj71/themes/hugo-creative-theme/static
```


# Edition des articles
---

Le différentes pages du site se trouve dans le dossier "./content/post/".  
Les articles qui seront mis en avant sur la page principale du site sont quant à eux dans le dossier "./data/projects/".

Tout cela a été fait à la va vite en adaptant un thème disponible à cette adresse : https://github.com/digitalcraftsman/hugo-creative-theme  
Tout ce que j'ai fait n'étant pas forcément des plus logique, ne pas hésiter à me demander (ouvrir une issue) pour plus de précisions.  






