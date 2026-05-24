# Monday Lite

A single-file simplified clone of Monday.com — board-based project tracker with multiple views.

**Open `index.html` in any modern browser.** No build step, no backend, no install. Data persists to `localStorage` in the browser.

## Features

- **Boards** — multiple boards in a sidebar, each with its own columns/groups/items
- **Groups** — collapsible labeled sections with colored bars
- **Columns** — typed cells: Status, Text, Date, Person, Number
- **Three views** per board:
  - **Table** — classic Monday-style grid with inline cell editors
  - **Kanban** — cards bucketed by status, drag-and-drop to update
  - **Calendar** — items plotted on a month grid by date
- **Status pills** — bold colored labels with per-column option sets (e.g. Status vs. Priority vs. Channel)
- **Person assignments** — multi-assign with avatar chips
- **Item detail drawer** — right-side panel with all fields editable
- **Search · Filter · Sort** — live search by name, filter chips per status/person, sort by any column
- **People manager** — add/rename/remove people across all boards
- **JSON export / import** — backup or restore your full workspace
- **localStorage** — single-user, all data lives in your browser

## Stack

- Single HTML file
- Vanilla JS
- Tailwind CSS (via CDN)
- Lucide icons (via CDN)
- Inter font (Google Fonts)

## Versioning

- **v1.0** — initial single-file build

Version appears in the footer.

## Notes

- The browser console will show a Tailwind CDN production warning. This is expected — the no-build single-file design uses the Play CDN intentionally.

## Layout

```
┌─────────────────────────────────────────────────┐
│ Monday Lite                  Export · Import    │
├──────────────┬──────────────────────────────────┤
│ BOARDS       │ Board name      People · New    │
│              ├──────────────────────────────────┤
│ • Roadmap    │ Table · Kanban · Calendar  ⊕ ↕  │
│ • Marketing  │                                  │
│              │ [view body]                      │
│              │                                  │
├──────────────┴──────────────────────────────────┤
│ Monday Lite · single-file work OS         v1.0  │
└─────────────────────────────────────────────────┘
```

## Roadmap (v1.1+)

- Multi-user / sharing
- Real-time collaboration
- Automations & integrations
- File attachments
- Dashboards/widgets
- Timeline/Gantt/Form/Chart views
- Activity log / notifications
