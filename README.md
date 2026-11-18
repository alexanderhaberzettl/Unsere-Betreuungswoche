# Unsere Betreuungswoche

*[English version below](#english)*

**Live:** https://alexanderhaberzettl.github.io/Unsere-Betreuungswoche/

Ein einfacher Wochenplan (Montag bis Freitag, 7 bis 18 Uhr), mit dem Familien auf einen Blick sehen, ob die Kinderbetreuung lückenlos abgedeckt ist.

## Was die App kann

- **Personen und Einrichtungen hinzufügen:**
  - **Elternteil:** Arbeitszeiten eintragen, außerhalb davon gilt die Person als verfügbar. Mit Wochenstunden (z. B. 30 h) und Soll/Ist-Anzeige.
  - **Weitere Person:** z. B. Großeltern, Babysitter oder Tagesmutter, mit den Zeiten, in denen sie betreuen.
  - **Einrichtung:** Kita, Schule oder Hort, mit den Zeiten pro Tag und wer bringt und wer abholt.
- **Kalender:** Zeiten direkt mit der Maus ziehen oder für mehrere Tage auf einmal eintragen.
- **Lücken und Hinweise:** Zeiten ohne Betreuung werden rot markiert. Die App warnt, wenn die Person zum Bringen oder Abholen zu der Zeit arbeitet oder nicht eingeplant ist.
- **Mehrere Kinder:** Kinder anlegen und bei jeder Zeit einer Einrichtung oder weiteren Person auswählen, für welches Kind sie gilt (z. B. Anna bis 12:00, Ben bis 15:00 im selben Kindergarten). Über den Stift lässt sich eine Einrichtung auch als Ganzes einem Kind zuordnen. Lücken werden pro Kind angezeigt, im Kalender lässt sich nach Kind filtern.
- **Plan teilen:** Ein Klick erzeugt einen Link, der den ganzen Plan enthält.
- **Deutsch und Englisch:** Die App folgt der Sprache deines Geräts. Mit dem Schalter DE/EN oben rechts lässt sie sich umstellen; die Wahl wird gemerkt.

## Datenschutz

- **Nichts wird irgendwo gespeichert.** Es gibt keinen Server, keine Datenbank und kein Konto.
- **Kein Tracking, keine Analytics, keine Cookies.** Die Seite lädt keine Skripte, Schriften oder sonstigen Inhalte von Drittanbietern.
- **Alles bleibt privat in deinem Browser.** Dein Plan wird nur im lokalen Speicher deines Browsers (localStorage) abgelegt.
- **Teilen über die URL.** Beim Teilen wird der Plan komprimiert und im Link hinter dem `#` kodiert. Dieser Teil eines Links wird vom Browser nie an einen Server geschickt, auch nicht an GitHub. Nur wer den Link bekommt, kann den Plan sehen.

Hinweis: Wer einen geteilten Link hat, kann den Plan lesen. Teile ihn also nur mit Personen, die ihn sehen sollen.

## Technik

Eine einzige Datei (`index.html`) mit HTML, CSS und JavaScript, ohne Abhängigkeiten. Gehostet mit GitHub Pages.

---

# English

**Live:** https://alexanderhaberzettl.github.io/Unsere-Betreuungswoche/

A simple weekly planner (Monday to Friday, 7 am to 6 pm) that lets families see at a glance whether childcare is fully covered. The app is available in English and German; it follows your device language, and the DE/EN switch in the top right remembers your choice.

## Features

- **Add people and places:**
  - **Parent:** enter working hours; outside of them the person counts as available. Includes weekly hours (e.g. 30 h) with a planned vs. entered check.
  - **Other person:** e.g. grandparents, a babysitter or a nanny, with the times they look after the children.
  - **Childcare or school:** kindergarten, school or after-school club, with the times per day plus who drops off and who picks up.
- **Calendar:** drag times directly with the mouse, or enter them for several days at once.
- **Gaps and warnings:** times without anyone available are marked red. The app warns when the person doing drop-off or pick-up is working at that time or isn't scheduled.
- **Multiple children:** add children and choose for each time at a kindergarten, school or with another person which child it is for (e.g. Anna until 12:00, Ben until 15:00 at the same kindergarten). The pencil icon on a kindergarten or school also assigns all its times to a child at once. Gaps are shown per child, and the calendar can be filtered by child.
- **Share a plan:** one click creates a link that contains the entire plan.

## Privacy

- **Nothing is stored anywhere.** There is no server, no database and no account.
- **No tracking, no analytics, no cookies.** The page loads no scripts, fonts or other content from third parties.
- **Everything stays private in your browser.** Your plan is only kept in your browser's local storage (localStorage).
- **Sharing via the URL.** When you share, the plan is compressed and encoded in the link after the `#`. Browsers never send this part of a link to any server, not even to GitHub. Only people who have the link can see the plan.

Note: anyone with a shared link can read the plan, so only share it with people who should see it.

## Tech

A single file (`index.html`) with HTML, CSS and JavaScript and no dependencies. Hosted on GitHub Pages.
