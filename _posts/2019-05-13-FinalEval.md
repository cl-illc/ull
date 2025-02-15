---
layout: post
title: Evaluation of the Final Project
date:   2019-05-13
author: Samira
categories: Info
mathjax: true
---
  
### In the final project you are expected to:
* Have a well formed research question 
* Design experiments to address the research question
* Correctly implement the models and obtain plausible results
* Perform adequate analysis to explain your results (whether you get positive or negative results!)
* Make a poster and present your project to the class -- **Deadline: 22 May 11:00, Poster presentation session**. The poster presentation is worth 10% of your course grade.
* Write a research report describing your research question, methods, experiments and main findings (5-7 pages) -- **Deadline: 3 June, 23:59**. The research report is worth 40% of your course grade.

Please note that we will not penalise you if you do not get a positive result. This is research and we know that a negative result is always a possibility. What we want to see is that you have conducted experiments following good scientific practice (as described in the project advice slides), and that you have analysed your results and provided some insight about the behaviour of the models.

### Poster instructions

The goal of the poster session is to present your project to us and your classmates, discuss it and get feedback and ideas. We recommend the following structure: 

* Introduce the problem area and the task, and clearly state your specific research question(s) and their novelty.
* Describe the models / architectures that you have developed in the project, in a way that they are clear to your classmates. 
* Describe the experiments: how did you train and evaluate you models (include information about datasets, training procedure and baselines).
* Present your results and main findings.
* Finish off by analysis and conclusions: what are the most important things you have learnt from your experiments?
 
Keep in mind that a poster presentation is not just about the content of your project: The organisation of your poster and the oral presentation count as well.
* You should organise your poster in a structured way such that the reader can understand the your work within a few minutes.
* Provide easy to understand visual aids that support the information described in the text and are appealing for the reader.
* Prepare a speech of a few minutes ("elevator pitch") summarising the highlights of your research. Use your poster in your speech, while keeping eye-contact with your audience. Ensure that your speech is understable for fellow students.

### Report instructions

Your report needs to be written in LaTeX. You are required to use the ACL 2018 template [(zip)](https://acl2018.org/downloads/acl18-latex.zip) which you can edit directly on [Overleaf](https://www.overleaf.com/latex/templates/instructions-for-acl-2018-proceedings/xzmhqgnmkppc). Make sure your names and student numbers are visible at the top. (Tip: you need to uncomment `/aclfinalcopy`).
You can find some general tips about writing a research paper [here](https://www.microsoft.com/en-us/research/academic-program/write-great-research-paper/), but note that you need to make your own judgment about what is appropriate for this project. 

We expect you to use the following structure:
* **Introduction** (~1 page, 1 point) - describe the problem, your research questions and goals, a summary of your findings and contributions. Please cite related work (models, datasets) as part of your introduction:
  * Introduce the task and the main goal
  * Clear research question
  * Motivating the importance of the question and explaining the expectations
  * How are these addressed or not addressed in the literature
  * What is your approach and its novelty
  * Short summary of your findings (Did you get the results you were expecting, what should one learn from your experiments and results?)
* **Related work** (~ 1 page, 1 point) - describe the existing research related to your research problem / question. Include a brief summary of the proposed methods and the key findings of the previous research.
* **Methods** (~1-2 pages, 2 points) - cover the main techniques ("building blocks") used in your project and intuitions behind them. Be accurate and concise.
  * How each technique that you use works (don't just copy the formulas)
  * The relation between the techniques
  * The architecture of the final models (what layers you have, how do you do the task? how you encode the input and output? What is your loss function? Here you should provide enough information for someone want to implement you models.)
* **Experiments** (~1/2 - 1 page, 1 point) - Describe your experimental setup. The information here should allow someone else to exactly re-create your experiments. Describe how you evaluate the models.
  * Explain the task and the data
  * Training the models (model, data, parameters and hyper parameters if the models, training algorithms, what supervision signals you use, etc.)
  * Evaluation (e.g. metrics)
* **Results and Analysis** (~1 page, 4 points). Go over the results and analyse your findings.
  * Answer each of the research questions you raised in the introduction.
  * Plots and figures highlighting interesting patterns
  E.g. What are the factors that makes model A better than model B in task C? investigate to prove their effect!
* **Conclusion** (~1/4 page, 1 point). The main conclusions of your experiments.
  * What have you learned from you experiments? how does it relate to what is already known in the literature? 
  * Where the results as expected? any surprising results? why?
  * Based on what you learned what would you suggest to do next?

You lose points for bad writing style (because you were asked to prepare a conference-style report).

#### Writing style
* did not make proper use of the latex template (e.g. tweaked the template): -0.5
* did not respect the page limit: 1 column is tolerated, beyond that it’s -0.5 for the first page, we stop reading beyond that (which will affect your grade for other criteria as well).
* bad structure (e.g. missing important sections such as introduction and conclusion): -0.5 per section.
* command of English: judged case by case

#### General Tips:
* Math notation – define each variable (either in running text, or in a pseudo-legenda after or before the equation)
* Define technical terminology you need
* Avoid colloquial language – everything can be said in a scientific-sounding way
* Avoid lengthy sentences, stay to the point!
* Do not spend space on "obvious" things! 

#### An ideal report:
* Precise, scientific-sounding, technical, to the point
* Not boring – because you don’t explain obvious things too much
* Efficient delivery of (only) the facts that we need to know to understand/reimplement
* Results visually well-presented and described with the correct priority of importance of sub-results
* Insightful analysis – speculation should connect to something interesting and not be too much; the reader "learns something new"
* No typos, no colloquialisms – well-considered language
* This normally means several re-draftings (re-orderings of information)
* Avoid general ungrounded claims. Base your claims either on the literature or your own experiments.

### Report submission

Report submission will be via Canvas. Please submit the PDF of your report, as well as a breakdown of contributions by team member. Clearly state what each team member has contributed to the project (e.g. which components they have implemented, how they have contributed to the analysis, which section(s) of the report they have written).

The deadline for the submission of the report is **3 June, 23:59**.
