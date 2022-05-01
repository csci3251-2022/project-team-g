# Introduction

This is Team G, and we are performing the project milestone 3 of CSCI3251. In this project, we will follow the task indicated in the `issues` folder, like write a C code to print the message everytime there is a merge action, get a status badge, showcase our team and register our repo. Hope that we will familiar with the Github feature for team works.

# Code

```c
// Write some code here
{% include_relative code.c %}
```
![example workflow](https://github.com/csci3251-2022/project-team-g/actions/workflows/c-cpp.yml/badge.svg)

# Contributor

{% for student in site.stu %}
<div>{{ student }}</div>
{% endfor %}

{{ site.description }}
