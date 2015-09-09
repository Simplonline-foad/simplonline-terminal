# Terminal: les lignes de commandes

Qu'est-ce qu'un terminal ? 
C'est l'interface qui permet d'intéragir avec l'ordinateur (pas de souris dans un terminal, tout se fait via le clavier !)

Voici les lignes de commande principales : 

```
pwd                   # Affiche le chemin du dossier dans lequel on se trouve
cd nom_du_dossier/    # Aller dans un dossier
cd ..                 # Remonter dans le dossier parent
cd ~                  # Aller au dossier personnel
cd /                  # Aller au dossier racine

ls                    # Liste les éléments du dossier
ls -l                 # Liste les éléments avec plus de détails
ls -a                 # Listes les éléments cachés

touch                 # Créer un fichier sans l'ouvrir
mkdir                 # Créer un répertoire/dossier
rm                    # Supprime un fichier
rm -rf                # Supprimer un dossier 
man ls                # Affiche le manuel de la commande ls
cp text1 text2        # Copie le fichier text1 en text2
mv text1 text2        # Renomme le fichier text1 en text2

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
# Si vous faites un ls, vous devriez voir votre dossier nouvellement créé. Allez-y. 
ls

```
