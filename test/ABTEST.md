**A/B Test Name:** Logout screen

**User Story Number:** 4

**Metric:** NPS and CTR

**Hypothesis:** By adding an additional screen for signing out with clear instructions and options, users will find it easier to complete the sign-out process, resulting in higher NPS scores and increased CTR on other app features.

**Experiment:** For the experiment setup, we will use Firebase Remote Config to implement the A/B test. We will allocate 50% of our user base to the experiment group (Group A) and the remaining 50% to the control group (Group B).

Rationale - Allocating 50% of users to each group ensures that we have a large enough sample size to draw meaningful conclusions from the experiment. Along with splitting the users evenly between the experiment and control groups helps minimize bias and ensures that any differences in outcomes can be attributed to the variations being tested rather than other factors.

Tracking Using Firebase Analytics - Set up event tracking in Firebase Analytics to monitor user responses to the NPS survey before and after the experiment. Track events related to the survey display, user responses, and overall NPS calculation. Also implement event tracking to monitor the click-through rate on other app features for both the experiment and control groups. Track events related to user interactions with different app features to measure changes in engagement.

**Variations:**
Control Variation (Group B):
Users in this group will experience the existing sign-out process without any modifications. This serves as our baseline for comparison.

Experiment Variation (Group A):
Users in this group will be presented with an additional screen for signing out, which includes clear instructions and options for confirmation. This variation aims to streamline the sign-out process and improve user experience.

**A/B Test Name:** Sign In to Prompt Screen

**User Story Number:** 4

**Metric:** Click Through Rate to Answering the Prompt

**Hypothesis:** My hypothesis is that users may not want to click through enough screens to get to the point where they answer the daily prompt. Therefore, I want to see if making the user encounter the prompt writing screen upon signing in will increase the number of users who write a prompt each day.

**Experiment -** The experiment will be completed by taking a group of users that do not respond to the prompt on a daily basis. Half of the users will be given the app with the variation while the other half will keep the base version of the app. After a week or so, the click through rates of the two groups will be compared to see which one is higher.

**Variations-** In the main app, when the user first signs in they are brought to the home screen with multiple places to go to from there. The variation fot this experiment will be when the user first signs in they will be brought directly to the prompt screen for the day if they have not filled out the prompt yet. This should encourage the users to fill out the daily prompt.

**A/B Test Name:** Rating Pop Up

**User Story Number:** 4

**Metric:** NPS

**Hypothesis:** My hypothesis is that users may get annoyed when they are prompted with a "rate my app!" pop-up after finishing a prompt like most other apps. Users tend to only rate the app if they have to or if they are randomly prompted with it unless they had an extreme experience, but giving the user the option to rate the app whenever they want could be an appreciated app that could lead to more positive reviews.

**Experiment -** The experiment will be conducted by taking the users that finish the daily prompt every day, with half of these users getting prompted to rate the app after every few prompts. The other half won't get prompted at all, and will have the option to rate the app whenever they open the drop down menu in the home screen. After 7 daily prompts, we can compare the NPS scores between the variations and take into account the amount of reviews that we get from each variation.

**Variations-** The main app will have the users that don't get prompts and can simply choose to rate the app whenever they please, and the one variation of the app will include the random "rate my app!" pop up after every 2-3 prompts that they answer in the prompt screen. This will give us a better idea on how we should conduct our surveys for our NPS score.


A/B Test Name: Prompt Viewing
User Story Number: 4
Metric (from the HEART grid): NPS
Hypothesis: I think that people will prefer to see the prompt and have to click on it to see the user rather than see the user and click on it to see their prompt

Experiment - The setup will be two similar screens, one where it provides the user with the prompts and allows them to click on it to find the user, the other provides the user and allows them to click on it to see the prompts.

For the audience, 50% of users will receive a different view prompts screen than the default one. 

The rationale behind it is that there are two main ways the data is sorted and that the the view prompts screen could be set up. By making one for each we can see how users like each version.

To track this, we will randomly provide the users with either screen 1 or screen 2 without them knowing which one they have. After they use it a few times we will prompt them with a question asking if they are satisfied with the way its set up, or if they have suggestions on how it should be set up. 

Variations - The two variations I want to do are:
The user is presented with a list of boxes each with a different user prompt in it, and the user can scroll and read them as they want. If they want to see more prompts by the user they can click on them to view their profile.
The user is presented with a list of boxes each with a different username in it with the first couple sentences of the prompt to give them an idea what they wrote about. They can then decide to click on it to view the whole prompt or view their profile.
