---
layout: home
title: Home
nav_exclude: false
nav_order: 1
permalink: /:path/
seo:
  type: Course
  name: Stanford CS 324
---

# CS 324 - Advances in Foundation Models

## Overview

Foundation models (FMs) are models (e.g., DALL-E, GPT-3, Stable Diffusion) that are trained on large amounts of broad data and are adaptable to a wide range of downstream tasks. They form the basis of all state-of-the-art systems across a wide range of tasks and have shown impressive generative and few-shot learning abilities. In this course, students will learn the fundamentals about the modeling, systems and ethical aspects of foundation models, as well as gain hands-on experience working with them. In addition, the course will feature speakers from industry working on these FMs. The key deliverable will be a quarter-long project through which students will design their own FM-based research project or application, targeting a problem they care about. 

---

## Teaching Team  
{% assign instructors = site.staffers | sort: 'index' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

---

## Logistics

**Where**: Virtual (Lectures and Speakers via Zoom), In-Person Office Hours

**When**: Mondays and Wednesdays, 3:30-4:20pm PST.  

**Format**: Classes are a mix of **lectures by course instructors** and **talks + Q&As with guest speakers**. Coursework is a combination of 1 *early assignment* and 1 *quarter-long project*, both focused on working directly and getting hands-on experience with existing foundation models.   
- For more details, please see the [Class](#class) and [Coursework](#coursework) sections below. These will be updated shortly with additional information.
- Speakers will be hosted by [MLSys Seminar](http://mlsys.stanford.edu). Students will be required to watch the seminar. 

---

## Class 
This year, CS 324 classes are roughly divided into two halves of the quarter:  
1. **Weeks 1 - 4**: In the first half, we'll cover the fundamentals and "need-to-know" of foundation models, and provide a general survey of the field. A complete list of topics and related readings can be found [here](https://stanford-cs324.github.io/winter2023/syllabus/). The primary format will be lectures taught by course instructors.
 
2. **Weeks 5 - 10**: In the second half, we'll hear from guest speakers representing a diverse set of experiences building, using, and deploying foundation models in industry and academia for various use-cases and settings. Each class will feature a talk by one guest speaker, followed by a private Q&A.

An updating schedule of individual classes and topics can be found on the [Calendar](https://stanford-cs324.github.io/winter2023/calendar/) page (currently up to Week 5).

---

## Coursework
Grading will be based on three activities:  
1. Early assignment (20%) 
2. Quarter-long project (75%)  
3. Class attendance and participation (5%)

### 1. Early assignment
Both the [early assignment](https://stanford-cs324.github.io/winter2023/assignment/) and the [quarter-long project](https://stanford-cs324.github.io/winter2023/project/) are designed to get you hands-on experience with foundation models. 

To get you started, the **early assignment** will involve interacting with models like GPT-3 and CLIP to solve a couple simple tasks. You'll walk through the process of prompting these models with instructions and examples, and test these models' capabilities to automate various workflows with zero-shot and few-shot learning. 

More information will shortly be available [here](https://stanford-cs324.github.io/winter2023/assignment/). 


### 2. Quarter-long project
The main deliverable of the course is a quarter-long project, designed to give you the open-ended opportunity to either: 
1. **[Build an FM-powered application or demo]()**. Using foundation models and zero-shot and/or few-shot techniques, we're excited to see you build an app that solves a problem or automates a workflow of your choosing. This could involve a creative use-case of existing models and prompting strategies, or the application of your own FM-based method / technique.  

2. **[Conduct a research project]()**. If you're interested in diving deeper into the research side of foundation models, we encourage you to conduct a research project of your own design. This could be a study of a particular FM's properties, an evaluation comparing multiple FMs, or a proposal and implementation for generally improving an existing FM-based method / technique. 

### Project logistics  
Both project formats may be done in **teams of 1-3 students**.

We will have **two milestones** to help organize your progress: (1) an initial proposal, and (2) a final submission. Dates for these milestones will be announced shortly.   
1. The **[initial proposal]()** should outline the application or research problem you're interested in, and the approach you plan to take. It should include a brief description of the FM(s) you plan to use, and a list of potential evaluation metrics.  

2. The **[final submission]()** will involve writing and coding components for both project formats. More details will be announced shortly, but expect:
- **Application / demo** submissions to include a working demo of your application (e.g., as a [Gradio](https://gradio.app/) or [Streamlit](https://streamlit.io/) web app), along with a shorter write-up describing and motivating the problem you're solving, the FM(s) you used, and how you built and evaluated your application.  
- **Research project** submissions to include a final report in the style of a research paper. This should describe and motivate your research problem, the related work, your proposed methods, and the results of your evaluation. 

More information will shortly be available [here](https://stanford-cs324.github.io/winter2023/projected/). We will also update the page with a list of potential project ideas and resources.

### 3. Class attendance and participation 
Starting in Week 3 (1/25/2023), classes will feature guest speakers and the opportunity to ask questions in **follow-up Q&As**. We encourage you to be active during these sessions. To help prepare, as the quarter progress, additional information about upcoming speakers and relevant readings will be added to the [Calendar](https://stanford-cs324.github.io/winter2023/calendar/) page. These will be updated at least three days in advance of each class; we encourage you to read the relevant materials ahead of time.

Daily class attendance will be recorded using the following [Google Form](https://forms.gle/CgdW2kxRgBFRpScr9)

Attendance should recorded by EOD for every Monday/Wednesday class.
