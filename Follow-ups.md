---
type: dashboard
cssclasses:
  - signal-dashboard
---
# Follow-ups

[[Home]] · [[00 Inbox/Inbox|Inbox]] · [[Meetings]] · [[03 Resources/Workflows|Task examples]]

These live lists need the **Tasks** community plugin. Every actionable personal checkbox gets `#task`; dates are `📅` for deadlines and `⏳` for planned work or a chase date. Write the task once, in whichever note has the context.

## Overdue

```tasks
not done
tags include #task
path does not include 90 System
due before today
sort by due
```

## Due today

```tasks
not done
tags include #task
path does not include 90 System
due today
sort by priority
```

## Scheduled or ready to chase

```tasks
not done
tags include #task
path does not include 90 System
scheduled on or before today
sort by scheduled
sort by due
```

## Next 7 days

```tasks
not done
tags include #task
path does not include 90 System
due after today
due on or before in 7 days
sort by due
```

## Waiting on people

```tasks
not done
tags include #task
path does not include 90 System
tags include #waiting
sort by scheduled
sort by due
```

## Undated actions

```tasks
not done
tags include #task
path does not include 90 System
tags do not include #waiting
no due date
no scheduled date
group by filename
```

## All open actions

```tasks
not done
tags include #task
path does not include 90 System
sort by due
group by filename
```

An action may appear in several views. They all refer to the same source checkbox. A due date is a commitment; use a scheduled date for your own reminder. These are review lists, not push notifications or Jira/GitLab/Teams synchronization.

> [!note]- Without Tasks: find open actions
> This built-in Search works without a community plugin. It does not interpret due dates.
> ```query
> task-todo:(#task) -path:"90 System"
> ```
