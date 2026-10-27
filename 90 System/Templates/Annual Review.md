---
type: annual-review
year: "{{title}}"
date: "{{date:YYYY-MM-DD}}"
cssclasses:
  - signal-dashboard
---
# {{title}} annual review

[[Home]] · [[05 Journal/Reviews/Reviews|Reviews]] · [[01 Projects/Projects|Projects]]

Name this note with the four-digit review year **before** inserting this template. Evidence below stays tied to that year. Use it to write the story of your contribution, not just a task count.

## Contribution summary

**The most useful work I delivered:**

**What changed because of my work:**

**Three outcomes I want my manager to remember:**

1.
2.
3.

## Work across the year

Include software delivery, offensive campaigns, AppSec audits, detection work, and the smaller requests that enabled other people.

| Work / contribution | My role | Outcome or impact | Evidence |
| --- | --- | --- | --- |
| Software engineering | | | |
| Pentesting / red teaming | | | |
| Application security | | | |
| Detection engineering | | | |
| Ad hoc requests / team support | | | |

## Ad hoc work that would be easy to forget

**Requests answered and people unblocked:**

**Repeated problems I reduced or eliminated:**

**Examples of ownership, collaboration, or knowledge sharing:**

## Learning and next year

**What I learned and put into practice:**

**What caused avoidable context switching or delays:**

**What to continue, stop, or change:**

**Next year's priorities:**

1.
2.
3.

## Evidence: daily outcomes

These are daily bullets you marked as wins, including small ad hoc contributions. Add missing outcomes to the relevant dated daily note.

```query
path:"05 Journal/Daily/{{title}}/" tag:#win line:(/^\s*- #win\s/)
```

## Evidence: completed projects and campaigns

![[90 System/Bases/Annual Projects.base#Completed in review year]]

## Evidence: completed personal actions

Requires Tasks with completion-date recording enabled. Tasks count by **completion date**, even if they were created in a previous year or their project is archived.

```tasks
done
tags include #task
path does not include 90 System
done in {{title}}
sort by done
group by filename
```

### Completed actions missing a completion date

These cannot be assigned to a year reliably. Add the actual completion date if known; do not assume it from file modification time.

```tasks
done
tags include #task
path does not include 90 System
no done date
group by filename
```

## Evidence: daily records for this year

Use these to review context that did not become a checkbox or a win.

![[90 System/Bases/Annual Days.base#Daily records]]
