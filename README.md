# Obsidian Starter

A desktop Obsidian vault for software engineering, security projects, meetings, and ad hoc work. It keeps context, personal next actions, decisions, and evidence of impact alongside links to your official work systems.

## Get started

1. Download and extract this repository, or clone it.
2. In Obsidian, choose **Open folder as vault** and select the repository folder. Include the supplied `.obsidian` directory.
3. Open [START HERE](START%20HERE.md), then [Home](Home.md).
4. Install **Tasks** by **Obsidian Tasks Group** for the follow-up dashboard and annual completed-action lists. Leave its Global filter empty and enable **Set done date on every completed task**.

Use a current desktop Obsidian release with Bases enabled. No community plugin code, theme, external font, or integration credentials are bundled. Empty dashboards are expected until you create notes.

## Included workflows

| Workflow | Entry point |
| --- | --- |
| Capture and resume interrupted work | Daily notes, Inbox, project `next` and `waiting_on` properties |
| Track personal commitments | Follow-ups, with due dates and scheduled chase dates |
| Record meetings | Standup and Meeting templates; views by date, month, kind, and project |
| Deliver projects and campaigns | Project and Campaign templates with scope, actions, and outcome evidence |
| Prepare an annual review | Review template collecting daily wins, completed actions, and completed projects |

The folder structure follows PARA, with Journal and System folders for dated records and reusable configuration. Core Templates and Daily notes create notes; Bases and Search provide views. Tasks is required only for `tasks` query blocks. A built-in search fallback finds open actions without it.

This vault does not sync tasks or meetings with Jira, GitLab, Teams, or other services, and it does not send reminders. Links keep those systems connected to your notes.

## Make it yours

Edit the Area notes, source-system labels, and `.obsidian/snippets/signal.css` to suit your work. Shortcuts are **Ctrl+Alt+D** for today's note and **Ctrl+Alt+T** for inserting a template; use Cmd instead of Ctrl on macOS. The command palette provides the same commands if a shortcut conflicts.

Use a private copy for real work. `.gitignore` excludes session state, community plugin code/settings, and local planning files; it does **not** exclude notes or attachments you add. Review staged files before publishing updates.

See [Workflows](03%20Resources/Workflows.md) for examples and [Plugins](03%20Resources/Plugins.md) for dependencies and documentation.
