# Your work vault

This vault is designed for software projects, pentest campaigns, and unpredictable requests. Jira, GitLab, and Teams hold the official work records. Obsidian holds your context, next actions, decisions, and evidence of impact.

## Open and finish setup

1. In Obsidian, choose **Open folder as vault** and select this `obsidian-starter` folder. Use a current desktop version with **Bases** enabled.
2. Open [[Home]]. The included settings enable Daily notes, Templates, Bases, and the other core features used here.
3. Install and enable the community plugin **Tasks** by **Obsidian Tasks Group**. It powers the due/overdue queries in [[Follow-ups]] and completed-action evidence in annual reviews. Leave its **Global filter** empty and enable **Set done date on every completed task**. Queries here explicitly select the `#task` tag.
4. Appearance should be **Light**, theme **Default**, CSS snippet **signal** enabled. No community theme or external fonts are needed.

Community plugin code is not bundled or enabled. Meeting views work with core plugins immediately. Tasks query blocks become live after you install Tasks; plain checkboxes and the fallback search in [[Follow-ups]] work before then.

## Your first day

- Press **Ctrl+Alt+D** to create today's note. It goes into `05 Journal/Daily/YYYY/` and receives the Daily template automatically.
- Put new requests in the daily note, or [[00 Inbox/Inbox]] when you need a quick landing spot.
- Write personal actions as `- [ ] #task Action`. Add `📅 YYYY-MM-DD` for a real deadline. Use `#waiting` and `⏳ YYYY-MM-DD` for the date you want to chase someone.
- At each context switch, update **Resume here** in the project note or daily note.
- At day end, add a bullet beginning `#win` with what changed, why it mattered, and a source link. Include small ad hoc contributions.

Do not copy unfinished tasks into every daily note. [[Follow-ups]] finds the original tasks, and checking one there updates its source note.

## Create notes

Create a note in the destination folder, **name it first**, then press **Ctrl+Alt+T** and choose its template. On macOS, use Cmd in place of Ctrl. If a shortcut conflicts, use **Daily notes: Open today's daily note** or **Templates: Insert template** from the command palette. Templates are inserted once, not continuously updated. Edit template files in Source mode to preserve their variables.

| Note | Folder | Name | Template |
| --- | --- | --- | --- |
| Daily | `05 Journal/Daily/YYYY/` | Automatic `YYYY-MM-DD` | Daily, via Daily notes |
| Team standup | `05 Journal/Meetings/` | `YYYY-MM-DD HHmm - Standup` | Standup |
| Project meeting | `05 Journal/Meetings/` | `YYYY-MM-DD HHmm - Topic` | Meeting |
| Software or security project | `01 Projects/` | A clear outcome | Project |
| Pentest or red-team campaign | `01 Projects/` | Campaign name | Campaign |
| Annual review | `05 Journal/Reviews/` | Four-digit year, e.g. `2026` | Annual Review |

For past meetings, change the `date` and `time` properties after insertion. Meeting views use these properties, not file modification time. For a past daily note, create its dated file and insert Daily, then set its date property and heading to the intended date. For an annual review, the **filename year** controls the evidence queries, so review last year by naming the note last year's number.

## PARA, with two supporting folders

| Folder | What belongs here |
| --- | --- |
| `00 Inbox` | Unsorted requests and quick notes. New notes land here by default. |
| `01 Projects` | Work with a finish line: a software delivery, pentest campaign, audit, or detection rollout. |
| `02 Areas` | Ongoing responsibilities: engineering, offensive security, AppSec, detections, team operations. |
| `03 Resources` | Reusable knowledge, playbooks, code patterns, and reference material. |
| `04 Archive` | Inactive or completed projects and retired resources. |
| `05 Journal` | Daily records, meeting records, and annual reviews. Link these to PARA notes. |
| `90 System` | Templates, dashboard Bases, and attachments. |

Project statuses: `active`, `waiting`, `paused`, `done`. Set `completed` when a project finishes, record its outcome, then move it to Archive. Keep journal notes where they are so your year stays searchable. Resolve outstanding actions before archiving a project; the follow-up dashboard deliberately continues to find unfinished tasks in Archive.

## A few conventions

- Meeting `kind`: `standup` or `project`. Add other values only when useful.
- Meeting tags: `meeting/standup` or `meeting/project`, plus a `work/...` tag when relevant. The dashboard's tag links open a search restricted to meeting notes.
- `project` and `area` properties contain note links. Use the property editor, or quoted links such as `"[[01 Projects/Example]]"` in source mode.
- Personal actions use `#task`. A commitment owned by somebody else belongs in meeting minutes; add your own `#task #waiting` follow-up if you need to chase it.
- Outcomes use `#win` in a dated daily note. The annual review gathers these separately from completed actions.

See [[03 Resources/Workflows]] for copyable examples and [[03 Resources/Plugins]] for optional additions.
