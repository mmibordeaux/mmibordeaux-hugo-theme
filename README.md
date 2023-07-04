# Thème MMI

Pour installer le thème mmibordeaux-hugo-theme dans votre repository
```
git submodule add https://mmibordeaux/mmibordeaux-hugo-theme.git themes/mmibordeaux-hugo-theme
```

Le fichier `.gitmodules`doit ressembler à cela :
```
[submodule "themes/osuny-hugo-theme-aaa"]
	path = themes/osuny-hugo-theme-aaa
	url = https://github.com/noesya/osuny-hugo-theme-aaa.git
[submodule "themes/mmibordeaux-hugo-theme"]
	path = themes/mmibordeaux-hugo-theme
	url = https://github.com/mmibordeaux/mmibordeaux-hugo-theme.git
```

Si vous apportez des changements à ce fichier (par exemple pour passer en https, n'oubliez pas d'invoquer 
```
git submodule sync
```

Dans le fichier `assets/sass/main.sass`, remplacer par :
```
@import "_theme/utils"
@import "_fonts"
@import "_configuration"
@import "mmibordeaux-hugo/theme"
@import "_style"
```

