## Feature Branch Workflow

- new Task/branch
  - clean up existing branches, stashes, and changelists; ***Update Main Branch***
  - if new Task: create new Task [for this issue]; push
  - else: switch to existing Task; update &lt;workingBranch&gt;; push
<br/><br/>

- until **Task/branch** work complete {
  - until **push Main** {
    - until **merge to Main** {
<br/><br/>
      - ***Update &lt;workingBranch&gt;***
      - while **push branch** {
        - while **commit** {
          - while **cache** {
            - test / code / test
            - diff local changes
            - add changed files as indicated (IDE add: ocA)
          - } **cache**
          - Inspect
          - Compare with original (diff)
        - } **commit**: commit changes
        - **Update &lt;workingBranch&gt;**
     - } **push branch**: checkout &lt;branch&gt;; Compare With &lt;remote&gt;; push &lt;branch&gt;
<br/><br/>
    - ***Update &lt;workingBranch&gt; Branch***
    - } **merge to `main`** *merge &lt;branch&gt; into main line of development*
      - on main: preview merge: &lt;branch-to-merge&gt;: Show Differences
      - merge to main: `git merge --no-ff &lt;branch&gt;`
    - } **merge**
  - } **push Main**
<br/><br>
- } **Task/branch**: close active Task; remove its changelist; switch to default Task 

#### Procedures

##### ***Update Main Branch***
- checkout `main` branch; `git status; git branch --no-merged`
- git fetch (rcF); if changed:
  - origin/main: Diff with Working Tree to get changes(?); commit and push main

##### ***Update &lt;workingBranch&gt; (From Main)***
- ***Update Main Branch***; checkout &lt;workingBranch&gt;; compare with `main` (&lt;workingBranch&gt;:cw)
- if changed: checkout &lt;workingBranch&gt;; preview merge (main:cw); `git merge --no-ff main`; test; commit

<button onclick="window.print()">`Print Button`</button>
