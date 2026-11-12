# Mes SecLists

Collection personnelle de listes générées, organisées par domaine et usage.

## Organisation

```text
wordlists/
  brute-force/
    usernames/
    passwords/
  discovery/
    directories/
    files/
    subdomains/
    parameters/
  file-upload/
    extension-obfuscation/
      asp_src.txt
      cfm_src.txt
      jsp_src.txt
      perl_src.txt
      php_src.txt
      sh_src.txt
      chars.txt
      covers.txt
      tails.txt
  payloads/
    sql-injection/
    xss/
    command-injection/
    path-traversal/
```

- `wordlists/` regroupe les listes du projet.
- `brute-force/` classe les noms d'utilisateur et les mots de passe.
- `discovery/` classe les noms utilisés pour découvrir des ressources.
- `file-upload/` concerne les tests de téléversement de fichiers.
- `extension-obfuscation/` regroupe les listes liées aux extensions de fichiers.
- `payloads/` classe les charges de test par type de vulnérabilité.
- Les fichiers `*_src.txt` regroupent les extensions par famille ; `chars.txt`,
  `covers.txt` et `tails.txt` regroupent les caractères, extensions de couverture
  et suffixes.

De nouveaux domaines ou usages peuvent être ajoutés sous `wordlists/` selon la
même logique. Les listes sont en UTF-8, avec une valeur par ligne ; les espaces
éventuels font partie des valeurs. Les fichiers `.gitkeep` conservent les
répertoires encore vides dans Git.
