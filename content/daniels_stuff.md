---
title: "UBusiness Stuff"
author: "Daniel S. Hain"
date: "12/2/2019"
output: html_document
---

# MSc - Social Data Science Programme

* 6 months Master Specialization in applied Machine Learning and Ai
* For business and social science students
* 1st year 30 students, 2nd year 60 students - one of the largest master programmes at AAU SAMF
* Engineering approach to problem solving
    * Applied ML
    * Working with unstructured data (Networks & Natural-Language-Processing)
    * Deep Learning and AI
    * Company project

---


# Outline - Getting started with ML&AI in your company

* The process we’ve experienced in several companies and what it needs to get started
* Understanding the technology (Supervised and Unsupervised ML)
* Identify ML&AI usecases.
* Establishing a business case and ROIs
* Identifying key people and building a team
* Creating and sustaining data literacy across the organization


---

# How to start with AI! 

![](images/big_data.png)

---

# How to start with AI! - Not.

* Get an AI degree!
* Hire an AI wizard!
* Pick an awesome algorithm!
* Dive into the data!


---

# AI vs. ML

![](twitter_what_AI.png)

![](AI_ifelse.jpeg)

![](ai_mask.jpg)

---

# Defining some terms

* Algorithm: In plain: Input -> Mush -> Output
* ML: An algorithm which we do not tell how to mush, but it learns by examples
* AI: Algorithms, where the mushing produces outputs we consider intelligent.
* DS: Academic/Professional discipline dealing with establishing ML processes and communicating insights 

![](ML_AI_circle.png)

![](algo.png)


--- 

# AI hype & FOMO

