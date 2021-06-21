# Repo Project

Repo Project is a multi-faceted project for development.
At this time, its facets are:
- GitHub
  - hosting for git repository(ies)
  - storage of Issues, Issue labels, other project details
  - automation for some aspects of devops workflow via Actions
<br/><br/>
- ZenHub
  - Kanban boards for project and issue management
  - Roadmaps, Initiatives and Epics/Projects for a high-level view of product development
    - in ZenHub, Initiatives are shown as groups of Projects with no content.
      - we use Epics with label Initiative to support that planning level
  - Projects and Epics for planning based on Feature development
  - Issues with IntelliJ Tasks for implementing Feature development
  - Releases and Milestones/Sprints for time-based planning
<br/><br/>
- IntelliJ IDE
  - extensive build tools for all expected coding and documentation requirements
<div style="page-break-after: always;"></div>

## Issue Labels

| group | # | color | label | description |
|:---|---:|:---:|:---:|:---|
| | #d73a4a | <span style="background-color: #d73a4a">&nbsp;&nbsp;&nbsp;&nbsp;</span> | bug | software defect |
| | #6B8E23 | <span style="background-color: #6B8E23">&nbsp;&nbsp;&nbsp;&nbsp;</span> | techDebt | technical debt |
| | #DDAB8C | <span style="background-color: #DDAB8C">&nbsp;&nbsp;&nbsp;&nbsp;</span> | docs | technical documentation  |
| | #FFC0CB | <span style="background-color: #FFC0CB">&nbsp;&nbsp;&nbsp;&nbsp;</span> | CE | continuing developer education |
| Epics | | | | |
| | #3E4B9E | <span style="background-color: #000064">&nbsp;&nbsp;&nbsp;&nbsp;</span> | Epic | Standard Epic |
| | #005C00 | <span style="background-color: #006400">&nbsp;&nbsp;&nbsp;&nbsp;</span> | Roadmap | Roadmap Project |
| | #781010 | <span style="background-color: #640000">&nbsp;&nbsp;&nbsp;&nbsp;</span> | Initiative | Initiative Epic |
| Issues to Fix | | | | |
| | #E4E669 | <span style="background-color: #E4E669">&nbsp;&nbsp;&nbsp;&nbsp;</span> | fix issue: content | fix issue content |
| | #E4E669 | <span style="background-color: #E4E669">&nbsp;&nbsp;&nbsp;&nbsp;</span> | fix issue: update |update issue |
| | #E4E669 | <span style="background-color: #E4E669">&nbsp;&nbsp;&nbsp;&nbsp;</span> | fix issue: links | fix issue relationships |
| | #E4E669 | <span style="background-color: #E4E669">&nbsp;&nbsp;&nbsp;&nbsp;</span> | fix issue: validity | Is this issue valid now? |
| | #E4E669 | <span style="background-color: #E4E669">&nbsp;&nbsp;&nbsp;&nbsp;</span> | fix issue: unfinished | issue edit is incomplete |
| | #E4E669 | <span style="background-color: #E4E669">&nbsp;&nbsp;&nbsp;&nbsp;</span> | fix issue: duplicate | issue or pull request already exists |
| Topics | | | | |
| | #A909DA | <span style="background-color: #A909DA">&nbsp;&nbsp;&nbsp;&nbsp;</span> | devops | Development / Operations |
| | #F95650 | <span style="background-color: #F95650">&nbsp;&nbsp;&nbsp;&nbsp;</span> | CI/CD | continuous integration/development |
| | #11C6F1 | <span style="background-color: #11C6F1">&nbsp;&nbsp;&nbsp;&nbsp;</span> | git | working with git |
| | #8B4513 | <span style="background-color: #8B4513">&nbsp;&nbsp;&nbsp;&nbsp;</span> | webdev | web development |
| Platforms | | | | |
| | #e99695 | <span style="background-color: #e99695">&nbsp;&nbsp;&nbsp;&nbsp;</span> | macos | macos platform |
| | #4682B4 | <span style="background-color: #4682B4">&nbsp;&nbsp;&nbsp;&nbsp;</span> | ios | ios platform |
| Languages | | | | |
| | #AEE9A9 | <span style="background-color: #AEE9A9">&nbsp;&nbsp;&nbsp;&nbsp;</span> | javascript | javascript |
| | #fbca04 | <span style="background-color: #fbca04">&nbsp;&nbsp;&nbsp;&nbsp;</span> | zsh | Z Shell |
| Tools | | | | |
| | #c055b8 | <span style="background-color: #c055b8">&nbsp;&nbsp;&nbsp;&nbsp;</span> | tools | development tools |

## Tasks

### Create Repo Project

- create a new GitHub repository; see [Create New Repository](../tools/GitHub.md#create-new-repository)
- add new project to a ZenHub Workspace; see [Add Repo Project to ZenHub Workspace](../tools/ZenHub.md#add-repo-project-to-zenhub-workspace)
- open new project in IntelliJ; see [Open Repository as Project](../tools/IntelliJ.md#open-repository-as-project)
