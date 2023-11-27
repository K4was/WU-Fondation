

# WU Fondation

Auteur : Kawas
<https://ozint.eu/ozinter/4630/>

## **1. Qu'abrite ce bâtiment ?**

On trouve le lieu avec une recherche en reverse avec Google Images :

<https://lens.google.com/search?ep=subb&hl=fr&p=AUM6UZA79qkZVTRBCA3zXKUB9wZhud4LhLj-YnOlMjZjHDd81ZlONei6uz_KH6sunw1qmsSfFEDsuYyRuSR_TYd0nL16CLEc2LNUgbkFmYpbZeYRzE1oXeNvDtavDmMLZzfHT-IA7yp-auKf2q4rw8WsB9iNtGWEAegjZh__nIYTGf2GP1OmI4s8rhm0wrQLIP4aNPT5DracCH1WrCJIJmmM9luNAMtyAJfV-eugQ1FCItEI3F-SeQrKu30k0--xlBrNhF17P9oLE1xN_MRR9HGxOJ9kH88rSF06nI6tr6k3#lns=W251bGwsbnVsbCxudWxsLG51bGwsbnVsbCxudWxsLG51bGwsIkVrY0tKR001WkdVNE5USTVMVGN6T0RNdE5EZzJOaTA1TURVekxURTFaVEl6Tnpnek1XWTNOUklmTURWNFNGSldjV05sUWpSVWIwUk1aa3hPVEZCZlpVOXhjV3BXY205NFp3PT0iXQ==>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/e5a0d164-159d-4c9c-834b-496ed0db0299)


C'est la maison où habitait Georges Clemenceau et qui abrite maintenant un musée à son nom.

réponse : **musee-clemenceau**

## **2. Quel CMS a été utilisé pour construire son site ?**

On peut chercher ce qu'est un CMS.
Une recherche **QU'EST-CE QU'UN CMS** nous permet de trouver ce site :
<https://www.salesforce.com/fr/resources/articles/definition-cms/>, qui nous donne également les CMS les plus utilisés à ce jour.

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/2b081ac3-a116-4610-84ba-3d87a1711db0)


Deux possibilités :

1. On connaît le raccourci clavier **CTRL + U** ou **CTRL SHIFT + U** nous donne accès au code source du site.
   
   @Elyse314 me souffle à l'oreille que **clic droit/inspecter ou afficher le code source** vous y amène aussi.

Une recherche **CTRL +F plugin** nous donne, dans les commentaires, à la ligne 13 :

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/61ce395a-f344-409c-ae2c-f0abcbdb28c6)


2. On cherche sur internet **QUEL CMS UTILISE SUR UN SITE**

Plusieurs sites proposent une réponse, citons celui-ci, très complet :
https://antoine-moulard.com/webmarketing/comment-trouver-cms-utilise-site-internet/
Plusieurs outils sont proposés, on peut essayer whatcms
<https://builtwith.com/>
<https://whatcms.org/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/54b6ef31-1283-4833-b180-d166e70490e8)


Les deux méthodes nous donnent la même réponse, le CMS  **wordpress**

## **3. Trouvez la question suivante**
J'avoue, c'est tordu !
La question 3 se trouve dans la ligne ***Comment*** des métadonnées de la photo...

On peut utiliser
<https://jimpl.com/>
ou <https://www.aperisolve.com/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/85638520-a0be-4524-be9d-47d61ca28e3e)

et dans les Strings :

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/f8b4c86c-5586-4255-b80f-3e4ee973f748)

On peut aussi le faire en ligne de commande avec exiftool :

![Screenshot from 2023-11-27 11-02-50](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/52dbab7c-48cb-4d5c-8aff-33a6a7e75208)


Question : ***Quel est son surnom le plus connu ?***

On trouve la réponse sur plusieurs sites, on peut citer celui-ci, la réponse est d'ailleurs dans l'URL :

<https://www.herodote.net/On_l_appelait_le_Tigre_-synthese-205.php>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/38fe4c32-9fff-4976-a819-5f7ea2779e8e)


Surnom **le Tigre**

Flag **NBCTF{musee-clemenceau_wordpress_le-tigre}**
