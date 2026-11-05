# aimadbouzid.github.io

Ce dépôt n'existe que pour servir **un seul fichier** : `robots.txt`, à la racine
du domaine.

## Pourquoi

Un `robots.txt` n'est lu qu'à la racine d'un domaine. Celui qui vivait dans
`https://aimadbouzid.github.io/makers/robots.txt` était donc **ignoré par tous les
robots** : seul `https://aimadbouzid.github.io/robots.txt` fait foi, et il vaut pour
**tous** les sites publiés sous `aimadbouzid.github.io`.

Conséquence avant ce dépôt : les blocages de GPTBot, CCBot et ClaudeBot écrits dans
le sous-dossier ne s'appliquaient pas. Le contenu était collectable sans restriction.

## Ce que fait ce robots.txt

- il laisse passer les moteurs de recherche — être trouvé est le but ;
- il refuse les robots qui ramassent du texte pour entraîner des modèles :
  GPTBot, ClaudeBot, CCBot, Google-Extended, Applebot-Extended, PerplexityBot,
  Bytespider, meta-externalagent ;
- il annonce le plan du site de la bibliothèque makers.

Les deux « Extended » méritent un mot : ce ne sont pas des robots mais des jetons de
refus. Les bloquer retire le contenu de l'entraînement de Gemini et d'Apple
Intelligence **sans** toucher au référencement dans Google Search ni dans Siri.

## Ce que ce fichier n'est pas

Une sécurité. Un robot malveillant ignore `robots.txt` — c'est une politesse entre
gens bien élevés. La vraie protection est qu'il n'y a rien de privé publié ici.

## Le jour où makers.si aura son propre domaine

Ce fichier ne le couvrira plus : un domaine propre a sa propre racine. Il faudra
remettre un `robots.txt` à la racine de ce domaine-là. Le site en fabrique déjà un
(`public/robots.txt`), qui deviendra alors le bon.
