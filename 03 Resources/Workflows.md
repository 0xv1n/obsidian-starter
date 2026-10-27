# Working with the vault

[[Home]] · [[START HERE]] · [[Follow-ups]]

## Capture an interruption in seconds

In today's note, write who asked, the request, and a source link. If it needs action, make that line a task. A deadline is a promise; a scheduled date is when you want to work on it or check in.

Copyable examples below are illustrative, not live tasks. Replace the dates and source URLs.

```markdown
- [ ] #task Review the parser change requested by Alex [GitLab MR](https://gitlab.example.com/group/repo/-/merge_requests/42) 📅 2026-10-28
- [ ] #task #waiting Ask Priya whether the test account is ready [Teams thread](https://teams.example.com/thread) ⏳ 2026-10-27
- [ ] #task Clarify the scope of the new audit request [Jira](https://jira.example.com/browse/SEC-123)
```

Keep checklists without a personal commitment untagged. Only `#task` checkboxes appear on Follow-ups. This prevents a campaign's test checklist from overwhelming your personal actions.

## Resume work after a switch

Before leaving a project, update its `next` and `waiting_on` properties, then add a sentence under **Resume here**:

> Implemented the parser and covered normal input. Empty-event test still fails. Next: inspect the normalization branch in the linked MR. Waiting on the telemetry owner for a representative sample; chase Thursday.

For short ad hoc work, use the same prompts in the daily note. Do not create a project for every small request.

## Make meeting actions usable

Put attendees in the property list, link the project, and write high-level minutes. Capture decisions with the reason and owner.

Write only **your actions** as `#task` checkboxes. If somebody else promises something, record their commitment in the table. Add your own `#task #waiting` chase action if you need it. Give it a scheduled date so it resurfaces.

For an ordinary daily standup, use Standup. Use Meeting when a project conversation needs purpose, decisions, and open questions.

## Turn small work into review evidence

At day end, write a concrete outcome in the daily note. Start the bullet exactly with `#win`, then describe your contribution, effect, and a link.

```markdown
- #win Unblocked the deployment by tracing the CI credential failure and documenting the fix. [GitLab MR](https://gitlab.example.com/group/repo/-/merge_requests/43)
- #win Answered the team's auth-design request; clarified the trust boundary and agreed a follow-up with the service owner. [Teams thread](https://teams.example.com/thread)
```

These examples are evidence patterns, not claims about your work. Include only outcomes you can support. A small request is worth recording if it helped someone, reduced risk, improved coverage, or saved repeated effort.

The annual review collects wins from daily notes under the selected year's folder, Tasks items completed that year, and projects with a matching `completed` date. Long-running project contributions still count through daily outcomes.

## End-of-week reset, about ten minutes

1. Triage Inbox and any loose daily requests.
2. Review overdue, waiting, and undated actions. Clarify dates instead of silently letting them slide.
3. Update each active project's next step and blockers.
4. Add any missed outcomes to the dated daily notes.
5. Close and archive finished projects.

## Finding meetings

- **Latest 10** sorts by meeting date, then time, newest first. Future-dated meetings stay in All meetings and month views.
- **By month** groups automatically from the date property.
- **By project** uses the project link. Project notes also show their linked meetings.
- **Quick tag links** limit Search to meeting notes.
- To find an attendee, open All meetings and add an attendees filter, or use Search with `[type:meeting] [attendees:Name]`.

Keep the meeting date correct when entering old minutes. Editing an old meeting should not make it look newly held.
