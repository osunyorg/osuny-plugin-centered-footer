# Plugin Osuny : centered footer

Ce plugin centre le pied de page en desktop.

<img width="1440" height="787" alt="image" src="https://github.com/user-attachments/assets/061e1977-926c-478d-8993-58ed7edfbf84" />


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
@import "osuny-plugin-centered-footer/style"
```

## Exemples 

- https://www.postgrowth.life
- https://prototype.frenchcraftguild.fr/fr/
