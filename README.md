# Git-Versenken #

Dies ist ein kleines Spiel im Sinne von Schiffe versenken um den besseren Umgang mit Pull-Requests zu lernen. Forken von Repos und das Einreichen der Änderungen als Pull Request sind ein elementarer Bestandteil des [Github Workflows](https://guides.github.com/introduction/flow/index.html).
Ich empfehle euch davor das absolvieren von [git-game](https://github.com/git-game/git-game). Wenn dazu Fragen sind helfe ich gern.

## Zum Spiel ##
* Ziel: alle Schiffe versenken
* Ausgangspunkt: ein 10x10-Raster
* Quelle: [Wikipedia](https://de.wikipedia.org/wiki/Schiffe_versenken)

## Wie erfolgt der Spielzug? ##
1. Dieses Repo [forken](https://help.github.com/articles/fork-a-repo/) (nur am Anfang nötig)
2. "Fix" in Form eines Spielzuges einreichen. Als Spielzug einfach das vermutete Feld (ja, nur ein Feld pro Zug) mit dem KLEINbuchstaben eures Vornamens versehen.
3. Die Änderung ist jetzt in eurem lokalen Repo, also commit&push in euer Github-Repo
4. Und jetzt stellt ihr einen PULL-Request an mich und ich kann euren Zug auswerten
5. Wieder von vorn, davor aber noch die Änderungen der anderen reinmergen ;-) [Link](https://help.github.com/articles/syncing-a-fork/)

## Symbolik ##
* + - unentdecktes Gebiet
* x - bereits beschossen, aber ins Wasser gefallen
* o (am Beispiel Oliver) - vom Spieler "Oliver" beschossenes Feld
* O (am Beispiel Oliver) - vom Spieler "Oliver" getroffenes Feld
..bereits beschossene Felder können nicht nochmal beschossen werden, außerdem sollten in meinem Upstream niemals Kleinbuchstaben (außer x) auftauchen da ich aus jedem "Schuss" ein x oder einen Großbuchstaben mache.

## Zeitraum ##
Pro Woche hat jeder zwei Schüsse. Trefferauswertung ist immer bis *Mittwoch*- und *Sonntag*abend (-> wer bis dahin nicht "geschossen" hat, rutscht in die nächste Runde).

Na denn mal los ihr Landratten :rocket: :ship:

Viel Erfolg!
