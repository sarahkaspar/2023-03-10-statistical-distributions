---
title: "Sampling"
teaching: 10
exercises: 5
questions:
- "What is sampling?"
- "What is a statistical distribution?"
objectives:
- "Understand the concept of sampling and statistical distributions."
keypoints:
- "Sampling means drawing events from the population of interest."
- "Sampling has to be random and independent for the sample to represent the population well."
- "Sampling processes can often be described by a statistical distirbution."
---

# Sampling frogs in a lake

![](../fig/sampling-frogs.png)
new path

Let's start with an example, and thereby define some terminology.
We have a lake with frogs in it, and there are light and dark green frogs.
There’s a sunny side of the lake, and a shadowy area by the trees. Now imagine you want to estimate the fraction of light green frogs in the lake.
There are too many frogs to count them all, so you catch a few and count how many of them are light coloured. This is a sample.
A *sample* are randomly independently drawn events from a population of interest. The *population of interest*, in this case, are all the frogs in that lake.
How can we draw randomly and independently? One obvious thing you could randomize in this experiment is the location at which you cath the frogs, because from the above picture you could get the impression that light-coloured frogs gather more in the shadows, while the dark-green frogs like the sun. Therefore, if we caught all the frogs in the same area, like in sample 1, this would probably overrepresent light frogs, thus not representing the population well. When randomizing the locations, this is less likely to be the case (see for example sample 2).
You get similar problems if the observations are not independent. One example of dependent observations would be if you start with one frog, then catch the one right next to it, and so on. This is also likely to overrepresent one colour of frogs, and the reason why observations shouldn’t depend on each other.
The *sample size* is the number of frogs in one sample.
And the *distribution* is a set of rules that the random frog catches follow.

          


> ## Quiz question
>
> Which of the following statements are true?  
> (1) A probability distribution assigns probabilities to possible outcomes of an experiment.  
> (2) The probabilities in a statistical distribution sum/integrate up to 1.  
> (3) If the experiments are not randomized, the results don't follow a statistical distribution.  
> > ## Solution
> >
> > Answers 1 and 2 are correct. To 3: If experiments are not randomized, the results still follow some distribution, but they are likely to not represent reality well.
> {: .solution}
{: .challenge}
