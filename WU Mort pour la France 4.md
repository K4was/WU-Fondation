# WU Mort pour la France 4

Auteur : Kawas
<https://ozint.eu/ozinter/4630/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/43ae5e5a-c479-44df-a60b-291d543320d0)


## 1. Un jardin de la mémoire portant son nom a été créé. Dans quelle ville est-il situé ?

Deux villes sont citées dans les sources : plusieurs sources touristiques et plus ou moins officielles donnent Rethondes. Wikipedia donne Rethondes sur la page d'Augustin Trébuchon.

Une recherche **CLAIRIERE ARMISITICE COMPIEGNE OU RETHONDES ?** nous amène au site de Compiègne agglomération qui traite de cette confusion :

<https://www.agglo-compiegne.fr/clairiere-de-larmistice>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/d8c0bce0-436c-499a-8b96-719019c33312)

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/59715bd1-1c33-4672-b570-b4d874e78d38)


Le mémorial et le jardin sont bien situés à **Compiègne**. On peut retrouver leur adresse, route de Soissons sur le site du musée Mémorial de l'Armistice :
<http://www.musee-armistice-14-18.fr/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/8380e360-fccd-4e10-b454-8110a57a58af)


Et sur Maps :
<https://www.google.com/maps/place/60200+Compi%C3%A8gne/@49.4179216,2.8874512,14z/data=!4m6!3m5!1s0x47e7d5e621cbedd7:0x40af13e81644610!8m2!3d49.417816!4d2.826145!16zL20vMDFxejd6?entry=ttu>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/d8349994-3782-471d-b003-36e5fa449676)


la réponse était bien **Compiègne**


## 2. Où était auparavant posée la pierre que l'on peut y voir, qui porte l'inscription "A nos morts, INDOCHINE, AFRIQUE DU NORD, OPERATIONS EXTERIEURES" ?

Partons visiter le jardin de la mémoire. Sur le site du mémorial on trouve des photos, dont celle du monument dont parle la question :
<http://www.musee-armistice-14-18.fr/visiter-le-memorial/la-clairiere/le-jardin-de-la-memoire/>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/04c006c8-d0dc-4717-a4b0-08d2b361e064)




L'information sur la provenance de la pierre est plus difficile à trouver.  Première obstacle, on ne devait pas chercher l'origine de la pierre, plutôt se renseigner sur le lieu où elle est actuellement avec les mots **AUGUSTIN TREBUCHON JARDIN MEMOIRE**.

L'information est donnée par une video audioguide postée sur youtube par le site du Mémorial de l'Armistice et non référencée sur le site.

Ensuite tout dépend du moteur de recherche que vous utilisez :

Curieusement on ne trouve pas cette video par une recherche sur Google.

On pouvait la trouver de plusieurs façons :

**En recherchant directement sur Youtube**, sous réserve d'avoir l'idée de chercher une video.
<https://www.youtube.com/results?search_query=augustin+trebuchon+jardin+memoire>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/1c272546-d91c-4be3-b6f2-fa3a45dfea83)


**Avec Yandex** où elle apparaît en premier lien :
<https://yandex.com/search/?text=augustin+trebuchon+jardin+memoire&lr=123574&search_source=yacom_desktop_common>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/e1bc941d-711d-4942-8228-0ef9c36db943)



**Avec Duckduckgo dans l'onglet Images** c'est aussi le premier lien qui apparaît :
<https://duckduckgo.com/?q=augustin+trebuchon+jardin+memoire&t=ffab&iar=images&iax=images&ia=images>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/b87a2911-b038-4e0e-9925-7fb1cbfb213f)


**Avec un métamoteur qui agrége les résultats de plusieurs moteurs de recherche, comme Startpage**, on retrouve aussi la vidéo en premier lien dans l'onglet Images :
<https://www.startpage.com/sp/search>

![image](https://github.com/K4was/WU-NBCTF-2023/assets/152096071/9694cdc9-301f-42a9-b341-c6c8eaaf111e)


<https://www.youtube.com/watch?v=cSIDTGdAdA8>

L'audio, les sous-titres et le transcript sous la video donnent l'information tant cherchée !

La pierre provient du **Cloître de la Visitation** de Nantes.

Flag
**NBCTF{compiegne_cloitre-de-la-visitation}**