* Emerging technology:  Everybody is excited, magical use-cases in the air.
* Overhype in news, science, business & technology reporting
* Lot of misinformation, eg. [MMC report](https://www.mmcventures.com/wp-content/uploads/2019/02/The-State-of-AI-2019-Divergence.pdf): 40% of EU AI startups don't use AI (EC report finds same in EU).
* Often simple/trivial use-cases mystified by tech-journalists by using obscure terms.

![](twitter_teenage.png)

![](twitter_stitchfix.png)

---

# Supervised vs. Unsupervised ML (Highlevel)

![](ml_types.png)

# Supervised ML: So, what is ML&AI? (in 95% of cases)

Thought Experiment: The AI island

* We have some 5k “friends” on a remote island that do tasks for us. They are specialized on labeling stuff.
* They speak a native language, so we can’t talk. We can only teach them by examples. When they look at enough, they eventually figure out how to label what.
* They make some mistakes, and need really a lot of examples to figure it out, but when they have, we can send them new stuff, and they label it for us.

What would you use our friends for?


---

# How to think "predictive"?

Some simple steps: 

1. Can we reframe the problem as a prediction task?
2. Is this task trivial and can be well designed by simple rules?
3. Do we have a reasonable amount of historical input-output data?
4. Is the outcome of interest well defined and measurable?
5. Is it reasonable to believe that the outcome of interest can be inferred from the input (signal/noise ratio)?
6. Is this data available in an accessible manner? Can input be mapped to the corresponding output? Is the input available at the point we need it? 
7. Can it be used to improve a well-defined metric of interest?


---


# Predictive Tasks: Examples

* Baby food ingredient: safe or spoiled?
* Patient: ideal medication dosage?
* Email: spam or ham?
* Patent: Breakthrough or worthless
* Start-up: Valuation
* Recorded phone call to call center: issue topic?
* Bottle of wine: will I like it or not?
* Start of a sentence: end of that sentence?
* Stock: tomorrow’s price?
* Transaction: legitimate or fraudulent?
* Data center cooling system: warmer or cooler?
* Machine: when will it need maintenance?
* Inventory: when to restock?


---

# Your turn: Spot prediction problems

Process

* Logistics?
* QM?
* Customer Care?

Product

* Toothbrush?
* Windmill?
* Running shoes?
* Kitchen stuff?


Service/Finance
* Dating?
* Insurance?
* Fund MAnagement

---

# Predictive Tasks: Industries & applications

![](industry_matrix.png)


---

# Unsupervised learning

Nothing to do with machines running around without adult supervision

![](cats_1.png)

---

# Unsupervised learning

Nothing to do with machines running around without adult supervision

![](cats_2.png)

---

# Unsupervised learning

Nothing to do with machines running around without adult supervision

![](cats_3.png)

---

# A little coding showcase

NOTEBOOK NOTEBOOK NOTEBOOK NOTEBOOK
NOTEBOOK NOTEBOOK NOTEBOOK NOTEBOOK

---

# Data Driven vs. AI driven

Are you a data driven company?

“Many people only use data to feel better about decisions they’ve already made.”

![](bias.png)

---

# Data Driven vs. AI driven

* What is the business aim and what do you expect the data to tell?
* Set your decision criteria before the analysis?
* Review: 4.2: More than 4 but less than 5?

---

# Ready for ML&AI?

![](data_driven.png)

* Is relevant data gathered on a routine basis, and made accessible throughout the organization?
* Is it used to create KPIs, which are continuously monitored.
* Are important decisions made based on relevant data (vs. intuition)?

If you check all with yes, your are probably data-driven. If not, don't introduce ML&AI until you are.

---

# Getting started with AI

![](cow_1.png)

---

# The AI getting-started Checklist

* Correct delegation: Does the person in charge understand your business?
* Output-focused ideation: Can you explain the system’s outputs and their value?
* Appropriate task for ML/AI: Ar you automating many decisions/labels?
* Reasonable expectations: Can you live with imperfection?
* Enough examples: Is the amount of data you have is enough to learn from?
* Team: Are you sure, you can assemble a team with the necessary skills?
* Ground truth: Do you have access to outputs?

---

# Your turn

Think about a cool ML&AI project in your industry to get started!

---

# Pick your project

* Drones? Self driving cars?
* If you are not a data-company - consider starting with something that is familiar?
* Less sexy but you know the business application and can estimate ROIs
* Airbus: Looks at predictive maintenance instead of autonomous flying…
* Industrial companies have a huge advantage where it comes to data ownership

---

# Setting up a team

Whom to hire? Let's imagine you can hire 10 people for your new data science team. What kind of people would you look for?

---

# Setting up a team

Something like that?

![](hinton.png)

---

# Setting up a team

The ML restaurant workflow

![](workflow.png)

---

# Setting up a team 

Who should operate the microwave?

![](microwave.png)

---

# Setting up a team 

Applied data science is highly interdisciplinary.

![](ds_ven_diagram)

---

# The ML-ops team

**Full-stack data scientist:** with business/domain expertise (= DS unicorn): Extremely rare, hard to hire and retain.

**Data Analyst/BI guy:** Knows how to answer business questions with tabular workflows, probably a but of (inferential) statistics, and dataviz (diagrams & dashboards). Good starting point when not existing so far.

**Statisticians:** Help decision-makers come to conclusions safely beyond the data. Carry out inferential (why) analysis, inspect data for bias.
Applied ML engineer: Trained in applying ML methods mainly to solve prediction tasks.

**ML systems enginer:** Trained in developing the tech infrastructure to bring models to production.
**(Academic) ML researcher:** Often trained in developing ML. Makes most sense when already having specific and demanding use-case. 

---

# Some of the btter ML cases

---

# Cases Product: StitchFix 

* Stitch Fix, established in 2011 in San Francisco
* Collaboration between artificial intelligence (AI) and human stylists
* Unsupervised learning paired with similarity search.
    * What are good combinations?
    * What products can be used to create the combination or an alternative?
* Takes in customer profile and order outputs combination recommendations for the stylist
* Inventory management!

---

# Cases Process: How ML Keeps Shelves Stocked at Home Depot

* Shelfout prediction: ≠ Out-of-stock
* ROI of having full shelves? - They experimented.
* Building the model: What could cause stuff not to be in the right shelve (collaborative effort)
* Result: system warning stockers

---

# Cases Service: Chatbot use at Ryanair

* Most people want to know trivial things: 
* How much cabin luggage can I carry?
* What items are allowed in checked in luggage?
* A less well known function of a chatbot is to classify requests into those that the chatbot can handle and those that require human support.
* Preselection allows to free up support to help with “real issues”

---

# Groupwork

SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING 
SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING 

---

# Wrapping up

SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING 
SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING SOMETHING 
