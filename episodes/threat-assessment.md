---
title: "Threat Assessment"
teaching: 5
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- What process do I follow to identify threats?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Your group should identify some threats and discuss their risk and impact.

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: instructor

### Instructor Notes - Prep


## Setup in Advance
1. Ensure there is a project for each participant to discuss. Each project should have at least 3 participants who know it well enough to discuss possible security problems.For participants with no such shared projects (or who have reasons not to discuss them), use the ‘MoneyZoom’ project from the previous Agile App Security Game workshop, and ensure each such participant has a printed description available (such as from the previous workshop).

### Setup in Advance – Face-to-face
1. Arrange tables for participants so each table has 3-6 participants, all familiar with one project.
2. Place a large number of various coloured post-it notes and appropriate (sharpie- style) pens on each table.
3. Set up whiteboards and flip charts (one for each project to be discussed the participants and one extra).
4. Have a few (whiteboard/flipchart) marker pens in two contrasting (allowing for colour blindness) colours. E.g. Black and red, or blue and red.
5. Locate a timing device (eg. mobile phone, physical timer, or Google Search “countdown timer”).


::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

You probably know that security is important.
But how do you, as a developer, impact security?
That first requires a different question: *not how but what?*

- What should you be worried about?
- What is likely to harm you, how would it happen?
- If it involves external attackers, what do they want, how might
they go about getting it and how much do we care?

Finding the answers to these questions is called "Threat assessment" or "threat modelling."
In this activity, we will do a light-weight exercise to introduce you to the concept of threat-modelling.

::::::::::::::::::::::::::::::::::::: instructor

### Instructor Notes - Running the Workshop

The timings are approximate. 
Adjust them according to how the teams are getting on in each step.

### Step 1: Ideation (30 min)
Display the slide with: *Who might do what bad thing to whom?
    Person – Thing – Reason*

Ask the groups to think about their project, and ‘ideate’ answers, writing down the person-thing-reason combinations on the post-its on their board.
Encourage everyone to write independently (duplicates will be combined in the next step).
Remind them that not every bad thing is malicious; sometimes security or privacy issues happen due to accident or misunderstandings.
Encourage them to discuss the issues, and to gather as many completed post-its (‘threats’) as they reasonably can.

### Step 2: Organisation (15 min)
Have the participants in each room cluster the ‘post-its’ into ‘topics’, posting related ones close together and duplicates on top of each other.

### Step 3: Evaluation (15 min)
This step identifies the most important threats.
Copy the ‘dot voting sets’ to the appropriate boards for each breakout room.
Ask each participant to pick the threats (post-its) that are (a) most likely, and (b) most damaging.
And to place a black dot next to the each of the three they consider most likely; and a red dot next to the three they think most damaging.
When they’re done, take a photo of each of the resulting boards, for reference.

### Step 4: Summary (10 min)

Get the Technical Leads or a responsible couple of people from each project to use the dots next to each post-it to position a selection of the threats on the grid.
A dozen or so is a good number to aim for.
Figure 4 shows an example (online); Figure 5, an example face-to-face.
The threats towards the top right are the most important ones to consider in the corresponding projects.

::::::::::::::::::::::::::::::::::::::::::::::::

## Step 1: Discuss & Ideate

Who might do what bad thing to whom?

*Person* – *Thing* – *Reason*


Begin this section by thinking about the question above.
Write down any combination of *Person* - *Thing* - *Reason* you can come up with on your worksheet.
Feel free to write independently from the rest of your group. 

Remeber that not every bad thing is malicious.
Sometimes security or privacy issues happen due to accidents or misunderstandings.
Discuss the issues amongst your group and gather as many completed threats as you can.





## Step 2: Organize

Cluster the ‘post-its’ into ‘topics’ by posting related ones close together and duplicates on top of each other.





## Step 3: Evaluation
This step identifies the most important threats.

- Pick the threats (post-its) that are (a) most likely, and (b) most
damaging1. 
- Place a black dot next to the each of the three you consider most likely;
- Place a red dot next to the three you think are most damaging.



## Step 4: Summary

Using the risk-impact grid, place a selection of the threats onto their appropriate space.

This information will be used for the Benefit Analysis section!

::::::::::::::::::::::::::::::::::::: instructor

### Instructor Notes

### Notes
The risk-impact grid is an inaccurate way to assess risks; however it is easy to understand and use.
More sophisticated teams may well use better approaches, but these are outside the scope of this workshop.

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: callout 

The risk-impact grid is an inaccurate way to assess risks; however it is easy to understand
and use. More sophisticated teams may well use better approaches, but these are outside
the scope of this workshop.

::::::::::::::::::::::::::::::::::::::::::::::::


::::::::::::::::::::::::::::::::::::: keypoints 

- Not all "bad things" are malicious, sometimes accidents happen.
- Threats should be considered by their likeliness and impact.

::::::::::::::::::::::::::::::::::::::::::::::::