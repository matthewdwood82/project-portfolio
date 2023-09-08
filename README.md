# Project Portfolio

This repo holds artifacts from a collection of recent projects. The descriptions below give a high level overview of the project and my role, and a brief description of the contents of each file from the project. A collection of these and other papers and reports can be found in [this Zotero library](https://www.zotero.org/groups/2420929/selected_works).

For a more comprehensive list of project artifacts, see my [Google Scholar profile](https://scholar.google.com/citations?user=XI2vZ6MAAAAJ&hl=en).

Please reach out to [matthewdwood82@gmail.com](matthewdwood82@gmail.com) with any questions or requests.

## DARPA ASIST
### Project Description
The DARPA Artificial Social Intelligence for Successful Teams (ASIST) Program aspired to develop Artificial Intelligence that could learn the shared mental models (SMM) of human teammates, and use theory of mind (ToM) to project the actions of those teammates. AI developers (TA1) produced and trained agents with an ability to learn SMM and apply ToM. Social scientists (TA2) performed research on the mechanisms that AI agents might employ to promote interaction with human teammates, and also developed measures which could be used in production to improve the quality of TA1 agent sensing and interactions. A Test and Evaluation (TA3) team from Aptima, with Arizona State University and the Center for Open Science, developed experiments to test the quality of TA1 agents and the veracity of TA2 theories. 


### Role
I served as lead for implementing evaluation measures and Project Manager for the TA3 team. In the evaluation measure role, I developed a reproducible research pipeline that produced an webpage that TA1 performers could use to see the performance of their agents during TA3 experiments, and provided a model for how TA2 researchers should be developing their analyses in support of their theories. This webpage provided summary tables and visualizations to provide an easy-to-interpret and brief description of both human and AI performance in these studies. As Project Manager, I developed and updated budgets for Aptima and subcontractors in response to changes in program demands and budget in coordination with almost 50 staff members across the three organizations. 


### More Information
A paper with measure summaries and visualizations I developed for the second of three TA3 studies for which I was involved can be found in the conference paper below.
* Freeman, J., Huang, L., Wood, M., & Cauffman, S. (2021, November). [Evaluating Artificial Social Intelligence in an Urban Search and Rescue Task Environment](https://github.com/matthewdwood82/project-portfolio/tree/main/darpa_asist). _Paper presented at AAAI Fall Symposium Series on Computational Theory of Mind for Human-Machine Teams_, Virtual. 


## ARI Skill Retention
### Project Description
Trainer’s Decision Aid is a paper-and-pencil job assessment designed to help military leaders assess individual task demands, work context, and external factors that make skills more difficult to retain in order to identify cognitive interventions (e.g., training, memory aids) to improve retention and enhance performance. Aptima was tasked with calibrating the assessment, and putting it into an electronic format so it is easier for military leaders to use, track results, and perform what-if analysis. The Trainer's Decision Aid - Electronic Scoring Tool (TDA-EST) was developed through a combination of expert elicitation to understand needs of military leaders (specifically combat first aid trainers), empirical collection of training classes to assess retention in the domain, and software engineering and interface design to develop the lightweight TDA-EST.  

### Role
I served as the Principal Investigator and Project Manager for the project. As Principal Investigator, I led the technical vision and execution of the project including expert elicitation, statistical analysis, and software development. As Project Manager, I developed budgets and ensured timely delivery of project reports and other status updates. In both roles, I led a team of four staff and one consultant in technical and programmatic execution. I coordinated data collection with the customer and partners, and pivoted the statistical analysis and software development approach when it was clear that COVID-19 was going to disrupt data collection efforts in a way that would make it difficult to calibrate the software decision tool using data by the end of the period of performance. Instead, we developed an approach where the user or follow-on investigators could update model weights and scoring mechanisms with future expert elicitation or data and easily update the software. 

### More Information
A high level overview of the project is contained in these slides developed for a job talk.
* Wood, M. D. (2021). [Refining a Tool to Measure Individual and Collective Skill Retention](https://github.com/matthewdwood82/project-portfolio/blob/main/ari_skill_retention/2021.01.08%20TDA%20JOB%20TALK%20MDW.pptx). Job talk. 

Major deliverables of the project included a decision support software tool written in VBA and Excel, and a User's Guide that walks through the tool and illustrates its major features. The User's Guide is provided below, which includes a walkthrough of the tool as well as a brief description of some of the expert elicitations used to inform its design.
* Wood, M. D., Kay, K., Reynolds, K., Leins, D. A., Flanagan, S., & Vowels, C. L. (2021). [Updates to the Trainers Decision Aid: Developing the Electronic Scoring Tool](https://github.com/matthewdwood82/project-portfolio/blob/main/ari_skill_retention/Wood%20et%20al.%20-%20Updates%20to%20the%20Trainer%E2%80%99s%20Decision%20Aid%20Developing%20.pdf). Research Product developed for U.S. Army Research Institute for the Behavioral and Social Sciences. 


## Houston Ship Channel
### Project Description
The Houston Ship Channel (HSC) is one of the busiest waterway corridors in the United States. Since the channel’s expansion in 2005 and to the time of the project in 2015, concerns were rising about design deficiencies in the HSC in the area of the Bayport Ship Channel (BSC), especially north of the turn at Five Mile Cut. The project conducted a mental models expert elicitation exercise to identify safety concerns arising from these design deficiencies, and provide qualitative information to structure analysis of techical data to better connect possible design deficiencies to incident outcomes. The elicitation produced an influence diagram to enable later causal reasoning for this reach of the HSC and nearby areas, and helped prime a comprehensive study of the feasibility of safety and performance modifications.

### Role
I was responsible for developing and executing the elicitation, and worked with the project lead to synthesize findings and report results.

### More Information
A paper summarizing the approach and results is here.
* Wood, M. D., Collier, Z. A., Bridges, T. S., & Russo, E. J. (2018). [Mental Models of Navigation Safety to Inform Risk Management Decisions: Case Study on the Houston Ship Channel](https://github.com/matthewdwood82/project-portfolio/tree/main/houston_ship_channel). _ASCE-ASME Journal of Risk and Uncertainty in Engineering Systems, Part A: Civil Engineering, 4_(3), 05018001. https://doi.org/10.1061/AJRUA6.0000963


# Code Portfolio

## LTS Bowl Transactions
Used Github Actions to pull transaction data (trades, waivers, etc.) for a fantasy football redraft league-of-leagues and publish to a Quarto Page. Built in R using [`{ffscrapr}`](https://ffscrapr.ffverse.com/), [`{quarto}`](https://quarto.org/), and the [`{tidyverse}`](https://www.tidyverse.org/). Done with help of [Tan Ho's](https://tanho.ca/) excellent [`rstudio::conf(2022)` talk](https://github.com/tanho63/project_immortality) on Github Actions, and mentorship from the [R4DS Online Learning Community](https://www.rfordatasci.com/). Code available on [GitHub](https://github.com/matthewdwood82/LTS-Bowl-2023), site on [Github Pages](https://matthewdwood82.github.io/LTS-Bowl-2023/).


## Babynames app - wip
Webapp written in [`{golem}`](https://engineering-shiny.org/index.html) and intended to visualize data from the Social Security Administration's [Popular Baby Names](https://www.ssa.gov/oact/babynames/limits.html) data. Includes and extends data from the [`{babynames}`](https://github.com/hadley/babynames) dataset. 

Almost-working code available on [Github](https://github.com/matthewdwood82/babynamesapp).


## narratetheshowR - wip
The stub of an idea for a package to help NFL researchers test hypotheses related to "the shower narrative," or the idea that teammates who spent time together on another team earlier in their career will produce chemistry that results in improved on-field coordination and therefore performance. Actively looking for collaborators, longer description available on [Github](https://github.com/matthewdwood82/narratetheshoweR/blob/main/README.md). 
