<p align="center">
<img src="https://github.com/squigglydonut/portfolio/blob/master/NVIDIA-Machine-Learning-Hackathon/imgs/banner.png"></p>
<h1>Summary</h1>
<p>In July 2016 I competed in a hackathon focused on the topic of Machine Learning. While I didn't work on the ml part of our project, I learned a ton about it from my teammates and the breakout sessions offered during the event. Our idea was to solve an issue our teammate Jamie had and that was applying to jobs.<br></br>She found herself, a recent graduate with a Masters, applying to over 100 jobs and seeing only a handful of interviews. She was sending a lot of the same information to potential employers and so she wanted a way to automatically apply to a bunch of jobs at once, like what the Common App does for college applications. So we built Steve's Jobs, a platform where you can upload your resume, answer a few questions, and you're done!</p>

<h2>What I Built</h2>
<p align="center">
<img src="https://github.com/squigglydonut/portfolio/blob/master/NVIDIA-Machine-Learning-Hackathon/imgs/stevesjobs.gif"></p>
<p></p>

<h2>Barriers</h2>
<p>Because this was a Machine Learning hackathon, we built our idea not as an aggregation platform but more as a matching platform. "Features" are very important in ml applications so we decided to focus on one type of applicant, a data scientist, and train the algorithm to detect one. We originally attempted to scrape github profiles but found the information provided in bio's is often missing and would mislead our feature set. We settled on StackOverflow profiles as they include a lot of credibility and ratings and would allow us to determine what a good data scientist looked like and what "not-a-data-scientist" looked like.</p>

<h2>Shortcomings</h2>
The design had too many screens because we had a hard time determining what the core value of our product was. By the end of the event we had successfully trained our algorithm (2 data scientist on our team) but our automatic job application "applyer" worked only on platforms without captcha.

<h2>Further Work</h2>
I think the job market will become 3 things. 
* Applications will aggregate so that an applicants profile gets added "to the pool"
* Companies will know exactly who they need to hire
* Companies will be able to source from the maximum number of applicants

So I think future work would involve consolidating this idea into one of those categories and "solving one problem really well".

