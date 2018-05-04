# Git auf Kölsch

Die tägliche Kommunikation in deutschen Entwicklungsteams, die `git`
(übersetzt: `Schwachkopf` oder `Depp`) anwenden, ist oft das feinste Denglish.
_"Kannst du bitte pullen"_ oder _"Hast du gepusht"_ sind nur zwei
der oft seltsam klingenden Konstruktionen.

Git auf Deutsch schafft Abhilfe!

## Vorschläge

Es folgen zwei Tabellen mit Vorschlägen für den täglichen Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | opmaache              |
| add         | adden              | dobeidun            |
| pull        | pullen             | trecke                |
| push        | pushen             | däue               |
| clone       | clonen             | nohmaache            |
| fetch       | fetchen            | holle                 |
| branch      | branchen           | abzweigen             |
| commit      | commiten           | avzweige             |
| rebase      | rebasen            | (neu) ääden           |
| diff        | diffen             | ungerscheide         |
| merge       | mergen             | vereinige            |
| fork        | forken             | jabeln                |
| stash       | stashen            | bunkere               |
| tag         | taggen             | markiere             |
| cherry-pick | cherry-picken      | Rosinen eruspecke  |
| checkout    | checkouten         | nemme                |

| Substantiv    | Aktueller Gebrauch | Vorschlag            |
|---------------|--------------------|----------------------|
| git           | git                | Pappnas                 |
| github        | github             | Pappnasdrihkrütz      |
| gitlab        | gitlab             | Pappnashütt          |
| gitea         | gitea              | Pappnasteebüggel                
| bitbucket     | bitbucket          | Gebessemmer          |
| repository    | repo               | Lagerhall          |
| branch        | branch             | Zwig                |
| commit        | commit             | Übergabe             |
| log           | log                | Tageboch             |
| pull request  | pull request       | Treckefroge         |
| merge request | merge request      | Verbingefroge |
| stash         | stash              | Bunker               |
| status        | status             | Zostand              |
| tag           | tag                | Markierung           |
| origin        | origin             | Herkunf             |
| master        | master             | Meister              |

## Beispiele

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Deppendrehkreuz drücken?

    - Dafür habe ich eine neue Lagerstätte eröffnet, mach sie nach und nimm dir den Entwicklungszweig.

    - Nein, drücke das gleich zum Meister im Ursprung!

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Bunker übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Meisterzweig heraus.

    - Gabeln Sie auf Deppendrehkreuz!

## Depp auf Deutsch anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Depp auf Deutsch in Deine Konsole bringt. Da Depp keine Umlaute zulässt, müssen wir in den Befehlen leider darauf verzichten. Nimm folgende Änderungen in deiner `~/.gitconfig` vor:

    git config --global alias.eroeffne init
    git config --global alias.machnach clone
    git config --global alias.zieh pull
    git config --global alias.fueghinzu add
    git config --global alias.drueck push
    git config --global alias.pfusch push --force
    git config --global alias.zweig branch
    git config --global alias.verzweige branch
    git config --global alias.uebergib commit
    git config --global alias.erde rebase
    git config --global alias.unterscheide diff
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag
    git config --global alias.nimm checkout
    git config --global alias.tagebuch log
    git config --global alias.zustand status

Und füge die folgende Zeile zu deiner `~/.bashrc` (oder das Äquivalent auf deinem Betriebssystem) hinzu:

    alias depp=git
