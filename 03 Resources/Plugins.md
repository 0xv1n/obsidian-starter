# Plugins and appearance

[[Home]] · [[START HERE]]

The starter uses core features for notes and meeting dashboards, plus **Tasks** for cross-note personal actions. No community plugin binaries are bundled. Recommendations checked 2026-10-25 against first-party documentation.

## Core plugins used here

| Plugin | Why it helps |
| --- | --- |
| [Daily notes](https://obsidian.md/help/plugins/daily-notes) | Creates today's note with the configured template and year folder. |
| [Templates](https://obsidian.md/help/plugins/templates) | Inserts the meeting, standup, project, campaign, and annual templates. |
| [Bases](https://obsidian.md/help/bases) | Live meeting/project views, filtering, and month grouping. |
| [Search](https://obsidian.md/help/plugins/search) | Finds request text, meeting tags, attendees, and annual outcome evidence. |
| [Bookmarks](https://obsidian.md/help/plugins/bookmarks) and [Quick switcher](https://obsidian.md/help/plugins/quick-switcher) | Fast return to Home, meetings, and active work. |
| [Backlinks](https://obsidian.md/help/plugins/backlinks), Properties, and Outline | Navigate related work and long notes. |
| [Note composer](https://obsidian.md/help/plugins/note-composer) | Extract growing daily-note content into a separate note. |
| [File recovery](https://obsidian.md/help/plugins/file-recovery) | Recover recent local note edits. |

These are enabled in the supplied configuration. Canvas is available for occasional system sketches; it is not required by a workflow.

## Community: start with Tasks

[Tasks](https://github.com/obsidian-tasks-group/obsidian-tasks) is the one community plugin needed for the prepared due/overdue dashboard and annual completed-task lists. It queries Markdown checkboxes across notes and lets you edit or complete the source task from a result.

Install **Tasks** by **Obsidian Tasks Group** in Settings → Community plugins. Leave Global filter empty; the supplied queries select `#task` themselves. Enable completion-date recording. Use the plugin's **Create or edit task** command to enter dates without memorizing symbols. [Task filters](https://publish.obsidian.md/tasks/Queries/Filters), [project documentation](https://github.com/obsidian-tasks-group/obsidian-tasks).

## Optional, only when the friction appears

| Plugin | Add it when | Tradeoff |
| --- | --- | --- |
| [QuickAdd](https://github.com/chhoumann/quickadd) | You want a shortcut to append a request to today's note or create a named meeting note. | Capture choices need configuration; the starter's core shortcuts already work. |
| [Calendar](https://github.com/liamcain/obsidian-calendar-plugin) | You prefer clicking a date to find or backfill daily notes. | An extra navigation plugin, not a meeting calendar or Teams integration. |
| [Templater](https://github.com/SilentVoid13/Templater) | You want prompted attendees/project fields or automatic note naming. | Adds a second template system and scripting. Core Templates is sufficient here. |

No Dataview is needed for the supplied meeting dashboards; Bases handles those views. No Periodic Notes is needed for a manually created annual review. Avoid adding both just to reproduce existing functionality.

## Readable appearance

**Default theme + the local Signal snippet** is the chosen setup: warm off-white background, dark green-gray text, restrained teal links, 16px text, and a comfortable line length. Dashboard pages are wider for tables. A matching dark palette is included if you switch later.

The styling uses Obsidian's documented [CSS snippets](https://obsidian.md/help/snippets) and [CSS variables](https://docs.obsidian.md/Reference/CSS%20variables/About%20styling), with local system fonts. Change it in `.obsidian/snippets/signal.css`.

If you later choose a community theme, the only proposed alternative is [Minimal](https://github.com/kepano/obsidian-minimal) with [Minimal Theme Settings](https://github.com/kepano/obsidian-minimal-settings). Disable Signal first to avoid two competing palettes. Neither is required for this vault.
