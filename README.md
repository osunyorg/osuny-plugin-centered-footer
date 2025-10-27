# Plugin Osuny : centered header

Ce plugin centre le pied de page en desktop.

## Utilisation

D'abord, importer le plugin dans le site.

```bash
git submodule add git@github.com:osunyorg/osuny-plugin-centered-footer.git themes/osuny-plugin-centered-footer
```

Ensuite, ajouter le plugin comme un thème dans `config/_default/config.yaml`.

```yaml
theme: 
  - osuny
  - osuny-plugin-centered-footer
```

Enfin, importer le style dans `assets/sass/main.sass`.

```sass
@import "osuny-plugin-centered-header/footer"
```

## Exemples 

- https://www.postgrowth.life
- https://prototype.frenchcraftguild.osuny.site
