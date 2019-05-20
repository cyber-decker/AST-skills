# Risk Management

As a tester we have to deal with risk, hence it is our job to inform our stakeholders to help them with making the decision to move the product to production. That means that we have assessed the risks and we are in control about those identified risks.

In the "continuous" world we live in, it is still important to take risk into account when we want to deliver a feature to the customer. How to deal with risk is a key component of our test strategy.

in this document I will guide you thru the principles of Risk Management and give you information how I used this to improve my skills about how to deal with risks. I think that if you follow this trail, you will master that skill too.

The principles of Risk Management originates from the groundbreaking article ["Software Risk Management: Principles and Practices"](https://people.eecs.ku.edu/~saiedian/Teaching/Sp08/816/Papers/Background-Papers/sw-risk-mgmt.pdf) written by Barry Boehm. He classified Risk Management in the following categories and sub-categories.

* [Risk Assessment](../skills/Risk Assessment)
  * Risk Identification
  * Risk Analyses
  * Risk Prioritization
* Risk Control
  * Risk Planning
  * Risk Resolution
  * Risk Monitoring

Risk can be described as “The possibility of suffering harm or loss”. In software testing, we think of risk on three dimensions:

* How the program could fail?
* How likely it is that the program could fail in that way?
* What the consequences of that failure could be?

For testing purposes, the most important concern is:

* How the product can fail?

For project management:

* How likely?
* What consequences?

For the test designer, the essence of risk-based testing is:

* Imagine how the product can fail => Risk Assessment
* Design tests to expose these (potential) failures => Risk Control

Risk-based testing starts from an idea of how the program could fail. Then design tests that try to expose problems of that type.

A “complete” set of risk-based tests would be based on an exhaustive risk list, a list of every way the program could fail.

Two part of this sentence are of high importance 
* 'An exhaustive risk list'
* 'A “complete” set of risk-based tests'

Risk list is a product of the Risk Assessment. A tester, especially the risk based tester, must have skills to come up with such a list. These skills are how to identify the risk, where to find them, to recognize them Risk Identification. Next is to do a proper analyzes on the risk so he can determine its priorities in relation to the other risks Risk Analyses and Risk Prioritization

Risk based tests are the product of Risk Control. As a tester you must have the skill to be able to tie a risk item (potential failure) to a test, a test set or several test techniques to expose this potential failure for real. Your test (approach) to expose a real failure in the field is very valuable, and makes your test(s) efficient (find the bug quickly) rather than credible.

(source : Kaner & Fiedler – BBST, Introduction to Test Design)

Before you want to go in the details of Risk Based Test first read the general explanation of Risk management

The purpose of Risk Management is to determine in advance the most important risks related to a product or a project. You look at the probability of a hazard that can occur and what is the impact of it. When you know the risks, you can take precautions. You have taken action to deal with the risks and try to prevent them.

How do you determine/find a risk related to a product/project?
This is done on the basis of a Risk Assessment. It consists of three steps. These are:

1. Risk Identification
1. Risk Analyses
1. Risk Prioritization

Risk Identification
With Risk Identification you are going to look which risk can occur within a product or a project. You constantly ask yourself the question; "What can go wrong?". You will do this investigation with stakeholders, persons who can say some about the product or project. You will find out what is happening.

Risk Analyses
For each identified risk, you will look for the possibility (probability) that it occurs and the impact that it brings along with it. You constantly ask yourself the question; "What are the main risks that we need to address?" The potential risk item is 'converted' into information that can be used to make decisions about these risks

Risk Prioritization
After extensive analysis, the risks are classified (measurable) and you can give it a priority. On the basis of risk exposure (the relationship between probability and impact), you can determine which risks are important and should be addressed first.

Now you have a list of risks, you should come up with a plan to address them. How will we manage the risks? This is done on the basis of Risk Control, which consists of three steps. These are:
 
1. Risk Planning
1. Risk Resolution
1. Risk Monitoring

Risk Planning
When you have identified the main risks and the corresponding relative priority, a plan must be created how to deal with each risk. The following actions can be taken:
 
* Risk Avoidance
* Risk Reduction
* Risk Acceptance
* Risk Transfer

Risk Resolution
Execution of the plans that are required to manage the risks.

Risk Monitoring
Ensure that the risk-reducing activities proceed according to plan. Where necessary, corrective actions are taken.



