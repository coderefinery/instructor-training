---
layout: episode
title: "Running CodeRefinery workshops"
teaching: 20
exercises: 10
questions:
  - "How can you use CodeRefinery lessons?"
  - "What are the essential steps for organizing a CodeRefinery workshop?"
objectives:
  - "Learn how to use CodeRefinery training material."
  - "Discuss on how to run a CodeRefinery workshop."
keypoints:
  - "Flexibility to reuse CodeRefinery teaching materials."
  - "Checklists for running CodeRefinery workshops."
---

## Organizing a CodeRefinery workshop

Anyone can organize a CodeRefinery workshop and teach the CodeRefinery lessons which are 
licensed under [CC-BY](https://creativecommons.org/licenses/by/4.0/).
However, making it a successful workshop requires careful planning and preparation. Here we will go 
through practical aspects of organizing a workshop. 

> ## Workshop manuals
> CodeRefinery maintains a number of [workshop manuals](https://github.com/coderefinery/manuals/) 
> with practical tips and checklists. We will be refering to this material below.
{: .callout}

## [Before the workshop](https://github.com/coderefinery/manuals/blob/master/workshop-administration.md#before-the-workshop)

- Select workshop coordinator
- Instructors and helpers
- Lecture room
- Advertising the workshop
- Communication with registered participants 
- Practicals

---

## [Pre-workshop survey](https://github.com/coderefinery/pre-workshop-survey)

It is very useful to ask future workshop participants to fill a pre-workshop survey before 
attending a workshop. The survey should probe the participants' previous experience 
with different tools and programming practices, which operating system the participants use 
and what lessons they are most interested in. 

The questions that are currently asked in the CodeRefinery 
[pre-workshop survey](https://github.com/coderefinery/pre-workshop-survey)
are the following:
- What is the operating system that you will use during the course (on your laptop)?
- Which version of operating system are you using? If your operating system is Linux, which distribution are you using? 
- Are you using version control? If yes, which?
- Which programming languages are you using or will you use in your projects?
- Are you using automated testing in your programming project(s)?
- Are you using code coverage analysis in your programming project(s)? These are tools and services like Gcov, Cobertura, Codecov, Coveralls, Code Climate, etc.
- Are you employing code review in your programming project(s)?
- Are you using the Travis or Jenkins or GitLab CI continuous integration service in your programming project(s)?
- How do you document your code?
- Are you using a web-based repository for your code(s)? Which ones?
- How would you describe your programming experience?
- How comfortable are you with the Unix/Linux command line working in a terminal window?
- Are you using an integrated development environment (IDE) for your programming project(s)?
- Please specify your main academic discipline. Please take the entry which is closest to your main field of study/work.
- Please select the sessions that you are most interested in.
- What do you expect to get from this course?

> ## Discussion: Pre-workshop survey questions and results
> 
> - Take a moment to read the survey questions. Is there anything you would want to add? Or remove?
> - How do you think the survey results look like for past workshops? Have a look at the
>   [survey repository](https://github.com/coderefinery/pre-workshop-survey) which shows the 
>   main results, and compare them with your expectations.
{: .task}

---

## Preparing lessons

- Carefully go through the lesson material you will be teaching and think about how you 
  intend to teach it, and how much time you will be spending on each episode.
- Go through the instructor guides of the lessons you will be teaching. Try to memorize the 
  typical pitfalls, common questions and core aspects that you should make sure to convey clearly.
- Collaborative Git and documentation lessons require exercise repositories to be set up. 
  For this follow the instructor guides in the lesson material.
- Go through the [lesson presentation hints](https://github.com/coderefinery/manuals/blob/master/presenting.md).

---

## During workshop

#### Arrival 

- As people arrive, emphasize to people that they need to sit with someone - don't work alone.
- Give an introductory talk, see [https://github.com/coderefinery/workshop-intro](https://github.com/coderefinery/workshop-intro).
- Have a 10 minute ice-breaker session where participants and instructors introduce themselves 
  and either describe their research in 2-3 sentences or what they hope to get out of the workshop.

#### While teaching

- Keep up interactive feel by encouraging and asking questions.
- Keep time.
- For presentations which have shell commands, create a cheatsheet/reference on the board in real time.
- Remind people about sticky notes.
- Make sure to take regular breaks (at least a short break each hour).
- Give participants some time to also experiment (do not rush the classroom through exercises).
- Encourage optional feedback at the end of each day on sticky notes.
- Create GitHub issues for points which are confusing or problematic.
- Take active part even in the lessons you're not teaching, e.g. by asking questions and (politely) interject with clarifications when you think something is confusing to the learners.

---

## End of workshop

- Give credit to those who contributed and helped.
- Use [https://github.com/coderefinery/workshop-outro](https://github.com/coderefinery/workshop-outro).

---

## Post-workshop

- Process and distribute feedback (e.g. type up in shared document)
- Debrief with instructors.
- Process certificate requests.

---

> ## Set up a workshop webpage
>
> 1. Go to the [workshop template repository](https://github.com/coderefinery/template-workshop-webpage). 
> 2. Click the green "Use this template" button to import the template to your own account. 
>    Name the new repository to include a date and a location, e.g. "2019-12-24-stockholm".
> 3. Clone the new repository and inspect the files. Open `index.md`, update some fields and commit the changes.
> 4. Push the commits. The workshop page should now be served on GitHub Pages
>    (e.g., *https://username.github.io/2019-12-24-stockholm/*).
{: .challenge}


