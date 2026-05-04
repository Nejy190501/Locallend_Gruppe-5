# Locallend_Gruppe-5

## 1. Team Composition
*   **Team Name:** Group 5 - LocalLend
*   **Repository Access:** Unser GitHub-Repository ist auf "public" gestellt und die Dokumentation ist über GitHub Pages erreichbar.
*   **Contributors & Meta-Goals**
    *   **Tuba Celik (Matrikelnummer: 77206594559)**
        *   *Target Grade:* 1.7
        *   *Personal Goal:* Das Flask-Routing richtig verstehen und das Backend für die Ausleih-Funktion eigenständig zum Laufen bringen.
    *   **Jean Yves Nkwane (Matrikelnummer: 77201393552)**
        *   *Target Grade:* 1.7
        *   *Personal Goal:* Ein sauberes Frontend mit HTML und Bootstrap bauen, komplett ohne verbotene JavaScript-Hacks.
    *   **Wendy Sharonia Lontsi Doumtsop (Matrikelnummer: 77209106458)**
        *   *Target Grade:* 1.7
        *   *Personal Goal:* Die SQLite-Datenbank logisch aufsetzen und sicherstellen, dass sie reibungslos mit Flask interagiert.
    *   **Maryam Joumma (Matrikelnummer: 77207472992)**
        *   *Target Grade:* 1.7
        *   *Personal Goal:* Den Git-Workflow strukturieren und dafür sorgen, dass unsere Pull Requests im Team ohne Konflikte funktionieren.

## 2. Value Proposition
Unsere App "LocalLend" ist eine klassische zweiseitige Plattform (Two-Sided Platform) für Tool-Sharing auf dem Campus und in der Nachbarschaft.

*   **Target User & Problem:** Wir richten uns primär an Studierende und Anwohner. Das Problem: Für einmalige Projekte (z.B. Umzug, kleine Reparaturen) werden teure Werkzeuge benötigt (z.B. Schlagbohrmaschine). Ein Neukauf ist für Studierende zu teuer (Pain). Andere besitzen diese Dinge, lassen sie aber meist ungenutzt liegen, weil sie Angst haben, sie an Fremde zu verleihen und sie beschädigt zurückzubekommen (Pain).
*   **App-based Solution:** Wir bauen eine Web-App, die das lokale Ausleihen und Verleihen sicher und übersichtlich organisiert.
*   **Die zwei Seiten der Plattform**:
    *   *Seite A (Die Verleiher):* Stellen ihre ungenutzten Werkzeuge ein. Als "Pain Reliever" gegen die Angst vor Beschädigung kann bei jedem Tool transparent eine verpflichtende Kaution hinterlegt werden, die Sicherheit schafft.
    *   *Seite B (Die Leiher):* Suchen gezielt nach Werkzeugen, können diese unkompliziert anfragen und sparen sich das Geld für einen Neukauf (Gain Creator).

## 3. Target Scope (Visual Scoping)

Um den Umfang unserer App visuell abzugrenzen, haben wir die Kern-Screens als Low-Resolution Prototypes (Scribbles) skizziert.

---

### Scribble 1: Landing Page (Startseite)
Eine zentrale Suchleiste und Übersicht verfügbarer Gegenstände.

![Landing](docs/scribbles/landing.jpg)

---

### Scribble 2: Browse Items
Liste aller verfügbaren Gegenstände mit Suchfunktion.

![Browse](docs/scribbles/browse.jpg)

---

### Scribble 3: Detailansicht
Detailseite eines Gegenstands mit Beschreibung, Besitzer und Kaution.

![Detail](docs/scribbles/detail.jpg)

---

### Scribble 4: Gegenstand erstellen
Formular zum Hochladen eines neuen Gegenstands.

![Create](docs/scribbles/create.jpg)

---

### Scribble 5: Login / Registrierung
Login- und Registrierungsseite mit Rollenwahl.

![Login](docs/scribbles/login.jpg)

---

### Scribble 6: Anfragen verwalten
Übersicht über eingehende Anfragen mit Annehmen/Ablehnen.

![Requests](docs/scribbles/requests.jpg)

---

**Unser Happy Path (User Flow):**

Ein Nutzer startet auf der **Landing Page (1)**, sucht nach einem Gegenstand und wechselt zur **Browse-Seite (2)**.  
Dort klickt er auf ein Item und gelangt zur **Detailansicht (3)**, wo er eine Anfrage stellt.  
Der Verleiher sieht diese Anfrage unter **Anfragen (6)** und kann sie annehmen.  
Neue Gegenstände werden über den **Create Screen (4)** erstellt.

Dieser Ablauf zeigt die zentrale Interaktion zwischen Verleihern und Leihenden innerhalb der Plattform.


## 4. AI Directory (Generative AI Use Policy)
Wir dokumentieren hier transparent unseren Einsatz von KI-Tools gemäß den Richtlinien des Moduls:
*   **Tool:** Gemini (Chat-Interface).
*   **Art der Nutzung:** Wir haben die KI als interaktiven Sparringspartner genutzt, um die Pains und Pain Relievers unserer Value Proposition sauber zu definieren und die Markdown-Struktur für diese README zu generieren.
*   **Erklärung:** Wir übernehmen die volle Verantwortung für alle formulierten Inhalte. Wir haben streng darauf geachtet, **keine** Agentic AI (wie Copilot Agents, Aider etc.) einzusetzen, die autonom Dateien verändert, Code generiert oder Commits erstellt.
