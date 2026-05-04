# Locallend_Gruppe-5

## 1. Team Composition
*   **Team Name:** Group 5 - LocalLend
*   **Repository Access:** Unser GitHub-Repository ist auf "public" gestellt und die Dokumentation ist über GitHub Pages erreichbar.
*   **Contributors & Meta-Goals****:**
    *   **Tuba**
        *   *Target Grade:* 1.0
        *   *Personal Goal:* Das Flask-Routing richtig verstehen und das Backend für die Ausleih-Funktion eigenständig zum Laufen bringen.
    *   **Yves**
        *   *Target Grade:* 1.0
        *   *Personal Goal:* Ein sauberes Frontend mit HTML und Bootstrap bauen, komplett ohne verbotene JavaScript-Hacks.
    *   **Wendy**
        *   *Target Grade:* 1.0
        *   *Personal Goal:* Die SQLite-Datenbank logisch aufsetzen und sicherstellen, dass sie reibungslos mit Flask interagiert.
    *   **Maryam**
        *   *Target Grade:* 1.0
        *   *Personal Goal:* Den Git-Workflow strukturieren und dafür sorgen, dass unsere Pull Requests im Team ohne Konflikte funktionieren.

## 2. Value Proposition
Unsere App "LocalLend" ist eine klassische zweiseitige Plattform (Two-Sided Platform) für Tool-Sharing auf dem Campus und in der Nachbarschaft.

*   **Target User & Problem:** Wir richten uns primär an Studierende und Anwohner. Das Problem: Für einmalige Projekte (z.B. Umzug, kleine Reparaturen) werden teure Werkzeuge benötigt (z.B. Schlagbohrmaschine)[cite: 6]. Ein Neukauf ist für Studierende zu teuer (Pain). Andere besitzen diese Dinge, lassen sie aber meist ungenutzt liegen, weil sie Angst haben, sie an Fremde zu verleihen und sie beschädigt zurückzubekommen (Pain).
*   **App-based Solution:** Wir bauen eine Web-App, die das lokale Ausleihen und Verleihen sicher und übersichtlich organisiert.
*   **Die zwei Seiten der Plattform**:
    *   *Seite A (Die Verleiher):* Stellen ihre ungenutzten Werkzeuge ein. Als "Pain Reliever" gegen die Angst vor Beschädigung kann bei jedem Tool transparent eine verpflichtende Kaution hinterlegt werden, die Sicherheit schafft.
    *   *Seite B (Die Leiher):* Suchen gezielt nach Werkzeugen, können diese unkompliziert anfragen und sparen sich das Geld für einen Neukauf (Gain Creator).

## 3. Target Scope (Visual Scoping)
Um den Umfang unserer App visuell abzugrenzen, haben wir die Kern-Screens als Low-Resolution Prototypes (Scribbles) skizziert.

*   **Scribble 1: Dashboard / Startseite**
    *   Eine zentrale Suchleiste ganz oben. Darunter sieht man direkt Kacheln mit den Dingen, die gerade in der Community verfügbar sind.
    *   `![Dashboard Skizze]`

*   **Scribble 2: Detailansicht & Action**
    *   Wenn man auf ein Werkzeug klickt, sieht man das Foto, wem es gehört und wie hoch die Kaution ist. Darunter ein klarer "Jetzt anfragen"-Button.
    *   `![Detailansicht Skizze]`

*   **Scribble 3: User Profile / Inventar**
    *   Die eigene Übersicht aufgeteilt in: "Was biete ich gerade an?" und "Was habe ich aktuell von anderen ausgeliehen?".
    *   `![Profil Skizze]`

*   **Scribble 4: Upload-Screen**
    *   Ein simples Formular für die Verleiher, um neue Gegenstände hochzuladen (Titel, Beschreibung, Foto, und das Feld für die Kaution).
    *   `![Upload Skizze]`

**Unser Happy Path (User Flow):**
Ein Nutzer sucht auf dem **Dashboard (1)** nach einem Werkzeug, klickt auf die **Detailansicht (2)**, akzeptiert die Kaution und leiht es aus. Der Verleiher hat dieses Werkzeug zuvor über den **Upload-Screen (4)** eingestellt und kann den Status nun in seinem **User Profile (3)** überwachen.

## 4. AI Directory (Generative AI Use Policy)
Wir dokumentieren hier transparent unseren Einsatz von KI-Tools gemäß den Richtlinien des Moduls:
*   **Tool:** Gemini (Chat-Interface).
*   **Art der Nutzung:** Wir haben die KI als interaktiven Sparringspartner genutzt, um die Pains und Pain Relievers unserer Value Proposition sauber zu definieren und die Markdown-Struktur für diese README zu generieren.
*   **Erklärung:** Wir übernehmen die volle Verantwortung für alle formulierten Inhalte. Wir haben streng darauf geachtet, **keine** Agentic AI (wie Copilot Agents, Aider etc.) einzusetzen, die autonom Dateien verändert, Code generiert oder Commits erstellt.
