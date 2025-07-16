---
title: "Introduction"
teaching: 5
exercises: 0
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is the purpose of this workshop?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- n/a

::::::::::::::::::::::::::::::::::::::::::::::::

## Purpose

![](fig/security-concern.PNG){alt='UI of Moneyzoom' style="float:right; width:300px;height:auto"}


In a world where software is essential for nearly every aspect of modern life, the need for secure development have never been greater.
However, many software engineers enter the workforce with limited knowledge or training on how to contribute to security during development without being security experts.
In this workshop, you will learn about and participate in activities that software engineers can perform to make development more secure.
These activities include:

- Identifying security risks
- Evaluating the trade-offs of addressing those risks
- Effectively communicating with other stakeholders about the problem.

This workshop is intended for research software engineers.
Due to the diverse backgrounds an RSE can come from, we cannot speculate on your current security knowledge or expertise.
Therefore, we assume you have limited knowledge of security. 
The good news is that this workshop is derived largely from the [Developer Security Essentials] workshop by Charles Weir.
[Developer Security Essentials] aims to instruct software engineers on threat assessment and benefit analysis, requiring little security expertise.
Other information in this workshop is informed by Charles Weir's [Secure Development Handbook].
This handbook is a good reference guide for the topics of this workshop and contains additional topics you may find interesting.

> "As someone working with developers and concerned about
software security, you want the ‘how to do it’. Not the
technical detail, but how you can change your professional
approach and that of your colleagues to deliver adequate
software security at a minimum cost. You reach for the
dummies guide, and there’s nothing like that available.
This book addresses that gap."
>
Source: [Secure Development Handbook]

To start the workshop, we will play a card game called the "Agile Security Game."
This game does not require security expertise to play and motivates developers to start considering their own projects' security and privacy requirements.
We assume participants do not have a common project they can discuss, therefore an artifical project and its connections are supplied.

The next part of the workshop focuses on threat assessment and benefit analysis.
In this activity, we explore the question "Who might do what bad thing to whom?"
Similarly to the card game, an artifical project is supplied.
This activity results in a list of identified threats to address.
The next activity focuses on benefit analysis.
In this activity, participants must make a case to "product management" about why they should address a given threat.



::::::::::::::::::::::::::::::::::::: keypoints 

- Threat assessment and benefit analysis are both activities that developers can perform with little security expertise.

::::::::::::::::::::::::::::::::::::::::::::::::

[Secure Development Handbook]: https://www.securedevelopment.org/resources/
[Developer Security Essentials]: https://www.securedevelopment.org/workshops/