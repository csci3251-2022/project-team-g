This area of content is not part of the Task 3, Delete at the final stage
```
# This team hasn't started yet...

1. All team members must tag their **pull requests** under **Project tag**, and **add their "hello" card**
2. All team members must also tag their **issues** under **Project tag**

**Please read `tasks.md` to start your work.**

# Current Progress 
Completed:
Task1
Task2
Task3
Task4
Task5
Task6
Task7
```

# Introduction

This is Team G, and we are performing the project milestone 3 of CSCI3251. In this project, we will follow the task indicated in the `issues` folder, like write a C code to print the message everytime there is a merge action, get a status badge, showcase our team and register our repo. Hope that we will familiar with the Github feature for team works.

# Code

```c
// Write some code here
{% include_relative code.c %}
```
![example workflow](https://github.com/csci3251-2022/project-team-g/actions/workflows/c-cpp.yml/badge.svg)

# Contributor

| Github Name | Student Name | Student ID | Contribute of Work |
| --- | --- | --- | --- |
| [EJ-L](https://github.com/EJ-L) | Eric John LI | 1155159116 | Task 1 |
| [SteveNoobPlus](https://github.com/SteveNoobPlus) | Yu-Shing CHENG | 1155158488 | Task 2 |
| [JasonWongin](https://github.com/JasonWongin) | Lap-Yin WONG | 1155147798 | Task 3 |
| [marcoao2001](https://github.com/marcoao2001) | Chon-Long AO | 1155135754 | Task 4 |
| [NovaTse](https://github.com/NovaTse) | Ka-Hei TSE | 1155159810 | Task 5 |
| [Jimmy-Li9912](https://github.com/Jimmy-Li9912) | LI Jingchen | 1155124512 | Task 6 |

{% for s in site.stu %}
<div>&emsp;&raquo;<img src="{{s.image}}" />@{{ s.user }} ({{ s.name }})</div>
<div>&emsp;&emsp;&raquo;{{ s.content | remove: '<p>' | remove: '</p>' }}</div>
<br>
{% endfor %}

Last modify: {% site.time %}
