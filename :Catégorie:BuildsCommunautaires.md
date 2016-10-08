## L'équipe des [http://builds.firefoxos.mozfr.org builds communautaires de Firefox OS] a besoin de toi !

Contact : IRC => irc.mozilla.org #buildopencfr
### Pourquoi et comment être bêta-testeur des builds communautaires ?

Être bêta-testeur, c'est avoir une nouvelle version avant les autres, mais surtout être prêt à passer du temps à chercher les bugs, à avoir un téléphone qui marche moins bien ou plus et idéalement, il faut disposer d'un téléphone de test. Pour des builds assez stables (comme le canal Beta ou Aurora), on pourra toutefois utiliser son appareil principal si on est à l'aise avec l'installation des builds communautaires. Il faut donc être prêt à accepter des bugs, des régressions (une fonctionnalité qui ne marche plus).

### Être notifier d'une nouvelle build à tester

Il faut s'inscire sur un bug de la branche que l'on veut et suivre au fur et à mesure les bugs.

### Installer le build pour le tester

Quand un build est prêt, il est mis à disposition sur le serveur. Chaque bêta-testeur le télécharge, dépose le build sur la carte SD de son téléphone, ''backup'' son téléphone, redémarre sur le téléphone en mode ''recovery'' et fait la mise à jour à partir de ce build (la procédure reste identique à celle appliquée lors de la première installation d'un build communautaire depuis une ''SD-card'', cf. http://builds.firefoxos.mozfr.org/doc/fr/devices/zte-open-c-fr Section Installation).

### Revenir en arrière

Il est bon de garder sur la même carte SD la version précédente du build. Ainsi en refaisant la procédure de mise à jour, on retourne à la version antérieure de Firefox OS dans sa version communautaire. Attention, cela fonctionne uniquement si on ne change pas de branche. Il faut faire des ''backups'' car il peut y avoir des problèmes.

### Quand on détecte un bug, que fait-on ?

Il faut se rendre sur le BugZilla et voir si personne n'a déjà remonté le bug. Si oui, on commente le bug en question.  Sinon, on ajoute une nouvelle entrée en donnant le maximum d'informations possible sur comment reproduire le bug/la manipulation effectuée, ce qui ne va pas, le comportement attendu et ce qui arrive. On interagit avec les personnes qui préparent les builds communautaires et ils feront leurs nécessaires pour corriger (quand cela est possible et de leur fait) les bugs remontés. => en fait non, on commente sur les bugs de la build à tester.

https://bugzilla.frenchmozilla.org/buglist.cgi?cmdtype=runnamed&list_id=1092&namedcmd=FFOSBuildCommunautaire

### Mise à disposition

Une fois le build stabilisé (les bugs sont corrigés ou clairement identifiés), il est mis officiellement le canal en tant que mise à jour. Ainsi toute personne qui a le build communautaire du canal correspondant aura une notification de mise à jour sur son téléphone et pourra installée cette nouvelle version.
