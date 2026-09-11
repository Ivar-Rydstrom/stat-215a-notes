# STAT 215a (applied statistics) notes
### UC Berkeley, Fall 2026

# Discussion 3

### Plotting tips

Save as .svg for vector graphics (try not to use .png when importing into LaTeX).

Make ticks point inwards, not outwards. Put ticks on all sides of the axes.

plt.rcParams['xtick.direction'] = 'in'
plt.rcParams['ytick.direction'] = 'in'
plt.rcParams['xtick.top'] = True
plt.rcParams['ytick.top'] = True

If using colormaps, rainbow colormap can sometimes show artificial boundaries in the data.
"Perceptually uniform" colormaps are usually better at seeing the difference between values in the colormap.
Can include topographic lines on top of the colormap to show true boundaries in the data.


# Lecture 5 (Sep 10 2026)

## Problem Formulation

Not all domain problems need to be solved computationally. Lots of traders just go off of their gut, and are very successful.

Who are the people this effects? Who are the 'patients' this problem serves? In other words: is this problem rooted in the real world, or is it fabricated and doesn't help anyone?

#### Discussion:

The readings present a practical and pragmatic stance on statistics and machine learning. Instead of using math headlessly to force it to model problems, ensure the problems you solve are appropriately grounded in the real world, and useful. It is better to have a model you don't understand that works, than a model that you do understand that doesn't actually help solve the problem and is not good at prediction.

# Lecture 3 (Sep 3 2026)

What do I think "scientific responsibility" means?

I think scientific responsibility is being honest about the limitations of your work, not cherry picking data without disclosure, being transparent about methods. The general public may not understand the nuances of your work, but they may follow the conclusions you draw. Scientific responsibility is ensuring that the conclusions that the public may draw from your work are not misleading. They look at "scientists" for the truth, so don't knowingly lead them away from that.

Be open minded and embrace surprises. It's not about being right, it's about uncovering the truth.


What about "Critical thinking"?

Reasoning about things for yourself. Considering the facts/evidence and coming to your own conclusions.
Understand your own bias. Avoid confirmation bias.


# Lecture 2 (Sep 1 2026)

Guest lecture with medical professional Aaron.

Background: CT scans can help diagnose intra-abdominal injuries, but they are expensive and expose patients to radiation. Clinical decision rules (CDRs) are tools that help clinicians decide when a CT scan is necessary based on patient symptoms and risk factors.

Risk of getting cancer from CT scan ionizing radiation for girls is lower than for boys.

### Case study: intra-abdominal injury

Injury to spleen, liver, urinary tract, pancreas, etc.


### Clinical decision rules

Tools that clinicians use to make decisions (must make fast decisions with limited information).

Is a set of rules with probability thresholds based on variables (heart rate, blood pressure, trauma, rash, etc)

* Widely used in clinical decision-making.
* Must be accurate, interpretable, and actionable

1. Severity of injury

2. Does the injury require an "Acute Intervention"? death, surgery, blood transfusion, etc.
Not all injuries require intervention.

3. Does it improve on existing clinical practice?

### Steps to set rules

1. clean up the data

2. 

3. Modeling


Example of Clinical Decision Instrument: [MD Calc Pecarn Website](https://www.mdcalc.com/calc/3971/pecarn-pediatric-intra-abdominal-injury-iai-algorithm)


We will make a lot of small judgement calls in our data analysis. Document the judgement calls so we can justify them later.


# Lecture 1 (Aug 27 2026)

AI stuff and boring intro stuff

