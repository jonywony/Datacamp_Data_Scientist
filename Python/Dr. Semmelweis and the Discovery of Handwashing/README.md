# Dr. Semmelweis and the Discovery of Handwashing

## Background

Dr. Ignaz Semmelweis, a Hungarian physician born in 1818 and active at the Vienna General Hospital. If Dr. Semmelweis looks troubled it's probably because he's thinking about childbed fever: A deadly disease affecting women that just have given birth. He is thinking about it because in the early 1840s at the Vienna General Hospital as many as 10% of the women giving birth die from it. He is thinking about it because he knows the cause of childbed fever: It's the contaminated hands of the doctors delivering the babies. And they won't listen to him and wash their hands!

In this notebook, we're going to reanalyze the data that made Semmelweis discover the importance of handwashing. Let's start by looking at the data that made Semmelweis realize that something was wrong with the procedures at Vienna General Hospital.

## Insight

#### Proportion of Deaths Comparison between 2 Clinics

![Clinic Comparison](https://github.com/jonywony/Datacamp_Data_Scientist/blob/main/Python/Dr.%20Semmelweis%20and%20the%20Discovery%20of%20Handwashing/pictures/clinic_comp.png)

Dr. Ignaz Semmelweis at first asked the question on why there are differences between proportion of deaths from childbed fever by different clinic. After some investigation, Dr. Semmelweis suspected that the clinic 2 have lower proportion of deaths because the clinic 1 is mainly served by medical students, while mostly midwife students served at Clinic 2. While the midwives only tended to the women giving birth, the medical students also spent time in the autopsy rooms examining corpses.

Dr. Semmelweis started to suspect that something on the corpses spread from the hands of the medical students, caused childbed fever.

Does washing hands can lower the proportion of death caused by childbed fever?

#### Proportion of Deaths Before and After Washing Hands

![Proportion before and after washing hands](https://github.com/jonywony/Datacamp_Data_Scientist/blob/main/Python/Dr.%20Semmelweis%20and%20the%20Discovery%20of%20Handwashing/pictures/wash_before_after.png)

The graph shows that just by washing hands can make such a huge differences by reducing the proportion of deaths from 10% to 2% or 8% differences.

#### Bootstrap Method

To get a feeling for the uncertainty around how much handwashing reduces mortalities we could look at a confidence interval (here calculated using the bootstrap method). Handwashing reduced the proportion of deaths by between 6.7 and 10 percentage points, according to a 95% confidence interval.
