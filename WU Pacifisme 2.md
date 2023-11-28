# WU Pacifisme 2

Auteur : Kawas
<https://ozint.eu/ozinter/4630/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/526db904-439e-4996-9b28-77866519d2c6)


## 1. On connaît le fichier S ; à l'époque existait un autre carnet de police destiné à recenser les individus soupçonnés d'espionnage puis les antimilitaristes. Quel est son nom ?

En recopiant les mots de la question dans la barre de recherche de Google on trouve ceci : Histoire du carnet B, ancêtre de la fiche S

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/a94fbad1-e29c-4af2-8c60-22ee464cff83)


<https://www.archivespasdecalais.fr/Decouvrir/Chroniques-de-la-Grande-Guerre/Histoires-de-la-Grande-Guerre/De-l-utilisation-du-carnet-B>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/b0af0e2f-4a71-4916-a7a2-ab2dbc2a681b)


Première partie du flag : **carnet-b**

## 2. Juste après l'assassinat, un télégramme est adressé à tous les préfets donnant l'ordre de ne pas utiliser les données qu'il contenait. Quel est l'Unix Timestamp de l'envoi de ce télégramme ?

L'article de wikipedia sur Jean Jaurès ne donne pas ce renseignement.

Mais celui sur son assassinat en parle. Non dans la narration de l'événement mais dans le paragraphe sur les réactions qui ont suivi.

<https://fr.wikipedia.org/wiki/Assassinat_de_Jean_Jaur%C3%A8s#Transfert_au_Panth%C3%A9on_des_restes_de_Jean_Jaur%C3%A8s>

![Screenshot from 2023-11-27 18-37-56](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/3b975a4a-2704-43f0-8de3-afc180491fc6)


L'article sur le Carnet B en parle également, dans le paragraphe sur la non-utilisation de ce carnet en 1914.

<https://fr.wikipedia.org/wiki/Carnet_B>

![Screenshot from 2023-11-27 18-49-52](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/a796606b-dab5-4a05-94ad-2c43b4fa92d5)



Le télégramme a été envoyé par le ministre de l'Intérieur, Louis Malvy, **le 1er août 1914 à 14h25**.

Nous avons la date et l'heure de l'envoi.

On se renseigne sur l'horodatage Unix :
<https://www.unixtimestamp.com/fr/>

![Screenshot from 2023-11-27 18-51-39](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/894706b8-993e-4c3a-a11c-1644e2bacf2a)


Sur ce site, parmi d'autres, on peut convertir une date de l'histoire en une somme de secondes, **négative** ici puisque située avant le 1er janvier 1970, date du début du décompte.

<https://www.unixtimestamp.com/fr/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/91230c05-c4dd-4671-85a1-e18dece4f619)


La conversion pour le 1er août 1914 à 14h25 
donne **-1748856900OOO**


Flag
**NBCTF{carnet-b_-1748856900000}**
