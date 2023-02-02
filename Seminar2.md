# Second seminar. Branches.

## Branch creating.

* *git checkout branch_name* - команда, осуществляющая переход на ветку *branch_name*;

* *git branch* - команда, отображающая список существующих веток и отмечает в нем текущую;

* *git branch_name* - команда, инициализирующая ветку с именем *branch_name*;

## Branch merging.

*git merge branch_name* - команда, сливающая текущую ветку, с веткой *branch_name*;

*git branch -d branch_name* - команда, удаляющая ветку *branch_name*;

## Conflicts.

Конфликты возникают: при наличии в сливаемых ветках коммитов, претендующих на общее рабочее пространство;

## Commit log graph.
*git log --graph* - опция --graph выведет график отражающий структуру ветвления истории коммитов;

*git log --graph* - просмотр истории комитов для текущей ветки в виде графика;
*git log --all --graph* - просмотр истории комитов по всем веткам; 

## Show commit.
*git show hash_commit* - просмотр полного списка изменений, внесенных конкретным комитом;

## Rolling back a commit.

*git revert* - отменяет изменения, записанные только одним коммитом;