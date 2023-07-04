# Thème MMI

Pour installer le thème mmibordeaux-hugo-theme dans votre repository
```
git submodule add git@github.com:mmibordeaux/mmibordeaux-hugo-theme.git themes/mmibordeaux-hugo-theme
```

Dans le fichier `assets/sass/main.sass`, remplacer par :
```
@import "_theme/utils"
@import "_fonts"
@import "_configuration"
@import "mmibordeaux-hugo/theme"
@import "_style"
```
