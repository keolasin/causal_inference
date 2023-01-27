---
Week: 1
Lecture: Lecture 1.1
Topic: Why bother with Causal Inference?
Instructor: Laura Balzer
Course: Intro to Causal Inference, PHW 252A
Tags: Introduction, Causal Inference, Statistics, Summary
---

# Lecture 1.1: Why bother with Causal Inference?

## Descriptive, Prediction, & Causal questions

Not all questions are causal:

- what was the average age of participants in our study?
  - descriptive, table 1 in applied journal papers
- which risk factors were associated with the outcome?
  - prediction, building a risk score for badness

But many of our questions are causal:

- how best to intervene to improve health

## What makes a question "Causal"?

Asking about the world under changed conditions

- for example, changing the way in which the exposure was generated
- Inference about a distribution that we do not (fully) observe

How would the outcome differ if all participants were exposed, vs. if the same participants, over the same time-frame, and under the same conditions were not exposed - (ideal experiment and concept of counterfactual)

### Some Sources of association

1. direct effects
2. indirect effects
3. measured causes
4. unmeasured causes
5. selection
6. all

**Note**: Big or small data do *not* undo "correlation is not causation"

## Causal Frameworks to the Rescue

How do we proceed from this seemingly complex mess?

1. Provide a systematic process: research question -> ... -> estimation and inference

- builds off the scientific method

2. Many frameworks available
   
- focus on framework for Targeted Learning
  - integrates causal modeling with machine learning algorithms and statistical inference

## The Causal Roadmap

1. Research Question
2. Causal model representing real knowledge
3. Counterfactuals & Causal parameter
4. Observed data & Statistical Model
5. Identify: Knowledge + data sufficient?
6. Statistical Estimation Problem
7. Estimation
8. Interpretation