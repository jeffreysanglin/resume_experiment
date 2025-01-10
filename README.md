# Resume Experiment
In 2024 I decided to apply to open data science and analytics positions. Often, the rejection/interview decision for these positions seemed like a black box. I was never sure why particular companies rejected or accepted my application. 

I wondered how/why recruiters were reaching their conclusions. Professionals had often suggested getting a professionally written resume and cover letter in order to be seen by ATS and recruiting processes. I decided to run experiment--show my self-written resume and cover letters to some applications while using a resume and cover letter written by a certified resume writer. Here's what I discovered!

# My Process
I. Pre-Analysis
I ran a quick pre-analysis to identify what kind of response rate I was seeing without using an alternative resume. I was picking job openings that I was a good fit and my response rate (invitations to interviews by the recruiter) was around 8%.

II. Design and Determining Sample
You can read the full rundown on the XP design [here](https://docs.google.com/spreadsheets/d/1w9lm5mPkVdQvBfVVBUPMmL8xUj5n0weZRhK8kbSiFyQ/edit?gid=0#gid=0). I'll share a quick summary below.

**My Hypotheses**
| Hypothesis | Description |
|------------|-------------|
| H0         | The resume and cover letter provided by Haley Stock perform the same as my own self-written resume and cover letter. |
| Ha         | The professionally-written resume and cover letter have a different interview invitation rate than the self-written resume and cover letter. |

I wanted to show whether one performed better than the other, so I chose a two-tailed XP. However, there were quite a few uncontrollable variables at play, that I accounted for in my design such as industry trends or even application platforms (lever, greenhouse, etc.)

I knew sample size would be the hardest part, so I considered the factors that were most important to me:
1. I mainly wanted to see if there was a glaring difference between my self-written resume and a pro-written one. I decided that a response rate difference of 5% or more was important enough to change how I applied to jobs.
2. Both resumes were solid illustrations of my capabilities and work history, so I was willing to risk a higher alpha and beta than normal (10%, 30% respectively).
3. At the time I wanted to apply to both manager and IC roles, so I segmented the randomization by these categories to reduce bias. This way I could ensure an equal distribution across C/T for these segments.

The sample size calculation pointed to 350 samples for each control and treatment which would be a lot, but doable.

III. Running the XP
I set out to apply to 700 job openings. This took over a month of submitting job applications to Data Analytics roles (Manager or Senior IC). I collected the data inside a google sheet and randomly assigned to control or treatment, segmented by job type (IC or Manager).

# Findings
In the end the difference in response rates was not statistically significant. In fact the response rates were much lower than the pre-analysis 8%. 2.7% for control (my self-written resume) and 2.2% for treatment (pro resume). 

Why was this? A few posibilities came to mind:
- My initial pre-analysis likely "cherry-picked" more fitting job postings for my work history and companies like my previous one. This meant my response rate was higher for that batch but lower when I was applying to any role, even if it was less like my previous company.
- There were likely other factors at play (like other applicants applying for some roles but not others), because it's hard to control for everything within a job application process.

# Conclusion
Ultimately, I want to showcase my work history and abilities to companies that will value them. I also want my own values to shine through. Since there is not a stat sig difference in response rates, I will use my own resume and add in any bits I like from the pro-written one.

# Reflections
**What worked well...**

I. It eased my mind that at least on the surface, my self-written resume isn't a 100% stinker :D.

II. I built a python class that will help me with future "proportion" tests and XP's. 

**What I'd do differently next time...**

I. I'd do a bit more work on the pre-analysis. While both the self and pro resumes didn't perform signifantly different, it would be better to know what actually does change response rates for my job applications.

II. The sample size was ultimately the problem. It's possible a different approach, such as diff in diff, would have fit the use-case better. It may have also helped control for other unseen issues that could not be controlled in the AB test.
