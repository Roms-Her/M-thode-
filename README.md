# Méthode ~

## Récupérer un dépot existant pour par la suite le push.

-On créé un repo a notre nom et on garde la clef SSH de coter
par exemple S04-SQL-Roms

-On ouvre un terminal dans le dossier voulu,

```bash
$ git clone "la clef SSH du repo"
```

-On renome notre dossier cloner avec le nom donner a notre repo (exemple: S04-SQL-Roms)

-On créé on new fichier .git
```bash
$ git remote -v
```

-On lui enleve puis remet un lien vers notre repo fraichement créé
```bash
$ git init
```
```bash
-$ git remote remove origin
-$ git remote add origin "notre clef SSH"
```

-On fait notre premier push

```bash
    $ git add .
    $ git commit -m "first commit"
    $ git push origin main
```
---


