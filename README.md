# PROJET METADONNEES DES FICHIERS IMAGES ET STEGANOGRAPHIE S3 PAR DAMODARANE.JEAN-BAPTISTE et ELUMALAI.SRIGURU

## Introduction
Ce projet est fait par <b> DAMODARANE Jean-Baptiste et ELUMALAI Sriguru </b>, étudiants en Licence 2 Informatique en groupe C.
<br></br>
Le projet se base sur le concept de <b>  steganographie </b>, dont l'objectif est de dissimuler un message dans un fichier image de type .png ou .jpeg et sur les métadonnées des fichiers images.

**La version java**
Pour ce projet, nous choisi avec la version javaSE-11

## Utilisation et exécutions en mdoe CLI
Ce projet peut être exécuté en CLI sur la console à l'aide d'un <b>fichier jar</b>.
<br></br>
Ouvrir votre console Linux.
<br></br>

En mode CLI, l'utilisateur peut :
le ficher se nomme : myCli.jar

1. examiner explorer un dossier, dont le nom sera passé en paramètre et l'utilisateur devra mettre un '.'
        commande à taper : `java -jar myCli.jar d .`  ou `java -jar myCli.ajr -d images`

2. afficher les métadonnées d'un fichier image dont le nom sera passé en paramètre
        commande à taper : `java -jar myCli.jar nom_image.png`

3. cacher un message/texte dans une image, le message et le nom de l'image sera passé en paramètre
        commande à taper : `java -jar myCli.jar -f nom_image.png -s "message_secret"`

4. extraire le message dissimulé dans l'image, le nom de l'image contenant le message caché sera passé en paramètre
        commande à taper : `jar -jar myCli.jar -f nom_de_limage_encode.png -e`