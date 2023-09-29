# Bash2023
## titre2
### titre3

un texte en **gras** et en *italique* et ***les deux***

- item 1
- item 2
  - item 3
  - item 4
    - item 5

1. trtrerte
2. toto
   1. titi


`print("toto")`

[lien vers killercoda](https://killercoda.com/emelin)


[lien vers markdown](https://www.markdownguide.org/cheat-sheet/)

## cours:
- `ls` (lister les fichiers)
- `cd` (se deplacer dans les dossiers)
- `cd ..`(revenir en arriere)
- `cat` (lire des fichoers texte.)  
- `Mkdir` (creer des répertoires)
- `nano` (ouvre un editeur de fichier)
- `touch` met a jour date et heure
- `du` (connaitre la taille du repertoire)
- `rm` (supprimer un fichier)
- `rm -r` (suppr dossier)
  - !! `rm -r/` efface l'ordi
- `cp` (copier un fichier)
- `grep` (rechercher un mot dans un fichier)
- `chmod` (pour modifier les droits)
- `mv` (deplacer unfichier si on met un slash apres l'argument, sinon le renomme)
`-`=nom de fichier   
`r`= read  
`w` = ecrire  
`x`= executer  
`sudo` permet de devenir l'utillisateur root

### utiliser chmod:
- `chmod (utilisateur : u(user), g(groupe), o(other))(+(ajourer des droits) - retirer les droits(droit a update)` 
- `chmod 777` donnera les permissions `rxwrxwrxw` (binaire avec un 1 si la permission est effective)


### utiliser mv :
1. Déplacer un fichier.
`mv /home/toto/truc.txt /temp/`
`mv /home/toto/truc.txt ../`

2. Deplacer un repertoire.
`mv /home/toto/docs/ /temps/`

3. Renommer un fichier.
`mv /home/toto/truc.txt /home/toto/machin.txt`

4. Les 2.
`mv /home/toto/truc.txt /home/truc.txt`

5. option :
-n : ne pas ecraser le fichier existant

bonjour
