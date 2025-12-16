# CommandLine_cheats
Liste de ligne de commandes pour mémoire

##Ligne de commande linux

Voir la version de Ubuntu
```shell

lsb_release -a
ou
systeminfo
```

Copier un dossier d'un serveur à un dossier en local :
```shell
scp -r user@adresse-serveur:/home/adresse/serveur/app /home/adresse/local/
```

Le grep :

```shell
grep #recherche les occurences de mots à l'intérieur de fichier
grep motif fichier
grep -i motif fichier #sans tenir compte de la casse
grep -c motif fichier #(en comptant les occurences
grep -v motif fichier #inverse la recherche, en excluant le "motif"
grep expression /répertoire/fichier
grep [aFm]in /répertoire/fichier
```

