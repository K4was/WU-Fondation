# WU Pacifisme 1

Auteur : Kawas
<https://ozint.eu/ozinter/4630/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/76e784f3-1a71-482c-a9e8-5ec6fba5701b)


## 1. Un pacifiste essaie d'empêcher l'événement qui nous préoccupe. Il est assassiné juste avant son déclenchement. Quelle est la date du transfert de ses cendres au panthéon ?

Nous cherchons un pacifiste assassiné juste avant la première guerre mondiale.
Une recherche  sur Google puis Duckduckgo avec les mots **PACIFISTE ASSASSINE** nous envoient vers plusieurs liens :

- lien vers la page wikipedia des pacifistes assassinés

<https://fr.wikipedia.org/wiki/Cat%C3%A9gorie:Pacifiste_assassin%C3%A9>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/fb75184e-8e8c-4904-a283-fa5648cb66f6)


Six noms apparaissent. Le seul qui convienne au niveau des dates est Jean Jaurès.

- un autre lien vers l'assassinat de Jean Jaurès<https://fr.wikipedia.org/wiki/Assassinat_de_Jean_Jaur%C3%A8s> le 31 juillet 1914.


![Screenshot from 2023-11-27 17-41-28](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/0218a52b-b3c5-45fa-9639-972e71658ef2)


Nous devons trouver la date du transfert de ses cendres au Panthéon. Wikipedia donne le 23 novembre 1924.

On peut vérifier l'information sur d'autres sites et des archives photographiques avec cette recherche **TRANSFERT DES CENDRES DE JEAN JAURES AU PANTHEON**

<https://www.lhistoire.fr/jaur%C3%A8s-au-panth%C3%A9on-la-gauche-divis%C3%A9e>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/ecba5543-cdb0-448f-8454-09e4594b89d0)


<https://gallica.bnf.fr/ark:/12148/btv1b53139719m.item>

![Screenshot from 2023-11-27 17-48-37](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/05a7786c-464e-429f-ba9b-26fcdce66904)



La date du transfert est le 23 novembre 1924, dans le format demandé : **19241123**

## 2.  Quel gouvernement présente le projet de loi décidant de ce transfert ?

On cherche à savoir qui décide du transfert éventuel au Panthéon, plus précisément sous la IIIème République. Avec la question **QUI DECIDE DU TRANSFERT AU PANTHEON ?** on obtient plusieurs informations.

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/5c81e15d-be6f-4297-8ab1-a6cc163581f7)


Le journal Le Monde nous apprend que pendant la IIIème République (1870-1940) ce sont les députés qui en décident :

<https://www.lemonde.fr/les-decodeurs/article/2017/07/03/entrer-au-pantheon-mode-d-emploi_5155049_4355770.html>

![Screenshot from 2023-11-27 17-44-48](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/b70fdc3b-e209-4694-a555-6a6106478074)



La page wikipedia de l'assassinat de Jean Jaurès répond à question 2 mais de façon moins claire que d'autres sites.

Sur 1-jour.fr et Le Figaro on parle du Cartel des Gauches :

<https://www.1-jour.fr/23-novembre-1924-jean-jaures-au-pantheon/>

![Screenshot from 2023-11-27 18-23-06](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/cdc62f98-0466-4f9b-bc77-46e6b0abbbf4)



<https://www.lefigaro.fr/histoire/archives/jean-jaures-entre-au-pantheon-le-23-novembre-1924-un-spectacle-grandiose-20191122>

![Screenshot from 2023-11-27 17-47-27](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/fc375ad0-0526-433e-bbf2-1bbecc57e3a8)



On vérifie l'information avec une recherche directe, **CARTEL DES GAUCHES**.
Le Larousse nous dit que le Cartel des Gauches est une "Coalition des partis de l'opposition formée en France lors des élections législatives du 11 mai 1924 contre la majorité de droite du Bloc national"

Le projet de loi a été présenté par le **Cartel des gauches**



Flag
**NBCTF{19241123_cartel-des-gauches}**
