# FVTodo #

## Description ##

This is an electronic implementation of [Mark Forster's](http://markforster.net) Final Version
time management system. See his site for details of how this system. As a foretaste, I will 
summarize how it works here.

1. First, all tasks entered one after another on a never-ending list.
2. Determining what to action in a session preselects of chain of actions based on the
question "What do I want to do before I do x?"
3. The chain always starts with the first unactioned task on the never-ending list.
4. This task then becomes the benchmark from which the next task is selected. The question
becomes "What do I want to do before I do that task?"
5. You iteratively proceed through the list, picking tasks you would rather do, and making
that task the benchmark for the next iteration.
6. Continue until you reach the end of the list.
7. This preselected list becomes a locked todo list to be done in reverse order.
8. If you don't finish a particular task, re-enter the task at the end of the list.
9. Once you have taken action on all the preselected tasks, preselect another chain of tasks
starting again from the first unactioned task on the list.
10. If the first task on the list can't be done now for some valid reason (e.g. wrong time of day, precondition not met, bad weather), then cross it out and re-enter it at the end of the list. Use the next task as your starting benchmark.
11. If at any stage you find that a task on the list is no longer relevant, then delete it.
12. If you find that your preselected list is no longer relevant (e.g. if you have had a long break away from the list), then scrap the preselection and reselect from the beginning.
13. If one or more very urgent things come up, write them at the end of the list and mark them with a dot so that they are done next. If something already on the list becomes very urgent, then move it to the end of the list and mark it with a dot in the same way.

## To Be Added ## 

* How to run projects
-- consider letting there be subdivisions included in the list or not, that are associated as steps of another step.

* Someday/Maybe

* How will I collect data to determine how one is proceeding, some items that have crossed my mind:

1. list growth to processing (biting off more than one can chew)
2. Time spent on given tasks/projects
3. Number of times a task is re-visited.
4. Statistics on when preselections get abandoned (daily biting off more than one can chew).

* Offline option, using HTML5 storage.
* Detailed notes to be associated with each task
* Export to xml and json