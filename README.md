# PROJET S3 METADONNEES DES FICHIERS IMAGES ET STEGANOGRAPHIE PAR DAMODARANE.JEAN-BAPTISTE et ELUMALAI.SRIGURU

## Introduction
Ce projet est fait par <b> DAMODARANE Jean-Baptiste et ELUMALAI Sriguru </b>, étudiants en Licence 2 Informatique en groupe C.
<br></br>
Le projet se base sur le concept de <b>  steganographie </b>, dont l'objectif est de dissimuler un message dans un fichier image de type .png ou .jpeg et sur les métadonnées des fichiers images.

**La version java**
<br></br>
Pour ce projet, nous choisi avec la version javaSE-11

## Utilisation et exécutions en mode CLI

Ce projet peut être exécuté en CLI sur la console à l'aide d'un <b>fichier jar</b>.
<br></br>
Ouvrir votre console Linux.
<br></br>
le ficher se nomme : myCli.jar
<br></br>
En mode CLI, l'utilisateur peut :
<br></br>

1. examiner explorer un dossier, dont le nom sera passé en paramètre et l'utilisateur devra mettre un '.'
<br></br>
        commande à taper : `java -jar myCli.jar d .`  ou `java -jar myCli.ajr -d images`

2. afficher les métadonnées d'un fichier image dont le nom sera passé en paramètre
<br></br>
        commande à taper : `java -jar myCli.jar nom_image.png`

3. cacher un message/texte dans une image, le message et le nom de l'image sera passé en paramètre
<br></br>
        commande à taper : `java -jar myCli.jar -f nom_image.png -s "message_secret"`

4. extraire le message dissimulé dans l'image, le nom de l'image contenant le message caché sera passé en paramètre
<br></br>
        commande à taper : `java -jar myCli.jar -f nom_image.png -s "message_secret"`

5. pour avoir des aides
<br></br>   
        commande à taper : `java -jar myCli.jar -h` ou `java -jar myCli.jar --help`


## Utilisation et exécutions en mode GUI

Ce projet peut être exécuté en GUI à l'aide d'un <b>fichier jar</b>.
<br></br>
le ficher se nomme : myGui.jar
<br></br>

Pour lancer la fenêtre, veuillez taper la commande : `java -jar myGui.jar`
<br></br>
1. Pour explorer un dossier, l'utilisateur doit se placer dans l'onlget "Lister un repertoire", puis cliquer sur le boutton "choisissez un dossier' (pour choisir un dossier) et ensuite cliquer sur analyser
![image](https://user-images.githubusercontent.com/91695685/146678770-c9a11784-7117-4247-b4a4-b543adcdd1a9.png)

<br></br>

2. Pour afficher, l'utilisateur doit se placer dans l'onglet "Metadonnees", puis choisir un fichier image et ensuite examiner
![image](https://user-images.githubusercontent.com/91695685/146679269-079960e7-104d-4468-8a9a-c18c884f6e05.png)

<br></br>

3. Pour encoder une image, l'utilisateur doit se placer dans l'onglet correspondant, puis choisir une image et taper nom de la nouvelle image qui va contenir le message. Ensuite taper le message secret et enfin appuyer sur le bouton cacher
![image](https://user-images.githubusercontent.com/91695685/146679396-62f76a0d-2dfd-4792-8573-3dbe627d9ac4.png)


4. Pour decoder l'image, l'utilisateur doit choisir le fichier image qui contient le message secret et appuyer sur le bouton decoder
![image](https://user-images.githubusercontent.com/91695685/146679570-16ded0d7-1a3e-4337-b5eb-ffe0736c5cc4.png)

