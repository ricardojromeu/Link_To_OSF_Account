# Link_To_OSF_Account
This provides a link to my Open Science Framework Account, where I post code and describe the research work I've been doing in my PhD

# Link to Projects:
Here's the link: https://osf.io/gavwn/

# Summary of what's there so far

(1) Analysis of Huntington's Disease Data - Here I applied a Ratcliff Diffusion model in a Bayesian way to analyze choice-response times from Huntington's/pre-manifest Huntington's/ and healthy control groups. Overall, we found that the pre-manifest group performed in between the Huntington's and controls in terms of what's called "evidence accumulation rate" in the diffusion model, but only when there was a large amount of stimuli on the screen (what was called the "Many" condition, could be considered a "Difficult" setting for the task). 

(2) A Bayesian Item Response Model - I created a framework for dealing with what I call "conditional structures" in self-report measures. This would involve questions like, "Would you endorse X?" where the person would respond "yes" or "no." And, _if_ they responded "yes," they would be asked to further questions, like, "Okay, how would you rate your experience with X?" In other words, the presentation of some questions are dependent (or conditional) on responses to another set of questions. And, in some cases, the response scales for these questions might be different. In the example here, the endorsement question would have binary responses (yes-no), while the follow-up question could be on a 1 - 5 Likert scale (rating experience). The general framework I developed would be able to handle this style of questions. I tested this framework on a popular method of measuring delusion-proneness (or, the likelihood of developing a delusion in the future) called the PEters Delusion Inventory, and overall the method was successful. 

# What's to come:
I will eventually post the code relevant to my PhD dissertation. This includes a number of files that would be useful to others who would want to independently replicate my work:

(1) All code I wrote to build the necessary experiments will be posted. In my thesis, I ran two experiments, the Peters Delusion Inventory (PDI) and the Beads Task. I'll have a version of the code with both tasks in one file, and then a file for each task separately for those who only want to run one task or the other and not both. 

(2) All code used to fit the models I test. This will include both the models for the Beads Task and the PDI, since I will rewrite the latter's code in Python. Implementing these models in Python will hopefully make it easier for others to use the code, since Python is free and ease to use. 

Stay tuned! 
