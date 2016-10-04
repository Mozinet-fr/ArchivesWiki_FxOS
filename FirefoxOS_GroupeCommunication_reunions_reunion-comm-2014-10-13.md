 # Compte rendu de la réunion du Groupe de communication MozFr/FFOS du 13 octobre 2014

__Présents :__

* MoniqueB
* Natalia
* Anthony
* Ahubert
* Dattaz
* Jm-gailis
* Kant1
* Mozinet
* Porkepix
* Tchevalier

__Etherpad du groupe__ :  https://etherpad.mozilla.org/groupecommozfr

## I. Point sur le [[FirefoxOS/MinisiteFirefoxOS|minisite]] avec l'équipe Webdev

### 1. la page ''custom'' à l'adresse firefoxos.mozfr.org

Base : le site de mozilla.org 

https://www-demo5.allizom.org/en-US/?version=a2 

Code dispo sur les pages GitHub suivantes : 

* https://github.com/mozilla/bedrock/compare/homepage-prototype-two
* https://github.com/mozilla/bedrock/commit/b1b72aa56cbca0d0f442264a501f6643d832c5f9

Concernant la page ''custom'', l'équipe Webdev rencontre des difficultés techniques liées à la densité du code HTML de la page d'origine. 1 400 lignes de codes en HTML brut, dont la majeure partie est superflue pour notre site. En outre, le site de mozilla.org est réalisé en Python qui génère du HTML. Reprendre directement ce HTML généré ne rend pas très bien.

L'avancée des travaux d'Anthony et Dattaz est dispo sur GitHub (télécharger le zip et ouvrir la page HTML contenue dedans sous Firefox). https://github.com/dattaz/miniffos-brouillon

Il reste également à mettre les outils de mesure d'audience, cf. discussion sur GitHub : https://github.com/mozfr/firefoxosminisite/issues/25#issuecomment-58898711

Concernant les tuiles, elles lieront vers (cf. [PDF joint](http://mozfr.org/pipermail/moz-fr/attachments/20141014/45f6a1ae/attachment-0001.pdf)) :
{| border=&quot;1&quot;
!Nom de la tuile
! Mode de récupération des données !! Statut
|-
| Facebook
| API Facebook (Firefox OS FR)
| En cours
|-
| Twitter
| API Twitter (Firefox OS FR)
| En cours de finalisation
|-
| #appdujour
| RSS depuis le blog
| Prêt
|-
| #foxprimezvous
| RSS depuis le blog
| Prêt
|-
| Les astuces de Mamie Fox
| RSS depuis le blog
| Prêt
|-
| YouTube
| API Youtube (Firefox OS FR)
| En cours
|-
| Aide (SUMO et Gecko)
| TBD
| TBD
|-
| Développeurs
| https://developer.mozilla.org/fr/Firefox_OS/Introduction 
| En cours
|}

Concernant la tuile Twitter, la question du défilement de plusieurs tweets est conditionnée par faire fonctionner les animations dans la tuile, donc à la question du code vue ci-dessus.

Contenu de la tile Mamie Fox :
* Monique propose d'intégrer les contenus qu'elle construit sur storify, ce qui a été validé par le groupe :
** https://storify.com/webatou/firefox-os 
** https://storify.com/webatou/lancement-de-firefox-os-en-france 
** https://storify.com/webatou/mozilla-c-est 
* Les contenus pourront mêler ''advocacy'', conseils d'apps, histoire de la communauté, histoire du libre et de Mozilla ; bref l'idée est de faire de Mamie Fox l'incarnation du blog, de notre vision du Web et de ce qu'on offre comme contenu aux visiteurs.

### 2. Le blog à l'adresse http://firefoxos.mozfr.org/blog/ et actuellement en bêta à l'adresse : http://beta.firefoxos.mozfr.org/blog/

Le blog est prêt, il manque :
* les __mentions légales__
* la __différenciation de design par rapport au design Mozilla__ : utilisation du ''blueprint'' de la communauté, dispo ici : https://assets.mozilla.org/Projects/Firefox%20OS/Engagement/Community/Artwork/Print%20CMYK/
* créer les __comptes pour ceux qui écrivent sur le blog__.

## II. Point sur les contenus

__Calendrier éditorial__ : pad dédié : https://etherpad.mozilla.org/calendriereditorial

Idée d'un calendrier de l'Avent à intégrer dans le minisite, avec chaque jour une astuce, une app, un ''do it yourself'' comme les ''paper toy'' (https://wiki.mozilla.org/PaperToy)…

## III. La suite

__Mentions légales pour le blog : Mozinet__

__Préparation de contenus sur la base des templates__ : 

Laurent est dispo pour un atelier d'écriture le __jeudi 16 octobre à 18h dans les locaux de Mozilla Paris et sur Vidyo__ à l'adresse : https://v.mozilla.com/flex.html?roomdirect.html&amp;key=Je3qmsd8C3lJ

Tous ceux qui le souhaitent sont invités à préparer un sujet de leur choix comme app du jour ou sur foxprimezvous afin de le construire avec Laurent.

Préparation sur les pads dédiés : 
* https://etherpad.mozilla.org/appdujour  
* https://etherpad.mozilla.org/foxprimezvous 
* et https://etherpad.mozilla.org/calendriereditorial 

Appdujour : OpenBeerMap => Aurélien
Contenus foxprimezvous => Kant1

__Framadate pour la prochaine réu__ :  http://framadate.org/mwbqd2i6uk85zk8p 

__Préparation d'un calendrier éditorial__ : réfléchir aux évènements (fêtes, vacances), sujets médiatiques, manifestations culturelles, etc. et particulièrement au calendrier de l'Avent :D
