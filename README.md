# 👩🏾‍🎓 Trombiquiz

##  Un outil pour apprendre les prénoms de ses élèves

Il est essentiel de connaître très rapidement les prénoms de ses élèves.
- Les élèves sentent qu'ils sont respectés en tant que personne et cela crée tout de suite un climat de confiance.
- La gestion de classe en cas de problème est beaucoup plus facile.

Je propose ici un outil, Trombiquiz, qui permet à partir d'un trombinoscope en ligne de mémoriser plus facilement les prénoms de ses élèves.

Si on dispose des photos avant même le premier cours, on peut ainsi arriver en classe en connaissant déjà au moins une bonne partie des élèves, ce qui les surprend souvent de manière très positive !

## Comment ça marche ?

Trombiquiz est un "bookmarklet" qui ne fonctionne que si vous le mettez dans un favori afin de pouvoir cliquer dessus quand vous serez sur un trombinoscope de vos élèves.

Trombiquiz fonctionne directement avec les applications suivantes : 
- Pronote
- Ecole Directe
- Oneconnect

Il fonctionne aussi pour les photos des participants à une formation sur Moodle ou Magistère.

Si vous utilisez un autre logiciel : vous pouvez me demander de l'intégrer à ce script (voir tout en bas de cette page).

Si vous disposez des fichiers des photos des élèves, vous pouvez aussi [créer une page HTML qui fonctionnera avec Trombiquiz](creer-fichier.html).

> Attention, les logiciels ci-dessus peuvent évoluer. Si Trombiquiz ne fonctionne plus, il faudra soit simplement télécharger la nouvelle version, soit me l'indiquer pour que je fasse les changements nécessaires.

## 1/ Créer un nouveau favori

Affichez la barre de vos favoris et glisser-déposer le lien ci-dessous dans vos favoris :

<a href="javascript:(function(){const script=document.createElement('script');script.src='https://trombiquiz.forge.apps.education.fr/trombiquiz.min.js';document.body.appendChild(script);})();">Trombiquiz</a>

## 2/ Afficher le trombinoscope de ses élèves

Par exemple sur Pronote (version en ligne) :

Cliquez sur “Mes données” / “Classes/élèves” / “Trombinoscope”

![](img/helpPronote.png)

Choisissez la classe et cliquez sur votre nouveau favori “Trombiquiz”

## 3/ Apprendre les prénoms

### Choisir l'ordre de présentation

Trombiquiz ouvre un popup et vous propose d'apprendre soit les prénoms dans l'ordre aléatoire (ordre par défaut : cliquez sur OK ou appuyez sur Entrée), soit dans l'ordre alphabétique (cliquez sur Annuler ou appuyez sur Esc).

```warning
Attention : pour que Trombiquiz fonctionne, il faut qu'on puisse voir toutes les photos des élèves sur l'écran, et si vous mettez du temps à faire votre choix de l'ordre de présentation, votre navigateur va probablement bloquer l'ouverture de la page des photos (il faudra alors soit relancer Trombiquiz et répondre plus vite, soit accepter les popups).
``````

![](img/firstMessage.png)

### S'entraîner à mémoriser les prénoms

Une page s'ouvre et Trombiquiz affiche une photo à la fois.

![](img/studentPhoto.png)

Quand vous pensez avoir retrouvé le prénom et le nom de l'élève, cliquez sur “Montrer la réponse”.
- Raccourci clavier : ⏎ (touche “Entrée”).

![](img/interface.png)

Si c'était facile, cliquez sur “Facile”. La photo de l'élève sera alors sortie de la liste.
- Raccourci clavier : &rarr; (flèche droite)

Si c'était difficile, cliquez sur “Difficile”. La photo reste dans la liste.
- Raccourci clavier : &larr; (flèche gauche)

Tant qu'il reste des photos dans la liste, l'outil parcourt la liste jusqu'à ce que vous ayez retrouvé tous les prénoms des élèves.

![](img/endMessage.png)

## Un outil libre et gratuit

Trombiquiz est diffusé sous licence libre. N'hésitez pas à modifier le script pour qu'il fonctionne avec une autre application. Les [sources](https://forge.apps.education.fr/trombiquiz/trombiquiz.forge.apps.education.fr) sont sur la Forge des Communs Numériques Éducatifs.

Si vous avez un problème ou une demande d'évolution de l'outil, n'hésitez pas à me contacter, en utilisant de préférence les “[tickets](https://forge.apps.education.fr/trombiquiz/trombiquiz.forge.apps.education.fr/-/issues)”. Vous pouvez sinon me contacter via les [réseaux sociaux](https://eyssette.forge.apps.education.fr).