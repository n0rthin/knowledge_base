create pr feature/SBK-222 to master in all repos and then move SBK-2153 to PO-QA
every time sb-development-backend successfully deployed move all tasks with label "ready-for-qa" to QA
every time heroku backend tests pass on master run "merge-master" workflow in scrappbook repo
every time heroku backend tests pass on master run "Tests" workflow in scrappbook-gallerys repo
once heroku backend successfully deployed move SBK-222 to QA

Services - place to perform tasks, place where an event can happen
Event:
service
payload

Task:
service
arguments

Task:
verb - "create", "move"
subject - "pr", "task"

Extract tasks and tasks order and time markers
For each task:
Determine service: must have service verbs, 

move [jira task] <task_number> to <column> [in <project_name> [project]]
move (?:jira task )?([a-zA-Z\-0-9]+) to ([a-zA-Z\-]+)

