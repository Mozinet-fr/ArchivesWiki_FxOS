__Guide pratique du rédacteur__ élaboré par le [[FirefoxOS/GroupeCommunication|Groupe de communication pour Firefox OS]]

__''Travail en cours : participez [sur notre liste](http://mozfr.org/mailman/listinfo/firefoxos-mozfr) ou en modifiant la page.__''

__TOC__

## Le fond

### Les sources

#### Les sources fiables

* CREDOC : [Enquête « Conditions de vie et Aspirations des Français » - R297 (PDF)](http://www.credoc.fr/pdf/Rapp/R297.pdf)
* http://www.statista.com


#### Les sources peu fiables à éviter

### Les contenus

#### Les contenus déclarés acceptables

La galette des rois
#### Les contenus à éviter

À « Noël » préférer « les fêtes »

Éviter de fêter des anniversaires de personnes.

## La forme

### L'orthographe

Les fautes d'orthographe nuisent à la crédibilité des contenus publiés. Relire et faire relire est vraiment important.

### Typographie

''Ne tient pas compte de la transformation automatique typographique du CMS.''

Voir cette [table des caractères spéciaux](http://lorem-ipsum.studiovitamine.com/caracteres-speciaux,287,fr.html) avec entité HTML, caractère ASCII, code clavier Windows et nom courant. Il existe des claviers à installer pour avoir les caractères spéciaux courants sous la main.

Nous n'utilisons pas les guillemets anglophones ni les guillemets droits, mais toujours les guillemets francophones «  » suivi pour l'ouvrant et précédé pour le fermant d'une espace (''n. f.'') insécable classique (&amp;amp;nbsp; &amp;amp;#160; Alt+0160).

On utilise des espaces insécables devant les ponctuations hautes (deux-points, point-virgule, point d'exclamation et point d'interrogation) ou encore avant les signes pour cent (non collés au nombre). Les symboles monétaires sont placés derrière la valeur et aussi précédés d'une espace insécable. Le symbole degré est collé au nombre qu'il suit sauf lorsque, s'agissant de température, il est lui-même suivi de l'abréviation précisant l'échelle utilisée (« 100° », mais « 100&nbsp;°C »)

Pour les nombres, le séparateur des milliers doit être une espace insécable.

Lorsque trois points sont présents (points de suspension), nous utilisons le caractère ellipse « … » à la place (&amp;amp;hellip; &amp;amp;#8230; Alt+0133). Attention, l'espace est après pas avant et veillez à ne pas utiliser « etc… » ou « ,… ».

Les tirets (à ne pas confondre avec le trait d'union plus court) sont les tirets demi-cadratin – (&amp;amp;ndash; &amp;amp;#8211; Alt+0150) pour les incises à l'intérieur d'une phrase (on peut mettre une virgule après les second tiret qui disparait devant un point-virgule ou un point final) et cadratin — (&amp;amp;mdash; &amp;amp;#8212; Alt+0151) pour les répliques (sauf la première) dans un dialogue.

Les titres ne prennent pas de ponctuation finale (ni point ni deux-points).

### Accessibilité, lisibilité et utilisabilité

#### Les liens hypertextes

Il faut éviter les liens « ici » ou « cliquez ici » ou toute autre instruction générique.

Les liens avec le même texte doivent avoir la même URL.

Le soulignement est réservé aux liens.

Les liens ne doivent pas se suivre juste séparés par des espaces.

Ne pas forcer les liens à s'ouvrir dans une nouvelle fenêtre sans prévenir les utilisateurs au minimum.

Ne pas mettre de liens trop longs. Être assez long pour être compris, mais suffisamment court pour éviter la confusion.

Indiquer le poids et format de chaque document à télécharger, le nombre de pages et la durée des vidéos et fichiers audio liés (PDF, 98 Ko, 16 pages).

HTML : remplissez bien l'attribut <code>title</code> dont la valeur apparaît en infobulle lors du survol par le curseur de la souris mais éviter de mettre là des informations essentielles que certains agents utilisateurs ne rendent pas.

L'attribut <code>hreflang</code> indique la langue du contenu cible du lien avec un code [code ISO 639-*](http://fr.wikipedia.org/wiki/Liste_des_codes_ISO_639-1) en deux ou trois lettres en minuscules pour la langue. Les caractères blancs ne sont pas autorisés dans les codes de langue. Un sous-code peut être rajouté à la langue après un trait d'union sous la forme d'un nom territorial ou d'un [code d'État ou de territoire](http://fr.wikipedia.org/wiki/ISO_3166-1) ce dernier en majuscules (ex. : <code>hreflang=&quot;fr-CA&quot;</code> sera pour indiquer que le document cible est en français du Canada).

L'attribut <code>lang</code> verra sa valeur formée de la même façon pour indiquer la langue du texte dans la balise (ex. : <code>&amp;lt;i lang=&quot;la&quot;&amp;gt;Errare humanum est&amp;lt;/i&amp;gt;</code> ou <code>&amp;lt;abbr title=&quot;Application programming interface&quot; lang=&quot;en&quot;&amp;gt;API&amp;lt;/abbr&amp;gt;</code> ).

#### Images

HTML : Les images doivent avoir un attribut <code>alt</code> (vide pour une image purement décorative) avec une courte description. Pour les longues descriptions, un attribut <code>longdesc</code> existe pour indiquer l'URL d'un fichier (texte ou HTML) avec une description exhaustive de l'image (utile pour les images avec du texte ou les infographies). Cependant, comme cet attribut est très peu <é et visible dans les interfaces utilisateur, il convient d'ajouter un D avec un lien vers le fichier (ex. : <code>&amp;lt;a href=&quot;URL_fichier_descritpion&quot; hreflang=&quot;fr&quot;&amp;gt;&amp;lt;abbr tite=&quot;Description&quot;&amp;gt;D&amp;lt;/abbr&amp;gt;&amp;lt;/a&amp;gt;</code> ).

#### Les tableaux

Pas de tableau de mise en forme. Les tableaux sont réservés aux données tabulaires.

Prévoir un titre pour les tableaux.

HTML : remplir l’attribut <code>summary</code> de la balise <code>table</code> avec une courte description du contenu du tableau.

#### Textes

Mettre des accents sur les lettres capitales.

Appliquer un contraste suffisant entre contenus et arrière plan. Une application utile pour vérifier votre contraste est [Colour Contrast Analyser](http://www.paciellogroup.com/resources/contrastanalyser/).

### Le HTML

Quelques conseils quelque soit le mode de saisie (wiki ou HTML) choisi :

En résumé : Le HTML sert à structurer les données, le CSS à les habiller.

__''[À finir]__''

## Préparer la publication des contenus

Après avoir écrit des articles sur le webzine (voir [[FirefoxOS/GroupeCommunication/Templates|le guide pratique]]), il importe de penser aux contenus qui vont permettre de :
# « Pousser »/mettre en avant ces articles ;
# Créer des contenus pour Twitter et Facebook qui permettent de créer de la réciprocité et de l'échange avec des communautés plus larges.


### Les étapes clés avant de publier un tweet ou un statut Facebook faisant la promotion d'un article du webzine


#### Le contenu peut-il choquer une communauté ?

Il est important d'être très explicite dans les tweets et statuts Facebook. Ceci afin d'être sûr que le contenu ne soit pas interpréter de façon incorrecte.

Plusieurs questions permettent de diminuer ce risque :
* Y a-t-il une référence communautaire dans le contenu publié ? Si oui, cette communauté est-elle visée, contestée, dénigrée ? À éviter le plus possible le cas échéant, sauf si c'est un objectif de communication manifeste et validée par le groupe ;
* Y a-t-il une actualité chaude qui parasite l'interprétation du contenu ? (ex. : un attentat, un « buzz », un phénomène de société, etc.). Là aussi, à proscrire.


#### L'orthographe est-elle correcte, la syntaxe précise ?

Rien de pire qu'un contenu « mal » écrit qui est ensuite relayée en ligne.

#### Les « calls to action » sont-ils bien implémentés ?

Vérifiez à tout prix que les liens fonctionnent, que les ''hashtags'' sont pertinents, et que les personnes à mentionner le sont effectivement.

#### L'étape de prépublication et de validation par la communauté

L'adage « Vérité en deçà des Pyrénées, erreur au delà » est crucial dans les réseaux sociaux. Afin d'éviter une erreur, rien de tel que demander à un regard extérieur un avis. La plupart des « bad buzz » et des erreurs de communication partent d'une bonne intention.

Une fois que votre tweet ou statut Facebook est prêt, relu, vous pouvez l'envoyer au groupe de comm. Si personne ne conteste dans l'heure qui suit, alors le contenu peut être publié. Cette double lecture n'est pas un ''process'' inutile puisque vous aurez déjà fait un travail préparatoire avant de demander le regard extérieur.

#### La mise en ligne et le suivi

Le contenu une fois publié doit être suivi. En effet, la plupart des réponses ou des interactions à un tweet se passent rapidement après la mise en ligne. Il faut donc converser par la suite et s'assurer qu'on maintient le lien avec la communauté.

Par ailleurs, un ''tweet'' de promotion de contenu du webzine peut très bien être répété ou légèrement modifié plusieurs fois par jour : à travailler dès cette étape-ci.


### Les étapes clés avant de publier un tweet ou un statut Facebook relayant une actualité ou permettant une conversation avec la communauté (Twitter)

Au-delà des étapes précédemment évoquées pour la publication d'un statut ou tweet faisant la promotion d'un contenu du webzine, de nouvelles règles ou principes doivent être ajoutés et pensés avant publication :

### L'article que je relaie a-t-il une valeur pour la communauté de ''followers'' (abonnés) ?

Une petite liste permet de se faire une idée assez simplement. Au moins un « oui » permet d'avoir une bonne raison de publier un contenu :
* est-ce divertissant pour la communauté ? Si oui, pourquoi ?
* le contenu relayé va-t-il permettre de nourrir la personnalité de Firefox OS en ligne ? (par ex. : le contenu permet-il de rendre plus sympathique Firefox OS ? ou est-ce en lien avec l'OS ou le produit ?)
* le contenu relayé va-t-il permettre de créer des liens avec des communautés affinitaires avec lesquelles nous n'avons pas encore suffisamment de liens ?
* le contenu relayé permet-il de faire notre propre promotion ?
* le contenu relayé permet-il de mettre en lumière des grandes causes qui sont associées à la communauté Firefox OS ?

### Comment faire du ''tweet'' ou du ''retweet'' un contenu vraiment Firefox OS

Le rôle de curation est déjà bien fait par une myriade de médias, utilisateurs Twitter, etc. Au-delà du relai d'articles (qui en soi est tout à fait légitime), y a-t-il une possibilité de rajouter un peu de Firefox OS dans le tweet ?
* a-t-on déjà écrit un article sur la thématique du contenu poussé ? Si oui, pourquoi ne pas le mentionner (ex. : « article du Figaro sur les risques de surveillance des internautes français URL », Firefox OS avait interrogé la communauté sur le sujet ici (URL2) ;
* peut-on faire un petit commentaire autour du contenu relayé (ex. : si le contenu est « LOL », pourquoi ne pas ajouter des « Le FOX en rigole encore : URL », « Approuvé par le fox… », etc.

## Parcours typique du rédacteur (pas à pas)

# rédiger un premier jet en XHTML ou au [format wiki de Dotclear](http://fr.dotclear.org/documentation/2.0/usage/syntaxes)
# choisir des illustrations (en notant l'origine, l'auteur et la licence de réutilisation)
# faire une copie d'[[FirefoxOS/GroupeCommunication#Mod.C3.A8les_de_documents_pour_les_articles|un modèle]] de Google Doc ou de pad selon le genre d'article
# remplir le document avec y compris :
## le titre affiché au dessus de l'article
## le titre SEO, <code>title</code> de la page web pour améliorer le référencement sur les moteurs de recherche
## les ''tags'' ou mots-clés aussi pour améliorer le référencement
## des propositions de messages pour Twitter (140 caractères) et Facebook
## un ''call to action'' ou incitation à faire réagir la communauté
## [la/les signature(s) du/des auteur(s)](https://mzfr.etherpad.mozilla.org/signatures-groupe-comm)
## un lien vers l'article précédent dans la catégorie (appdujour, jeu, Mamie Fox, Foxprimez-vous…)
## le crédit et les éventuelles licences pour les illustrations (internes et externes)
## une éventuelle licence pour le texte si elle s'avère dérogatoire de celle par défaut de notre site (pas encore mise en place)
# donner des droits de modification du document à toute personne avec le lien
# ajouter l'URL du document de travail sur la carte Trello de l'article et y ajouter le label « À relire » ; ajouter une ''checklist'' « Reste à faire » en la copiant depuis « Modèle de Gdoc appdujour et de checklist » par exemple et l'adapter
# mettre à relire sur notre liste avec l'URL de partage du document de travail
# incorporer les retours en tenant compte des commentaires et en acceptant ou refusant les suggestions de modifications
# mettre sur le blog avec les illustrations ou demander aux membres avec des droits sur le blog d'y mettre son article (sans oublier de joindre les illustrations)
# programmer ou publier le billet de blog
# ajouter la future URL ou l'URL du billet sur la carte Trello avec l'heure de publication
# indiquer la publication ou l'heure de publication avec l'URL sur notre liste
# faire une pull request sur le GitHub de MozFr si l'article entre dans une des catégories mises en avant sur le site vitrine (appdujour, Mamie Fox, Foxprimez-vous)
# faites la promotion de votre œuvre sur vos propres réseaux sociaux :-)
