---
layout: default
title: Additional Resources
permalink: /extras
nav_order: 4
---
# Additional Resources

Contributors: {% git_author %}

To help make this guide as complete and comprehensive as possible for all things planning, below you can find a wide variety of additional resources to help with your PDDL and planning ambitions. 

For inclusion in this additional resources section please [file an issue](https://github.com/nergmada/pddl-reference/issues/new/choose) detailing the resource you believe should be added. Please mark this issue as new content. 

- [Planning.Domains](#planning.domains)
- Planner Tools
- PDDL Tools
- Learning Resources

## [Planning.Domains](http://planning.domains/)
[Planning.Domains](http://planning.domains/) is the definitive home of Artificial Intelligence Planning. The sit features a wide variety of tools and resources to help you with AI Planning. Included in its toolset is a Planning as a Service (PaaS) API. An online editor for writing and testing domains and problem files.

It also links to education resources, and provides links to institutions that are key players in the field of AI Planning research.

## Planner Tools

### [VAL - The Plan Validator](https://nms.kcl.ac.uk/planning/software/val.html)
[VAL](https://nms.kcl.ac.uk/planning/software/val.html), also known as Validator, is a tool for validating the solutions produced by a planner against the original domain and problem file. VAL allows you to check that the plan actually achieves the goal whilst adhering to all the preconditions it needs to when applying actions.

### [Eviscerator - The Planner tester](https://www.github.com/nergmada/eviscerator)
[Eviscerator](https://www.github.com/nergmada/eviscerator) is a tool developed for this PDDL Reference guide that allows us to automatically test and identify what PDDL requirements a planner supports. It is an open source tool, which comes with a Continuously Deployed Pre-built binary for Linux. This means you can download it and test a planner without worrying about compilation. 

### [ROSPlan - Planning in ROS](https://github.com/KCL-Planning/ROSPlan/)
[ROSPlan](https://github.com/KCL-Planning/ROSPlan/) is a module for the Robotic Operating System (ROS) that allows for the integration of AI Planning into Robots that make use of ROS. ROSPlan allows for modelling of Robotic environments for the purpose of planning and executing tasks.

### [Plansys2 - Planning in ROS2](https://github.com/IntelligentRoboticsLabs/ros2_planning_system)
[Plansys2](https://github.com/IntelligentRoboticsLabs/ros2_planning_system) is a project for the new version of Robotic Operating System, **ROS2**, that integrates Planning and Robotics. It aims to be a framework where different planners can be easily integrated to make robots perform tasks. Actions are implemented using [Behavior Trees](https://github.com/BehaviorTree/BehaviorTree.CPP), and there are a bunch of [examples](https://github.com/IntelligentRoboticsLabs/ros2_planning_system_examples/) in the repo.

### [Universal Planning Validator (Under Development)](https://github.com/aig-upf/universal-planning-validator)
[Universal Planning Validator (Under Development)](https://github.com/aig-upf/universal-planning-validator) is a tool designed to validate planning domain and problems. Currently it can only support classical planning problems and domains, but the tool is intended to be expanded to include temporal and multi-agent domains. If you require a Validator that supports more advanced PDDL features than classical planning, then try VAL, the Planning Validator instead.

## PDDL Tools
### Visual Studio Code + PDDL Plugin
[Visual Studio Code](https://code.visualstudio.com/) is a text editor developed by microsoft with a plethora of fantastic integrations. A fantastically helpful [PDDL plugin](https://marketplace.visualstudio.com/items?itemName=jan-dolejsi.pddl) allows for the development of PDDL with syntax highlighting and then in-editor execution of the domain and problem file on pre-installed planners.

## Learning Resources
### [Learn PDDL by Dr Fares K. Alaboud](https://fareskalaboud.github.io/LearnPDDL/)
[Learn PDDL](https://fareskalaboud.github.io/LearnPDDL/) is an introductory tutorial on PDDL which allows you to get to grips with the writing and developing of PDDL files. PDDL1.2 is introduced first using basic predicate logic before proceeding to make progressively more complex domains.

### Introduction to AI Planning
Dr Andrew and Amanda Coles introduce AI Planning in this fantastic two part YouTube video that gives a great immersive overview of AI Planning, its applications and its current areas of continuing interest.

- [Introduction to AI Planning. Part I. (video)](https://www.youtube.com/watch?v=EeQcCs9SnhU)
- [Introduction to AI Planning. Part II. (video)](https://www.youtube.com/watch?v=FS95UjrICy0)

## Publicly Available PDDL Domains
Below is a list of links to PDDL domains available publicly.
- [IPC PDDL Domains](https://github.com/potassco/pddl-instances)
