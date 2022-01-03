# Commits

Vous commencez un nouveau projet, il est donc impératif de mettre en place une bonne convention de commits en équipe.


## `.gitignore`

Ajoutez un fichier `.gitignore` à la racine de votre projet. Ce dernier **doit** suivre les meilleures pratiques en terme de fichiers ignorés. Vous trouverez beaucoup d'information sur le Web à ce sujet. On veut notamment ignorer :

1. Les configurations *personnelles*
2. Les fichiers contenant des *path* personnels
3. Les fichiers auto-générés
4. Les fichiers contenant des *secrets* (mots de passes, clés, etc.)
5. Les *builds*

## Convention

Vous devez suivre une convention pour l'écriture et le contenu des commits, en plus de la gestion et le nommage des branches. Vous pouvez vous inspirer de pratiques populaires existantes si vous le désirez. On vous demande de **décrire vos conventions de commits et de branchage** dans le fichier `exerices/tp1.md`. Assurez-vous d'**indiquer vos sources** si vous vous inspirez d'ailleurs. On cherche notamment à savoir :

1. Comment nommer les commits selon leur type/section/grosseur/etc.
2. Quoi et quand commiter?
3. Quelles sont les branches *de base* (qui sont communes et qui existeront toujours) et quels sont leurs rôles (chacune)?
4. Quelle branche est *LA* branche principale (contenant le code officiellement intégré et pouvant être remis)?
5. Quand créer une nouvelle branche?
6. Quand faire une demande de changement / d'intégration (pull request / merge request) et sur quelle branche la faire?

Voici quelques points de départ pouvant vous être utile :

- [Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [Trunk-based development vs. Git Flow](https://www.toptal.com/software/trunk-based-development-git-flow)

Vous n'êtes pas obligé de suivre un standard, mais vos méthodes *doivent* être **cohérentes**.
