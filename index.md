## Overview
This workshop is meant to be a platform of exchange between the three communities of computer vision, machine learning, and robotics. We want encourage them to find feasible solutions that bridge the gap between stand-alone  perception and robotic related tasks such as motion or assembly planning, visual servoing  and grasping. A main topic is how sensing, manipulation and planning  can be combined to yield mutual benefits. We also search for scalable  learning-based approaches that require little supervision and examine them on their benefits and limitations. This can include learning in simulation, transfer and few-shot learning, automatic labeling or reinforcement learning. Are end-to-end learning  approaches really the right way to go or are modular pipelines still preferable due to better introspection? Are current subtask metrics suitable indicators for execution success? What is necessary to address the  needs of end-user applications in terms of scalability, robustness, runtime, cost,  maintainability and fail-safety? 

---

## Invited Speakers
* [__Maxim Likhachev__](http://www.cs.cmu.edu/~maxim/), Robotics Institute Carnegie Mellon University
  <details>
    <summary>Offline Learning for Online Planning</summary>
  
    In manufacturing and automation settings, robots often have to perform complex yet repetitive manipulation tasks. Furthermore, in many cases, for example, a robot operating at a moving conveyor, robots have very limited time to decide what action to execute next and how to do it, independently of the complexity of a planning problem. In this talk, I will describe some of our research efforts towards the use of offline learning to ensure that online planning is fast and robust enough for such problems. Specifically, in the first part of the talk, I will present an offline pre-processing method that provides a provably constant-time online planning for repetitive planning tasks in static environments. In the second part of the talk, I will describe our approach to learning from offline simulation-based planning for online decision-making under significant uncertainty in the model and environment. I will use mobile manipulation tasks to illustrate the described approaches.
    
  </details>

* [__Renaud Detry__](https://www-robotics.jpl.nasa.gov/people/Renaud_Detry/), NASA JPL
  <details>
    <summary> Combining Semantic and Geometric Scene Understanding: From Robot Manipulation to Planetary Exploration </summary>
  </details>
* [__Sergey Levin__](https://people.eecs.berkeley.edu/~svlevine/), UC Berkeley, EECS
  <details>
    <summary>Data-Driven Robotic Reinforcement Learning</summary>
  
  The ability of machine learning systems to generalize to new situations is determined in large part by the availability of large and diverse training sets. In robotics, it is often thought that large datasets are difficult to obtain, and therefore we need alternative methods that can handle small datasets. In this talk, I will discuss how in fact robots should be better suited for large-data training regimes than supervised learning systems, since they do not require humans to manually provide labels for the data. I will discuss how effective robotic learning requires removing the barriers to data-driven improvement from every part of the learning pipeline, from task specification, to data collection, to off-policy reinforcement learning, and present initial results that study each of these problems.
  </details>
* [__Leonel Rozo__](http://leonelrozo.weebly.com/), Bosch Center for Artificial Intelligence
  <details>
    <summary>Exploiting Geometric and Temporal Structure in Object-centric Skills Learning</summary>
  </details>
  
* [__Gilwoo Lee__](https://gilwoolee.github.io/), School of Computer Science & Engineering at the University of Washington
  
* [__Dieter Fox__](https://homes.cs.washington.edu/~fox/), University of Washington, as well as NVIDIA AI Robotics Research Lab

---

## Call for Papers
We solicit __2-4 page extended abstracts__ (following RSS style guidelines). The submissions can include: __late-breaking results__, __under review material__, or __archived__. We strongly encourage the preparation of __live demos__ or __videos__ accompanying the submission.

* Reducing the setup time through automatized training procedures
  * What do we gain / sacrifice with the current methods that require less supervision?
  * Transfer learning, learning in simulation, automatic labeling, reinforcement learning
* How can the interaction between sensing, manipulation and planning yield mutual benefits?
  * e.g. Extracting semantic information from visual/tactile data for improved execution planning
* Scalable approaches for grasping novel objects and for generalizing functional grasps
* As end-to-end approaches gain traction, which benefits and limitations do they possess compared to modular pipelines?
  * How can we achieve introspection in end-to-end methods?
  * Are commonly used subtask metrics in modular approaches suitable indicators for execution success?
* Which possibilities for automatic recovery exist to create failure proof systems?
* Addressing the needs of end-user applications in terms of robustness, runtime, cost, maintainability, etc.

Submitted papers will be reviewed by the organizers and invited reviewers. Accepted contributions will be presented as posters or within the Demo/Video Talk format. Selected papers are further featured as spotlight talks. All accepted contributions and posters will be posted on the workshop website upon author approval.

Submission is now open on EasyChair [__SLIPP-2019RSS__](https://easychair.org/my/conference?conf=slipp2019rss), please take note on the submission [__deadline__](https://scalableroboticlearning.github.io/#important-dates).

---

## Schedule

| Time  | Topic |
| :------------- | :------------- |
| __8:00 - 9:00__ | __On-site Registration__ |
| __9:00 - 9:10__ | __Introductory Remarks__ |
| __9:10 - 9:50__ | __Invited Talk__: Maxim Likhachev <br> *Offline Learning for Online Planning*|
| __9:50 - 10:30__ | __Invited talk__: Renaud Detry |
| __10:30 - 10:45__ | __Poster Spotlights__ |
| __10:45 - 11:30__ | __Coffee Break + Posters__ |
| __11:40 - 12:20__ | __Invited Talk__: Sergey Levine <br> *Data-Driven Robotic Reinforcement Learning*|
| __12:20 - 1:00__ | __Invited Talk__: Leonel Rozo <br> *Exploiting Geometric and Temporal Structure in Object-centric Skills Learning*|
| __1:00 - 1:45__ | __Lunch Break__ |
| __1:50 - 2:30__ | __Invited Talk__: Gilwoo Lee |
| __2:30 - 3:15__ | __Coffee Break + Posters__ |
| __3:20 - 4:00__ | __Invited Talk__: Dieter Fox |
| __4:00 - 4:20__ | __Demo/Video Talks__ |
| __4:20 - 4:40__ | __Discussion with participation of the audience and experts__ |

---

## IMPORTANT DATES

| Timeline |  |
| :------------- | :------------- |
| June 7, 2019 (23:59  Pacific Time) | Paper Submission Deadline |
| June 14, 2019 (23:59 Pacific Time) | Paper Acceptance Notification |
| June 22, 2019 (Saturday) | Workshop <br> __WS1-2__ Scalable Learning for Integrated Perception and Planning <br> 	[Faculty of Engineering](https://goo.gl/maps/2iwdEFKUh1m), Building [82](http://www.roboticsconference.org/docs/workshops.pdf), Room [00 006](http://www.roboticsconference.org/program/workshops/bd82/)

---

## Contact

Should you have any questions, please __do not hesitate to contact the organizing committee__ at <scalableroboticlearning@dlr.de>:
* Maximilian Durner
* Martin Sundermeyer
* Zoltan Marton
* En Yen Puang
* Rudolph Triebel
