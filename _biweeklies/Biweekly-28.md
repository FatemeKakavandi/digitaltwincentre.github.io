---
layout: default
title: Biweekly 28
date: 10 November 2020, 1400 CEST
---

<script src="https://code.jquery.com/jquery-1.11.1.min.js">
</script>
<script src="/javascripts/edit.js"></script>
<script>setEditButonNm();</script>

# {{ page.title }}

|||
|---|---|
| Date | 10 November 2020, 14:00 CEST |


## Pre-meeting stakeholders' reports

<!-- Please keep in mind that the minutes are publicly available.-->

#### Peter Gorm Larsen
* Met with Poul Toft from the PDJ Foundation last week
* Together with Lukas selected the post-doc candidate to work in the UPSIM project (start early 2021)
* Announced the webinar at the end of November (see https://into-cps.org/events/show/artikel/into-cps-webinar-1/)
* Read and made edits to the technical report that Hao has produced for the incubator case study
* Read and made minor adjustments to the Isola paper driven by Carl and Beidi for buiulding digital twins
* Completed review of digital twin paper related to safety-critical systems
* Prepared interview with Ole Green

#### Nick Battle
* Skype with Jonas/Frederik about the best way to enable the Combinatorial Testing UI feature
* Implemented the basic protocol for the above - list traces, generate tests, execute tests.
* Implement cancellable operations and intermediate result notifications for better UI interaction.
* Look at some VDMJ/Overture issues for Leo
* Re-structured VDMJ (suite) Maven POMs to allow direct release to Aarhus ArtiFactory repository (for Maestro)
* Released VDM 4.3.0 to ArtiFactory, with help from Casper
* Started work on "runtrace" command to allow "Send to Debugger" CT functionality

#### Hugo Daniel Macedo
* Sorted issues Leo found on running External Tools with Overture
* Started testing MaestroV2 inside the INTO-CPS App
* Helped a student from Newcastle troubleshooting the INTO-CPS app
* Worked with Gita on scenario generation
* Discussing with Till on Digital Twins for Manufacturing Survey

#### Claudio Gomes
* Helped Hao finalize his tecnical report on the incubator case study.
* Clarified semantics of synchronous clocks for the FMI standard
* Helped Simon finalize his UPPAAL interpreter for co-simulation algorthms with step rejection and algebraic loop solving.
* Met with Fateme, Peter, and Novo Nordisk on Fateme's phd project.
* Facing some challenges with symbolic manipulation of UR robot newton-euler equations.
* Prepare simple continuous model of steam boiler for Bachelor course.

#### Casper THule
* Released Maestro2
* WOrking on typechecker for Maestro2
* Fixed issue in classmapper usage of VDMJ
* Assisted Nick with maven related stuff
* Wondering about basing a plugin entirely on Prolog
* Fixed issue in RabbitMQ FMU
* Discussed RabbitMQ Future with Gita
* Maestro2 plan: Support legacy features followed by focus on digital twins.
* Discussed FMI2 interface functionality with Christian

#### Prasad Talasila
* Work with ULBS, Romania researchers to create co-simulation of AgroIntelli's Robotti manufacturing line.

#### Christian Møldrup Legaard

* Using the lessons learned from PyFMU, i am finishing implementation of a generic version.
 - based on a message queue zmq
 - supports distribution / remote execution

#### Emil Madsen
* AU DTL-Skjern:
- Last week: Met Charles Møller at AAU to see Festo industry 4.0 production equipment.
- Investigated possible Festo Didactic equipment and 3D printers.
- Wrote Festo Didactic.
- This week: Meet Christian Schlette at SDU to see robotic systems.
* Identified error in converting linear robot dynamics to linear AND minimal robot dynamics
To-do / upcoming:
* Webinar presentation on November 25 on robot dynamics calibration 

```toml
[command]
windows = [ "python", "launch.py" ]
linux = [ "python3.8-dbg", "launch.py" ]
macos = ["python3.8","launch.py"]

[timeout]
launch = 500
command = 500
```


## Sub-projects status


#### Sub-project X

#### Sub-project Y

#### Sub-project Z

##  Any Other Business

Next Meeting
------------

24 November 2020, 14:00 CEST


<div id="edit_page_div"></div>
