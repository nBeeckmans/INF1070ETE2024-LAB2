# INF1070ETE2024-LAB2

# NOTES GÉNÉRALES :   
    - Ctrl de droite est réservée par Virtual Box.  

# Exercise 1  
  
## 1.1 s'authentifier  

Sur les ordinateurs des laboratoires, si vous voulez utiliser Ubuntu, redémarrer l'ordinateur et sélectionner Ubuntu comme système d'exploitation. Ensuite, suivre l'énoncé !

## 1.2 Navigateur de fichier

Sur Ubuntu 24.04 (et 22.04), sur la barre de gauche, cliquez sur files et visiter les différents répertoire. 

Pour créer un dossier :
    - Click-droit
    - Créer répertoire (create folder)
    
Créez 1 répertoire INF1070 et 1 sous-répertoire Labo02

## 1.3 Fureteur et téléchargement

Utiliser firefox normalement (le but de cette partie du labo est de montrer que Ubuntu peut être utilisé normalement !)

Veuillez télécharger les documents demander (qui seront mis par défaut dans les télécharement) ensuite les déplacer dans le dossier Labo2 créé dans la partie 1.2. 

Particularités: 
    - pour le texte : click-droit sur la page puis sauvegarde la page !  
    - pour les fichiers gitlab : cliquer sur le bouton de téléchargement à droite juste au dessus du pdf ou du code java  
    - pour l'image : même chose que pour le texte  
    - pour le fichier audio : click-droit sur la barre de progression puis sauvegarder l'audio !  

## 1.4 Lecture de fichiers 

Applications (Ubuntu 24.04, peut-être 22.04 aussi mais à vérifier!) :   
    - .pdf : Evince  
    - .ogg : videos, Totem   
    - .txt, .java : Text editor de GNOME  
    - .png : Image viewer de GNOME   

Pour vérifier, chercher dans les sections Help ou préférence de chaque application ! (souvent 3 points ou 3 barres en haut à droite).

Pour les fichiers binaires, en utilisant Text editor, on voit que tous les fichiers non ouvert par défaut par Text editor sont binaires !

Dans la partie sur `Calc`, utilisation similaire à Excel ! 

## 1.5 Paramètres 

Ici, c'est à vous d'essayer ! 

Conseil :
    - Augmenter la résolution pour que l'écran soit plus grand.   
    - Si cela vous donne un écran noir, il faut allouer de la mémoire graphique supplémentaire à votre machine virtuelle.   

# Terminal 

Appuyez sur la touche "Windows" ("command"), puis taper "terminal" et "entrer". (N'hésitez pas à jouer avec les préférences.)

Les commandes :

`pwd` : donne le chemin absolu de la position actuelle  
`ls` : liste les fichiers et répertoire dans le répertoire actuel  
`cd` : permet de changer de répertoire  
`xdg-open` : permet à Ubuntu d'ouvrir un fichier avec le programme par défaut   
`man` : permet d'ouvrir le manuel d'une commande  
`cat` : permet d'afficher à la sortie standard (console) le contenu d'un fichier texte  
`date` : donne des informations liées à la date sur les fichiers    
`wget` : permet de télécharger un fichier de puis internet   ( ex : `wget https://www.gnu.org/licenses/gpl-3.0.txt` ).

# Éditeur de texte : 

`Gedit` n'est plus utilisé par défaut par Ubuntu ! (`Text editor` à la place ou veuillez le télécharger avec `sudo apt install gedit`)  
`Nano` est un éditeur texte sur console ! (pour quitter, il faut utiliser `^X` (contrôle avec `x`) puis `y` pour sauvegarder puis ensuite appuyer sur `entrer` !  

# VIM : 

`:wq` pour sauvegarder et quitter.   
`:q!` pour quitter sans sauvegarder.   
`i` pour entrer en mode insertion.   
`esc` pour revenir en mode normal.  

Pour le `vimrc` :     
    - Créez le dossier ".vim/" dans votre `home`.  
    - Déplacez le `vimrc`dans le dossier récemment créé !   

_EN_CAS_DE_PROBLÈME_ :  
    - Entrez la commande : `curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim`  
    - Installez `git` : `sudo apt install git`   
    (Ceci devrait régler les problèmes)  
   
# Commandes :   

Installation de `cal` : `sudo apt install cal`.   

`cal` : affiche le mois actuel puis permet d'avoir plus d'information avec des options données   
`-y` : spécifie l'année (par défaut c'est l'année courrante)
`>` : redirection, permet de mettre ce qui devrait apparaitre dans la console dans un fichier   

Pour supprimer des blocks sur `VIM`, utilisez `v` ou `ctrl-v`. Ensuite, déplacez-vouz et finalement `d` pour supprimer tout ce qui a été sélectionné.  
L'utilisation de `r` permet de remplacer ce qui se trouve sous le curseur avant par le prochain charactère écrit.

__éditeur_favori__ : `VIM` (en réalité, vous pouvez utiliser celui que voux préférez)  

# PacVim :   

C'est un bonus, je vous conseille d'essayer !   
