Bonjour monsieur ,
Nous sommes le binome : Okbani Issam Eddine
                        Zadel Widad Fatima Zohra

Groupe : 1 

***Petit Discription du project : ***
**On a la classe MyFunc dans on a mis nos tokens sous forme de fonctions : **
-On a la fonctions Ul qui reconnée les unités léxical et leurs définitions, On a un tableau d'unité léxical est un tableau de leur définitions 
on a une var i qui parcour le tableau est retourne chac ul a sa signification. 
-On a la fonction isNumber qui reconnée tous les nombres sous forme de tableau cette fonction
contien une var j qui parcour le tableau avec une boucle while si elle le trouve ca retourn true est 
on accrémente le j, si non alors elle retourne false.
-On a la fonction Charac qui reconnée tous les alphabets c'est le meme principe que la fonctions isNumber.
-On a la fonction number qui contien 2 var et un booleen vir qui reconné les virgules, on a la boucle while qui vériffie si le nombre contien une virgule
ou non , si elle contien alors vir retourn false car on peut pas avoire un nobre avec 2 virgules, on a la boucle if qui test avec vi , si le nombre conient
une vir alors c'est un réel si non alors c'est un entier.
-On a la fonctions ident qui reconnée les identificateurs, cette fonction contien 4 var , 2 var booleen verif_premier qui test le premier element et la var tir qui test
les tirets , la premier boucle if test si le premier element est un caracter si oui alor on incrémentes et on mets verif_premier sur true, la prochaine boucle test la taille de
l'ident si elle est egale a 1 alors c'est un ident si nn alors elle test le prochain element si c'est un nombre alors c'est un ident et meme chose si c'est un caracter
l'ident doit avoir un seul tiret.
**On a la class MyAnaliseur qui contien l'interface et les differentes analyses : **
-On a la fonction lexicaleAnal qui fait lanalyse lexicale on a crée une liste lexic et on fait des test dans la fonction lexicaleAnal si elle roconnait une ul elle l'ajoute a cette liste
si non Elle affiche ul lexical non reconnue et a la fin on laffiche dans le text area.
-On a la fonction syntaxAnal qui fait lanalyse syntaxique qui test si la chaine contien l'ul et elle retourne sa signification, on a les boucles if qui test les diff type comme les nombres
entiers et réel , les identificateurs et les differentes type de boucle et affectations.