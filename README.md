# mizan-donnees

بيانات قانونية تونسية عمومية يستعملها «ميزان»، مساعد قانوني يعمل على حاسوب المحامي دون اتصال بالإنترنت.

Données juridiques tunisiennes **publiques** utilisées par Mizan, un assistant juridique qui
fonctionne sur le PC de l'avocat, hors ligne.

## Contenu

Les données sont publiées dans les [Releases](../../releases) de ce dépôt :

- l'**index initial** (codes en vigueur, JORT récent, arrêts de la Cour de cassation) ;
- puis un **petit paquet de mise à jour par numéro du JORT**, pour ne télécharger que la nouveauté.

Ce dépôt ne contient encore aucune donnée : la première release viendra avec le premier index.

## Sources

| Source | Contenu |
|---|---|
| Journal Officiel de la République Tunisienne (IORT), via la copie [jort.tn](https://jort.tn/) | Lois, décrets-lois, décrets, arrêtés |
| [legislation.tn](http://www.legislation.tn/) | Codes en vigueur |
| [cassation.tn](http://www.cassation.tn/) | Arrêts de la Cour de cassation |

## Statut juridique

- Les textes officiels de nature législative, administrative ou judiciaire et leurs traductions
  officielles ne sont pas protégés par le droit d'auteur (loi n° 94-36 du 24 février 1994,
  article premier, dernier alinéa ajouté par la loi n° 2009-33).
- **Seule la version arabe publiée au JORT fait foi** (loi n° 93-64 du 5 juillet 1993).
  Les fichiers de ce dépôt sont une copie de travail : vérifiez toujours le texte officiel.

## Ce que ce dépôt ne contient jamais

Aucune question d'avocat, aucune donnée de client, aucune donnée personnelle collectée par Mizan.
L'historique des avocats reste chiffré sur leur propre ordinateur.

## Intégrité

Chaque paquet sera accompagné de son empreinte SHA-256 et d'une signature. L'application Mizan
vérifie la signature avant d'installer une mise à jour. La clé publique sera publiée ici.
