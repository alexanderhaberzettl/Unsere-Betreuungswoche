# Unsere Betreuungswoche

**Live:** https://alexanderhaberzettl.github.io/Unsere-Betreuungswoche/

Ein einfacher Wochenplan (Montag bis Freitag, 7 bis 18 Uhr), mit dem Familien auf einen Blick sehen, ob die Kinderbetreuung lückenlos abgedeckt ist.

## Was die App kann

- **Personen hinzufügen** mit einer Rolle:
  - **Elternteil:** Arbeitszeiten eintragen, außerhalb davon gilt die Person als verfügbar. Mit Wochenstunden (z. B. 30 h) und Soll/Ist-Anzeige.
  - **Betreuung:** z. B. Großeltern oder Babysitter, mit den Zeiten, in denen sie betreuen.
  - **Kindergarten:** Betreuungszeiten pro Tag, dazu wer bringt und wer abholt.
- **Kalender:** Zeiten direkt mit der Maus ziehen oder für mehrere Tage auf einmal eintragen.
- **Lücken und Hinweise:** Zeiten ohne Betreuung werden rot markiert. Die App warnt, wenn die Person zum Bringen oder Abholen zu der Zeit arbeitet oder nicht eingeplant ist.
- **Plan teilen:** Ein Klick erzeugt einen Link, der den ganzen Plan enthält.

## Datenschutz

- **Nichts wird irgendwo gespeichert.** Es gibt keinen Server, keine Datenbank und kein Konto.
- **Kein Tracking, keine Analytics, keine Cookies.** Die Seite lädt keine Skripte, Schriften oder sonstigen Inhalte von Drittanbietern.
- **Alles bleibt privat in deinem Browser.** Dein Plan wird nur im lokalen Speicher deines Browsers (localStorage) abgelegt.
- **Teilen über die URL.** Beim Teilen wird der Plan komprimiert und im Link hinter dem `#` kodiert. Dieser Teil eines Links wird vom Browser nie an einen Server geschickt, auch nicht an GitHub. Nur wer den Link bekommt, kann den Plan sehen.

Hinweis: Wer einen geteilten Link hat, kann den Plan lesen. Teile ihn also nur mit Personen, die ihn sehen sollen.

## Technik

Eine einzige Datei (`index.html`) mit HTML, CSS und JavaScript, ohne Abhängigkeiten. Gehostet mit GitHub Pages.
