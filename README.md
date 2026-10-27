# AfriSoma — Kiswahili Learning Prototype

A high-fidelity, single-file mobile prototype for learning Kiswahili. Built with vanilla HTML, CSS, and JavaScript — no build step, no dependencies, no framework. Open the file and it runs.

![AfriSoma](icon.svg)

## Live demo

[Add your Netlify or GitHub Pages URL here]

## What's inside

AfriSoma is a complete interactive learning app prototype with:

- **Nyumbani** — Home dashboard with greeting card, hero carousel, feature tiles, and learning goal
- **Kujifunza** — Learning hub with Kozi / Masomo / Mafunzo tabs, lessons, and drills
- **Maktaba** — Library with Hadithi / Riwaya / Tamthilia / Nyaraka, book reader, and dialog viewer
- **Michezo** — Three quiz games: Sokoni, Ngeli ya I-ZI, Wakati Uliopita
- **Maendeleo** — Progress ring, completion stats, recent activity
- **Wasifu** — Profile with editable name, voice toggle, and data reset
- **Zaidi** — More menu with Kamusi, Mipango, Vyeti, and Mwalimu Live
- **Mwalimu Live** — Live class sessions, Q&A submission, and reminders
- **Kamusi** — Bilingual dictionary with search and example sentences

## Interactions

- **Bottom navigation** switches between the five main sections without losing state
- **Kujifunza and Maktaba tabs** re-render their lists in place
- **Hamburger menu** opens a left-side drawer; tap the backdrop or press `Esc` to close
- **Lesson screen** plays simulated audio and gives instant quiz feedback
- **Book reader** opens a detail sheet; tapping word chips shows dictionary entries
- **Mwalimu Live** lets you join sessions and submit questions
- **Profile** persists your name, voice preference, and completed lessons in `localStorage`
- **Voice** uses the browser's `speechSynthesis` API with automatic fallback to text

## Run locally

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/afrisoma-prototype.git
cd afrisoma-prototype

# Open in browser
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
