# Terminal: les lignes de commandes

Qu'est-ce qu'un terminal ? 
C'est l'interface qui permet d'intéragir avec l'ordinateur (pas de souris dans un terminal, tout se fait via le clavier !)

Voici les lignes de commande principales : 

```
pwd                   # Afficher le chemin du dossier dans lequel on se trouve
cd nom_du_dossier/    # Aller dans un dossier
cd ..                 # Remonter dans le dossier parent
cd ~                  # Aller au dossier personnel
cd /                  # Aller au dossier racine

ls                    # Lister les éléments du dossier
ls -l                 # Lister les éléments avec plus de détails
ls -a                 # Lister les éléments cachés

touch                 # Créer un fichier sans l'ouvrir
mkdir                 # Créer un répertoire/dossier
rm                    # Supprimer un fichier
rm -rf                # Supprimer un dossier 
man ls                # Afficher le manuel de la commande ls
cp text1 text2        # Copier le fichier text1 en text2
mv text1 text2        # Renommer le fichier text1 en text2

```

Nous allons mettre en pratique ces quelques lignes de commande.
Pour commencer, lancez votre terminal : où sommes-nous ? 

```
pwd 
# Le terminal devrait vous afficher quelque chose comme ça : 
/Users/Votre_nom_d'utilisateur (Mac) ou /Home/Votre_nom_d'utilisateur (Linux) 

```
Nous sommes donc dans notre dossier personnel. Nous allons maintenant créer un dossier. 

```
mkdir mon_dossier 
# Si vous faites un ls, vous devriez voir votre dossier nouvellement créé parmi les autres dossiers/fichiers qui se trouve dans votre dossier personnel. Allez-y. 
ls
repertoire1 repertoire2 repertoire3 mon_dossier 
```
Notez qu'il vaut mieux ne pas utiliser de majuscules, d'accents ou d'espaces lorsque vous nommez vos dossiers ou fichiers. 
Nous allons maintenant accéder à l'intérieur de mon dossier créé. 
```
cd mon_dossier
# Je suis maintenant à l'intérieur de mon_dossier 
pwd
/Users/Votre_nom_d'utilisateur/mon_dossier ou /Home/Votre_nom_d'utilisateur/mon_dossier
```
Si vous faites taper la ligne de commande 'ls', rien ne s'affichera. Normal, le dossier est vide. 
Nous allons donc créer plusieurs fichiers avec la commande 'touch'

```
touch fichier1
touch fichier2
# Nous allons aussi créer un dossier tant qu'à faire
mkdir repertoire
# Faisons un 'ls'
ls 
fichier1 fichier2 repertoire
```
Nous allons maintenant copier le fichier1. 

```
cp fichier1 fichier3 
ls
fichier1 fichier2 fichier3 repertoire
```
Et si nous voulions renommer le fichier3 ? 
```
mv fichier3 fichier4
ls
fichier1 fichier2 fichier4 repertoire
```
Enfin, essayons de supprimer le fichier4 et le dossier repertoire. 
```
rm fichier4
rm -rf repertoire
ls
fichier1 fichier2
# Et si je veux revenir dans le dossier parent 
cd ..
ls
repertoire1 repertoire2 repertoire3 mon_dossier 
```

Il existe bien entendu d'autres lignes de commandes, mais celles citées ci-dessus sont les plus courantes.
Vous n'avez plus qu'à vous entraîner.

Pour en savoir plus : https://www.maketecheasier.com/cheatsheet/linux-command-line/
