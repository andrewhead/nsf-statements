# Outline

## Information needs

Challenges when first starting a new job

## A Revised Vision

When taking on a job for the first time, a programmer inevitably needs to start finding information and learning on their own (Exter & Turnage).

Recently, comprehensive (Parnin et al.), high-quality (Mamykyna et al.) crowd-developed online documentation has made it easier than ever for programmers to fall back on the web to find examples of how to use unfamiliar language features and APIs (Brandt).
But using online documentation can be fraught with hazards.
When learning just the bare minimum to do a coding task (i.e., programming "opportunistically" (Clarke)), programmers develop shoddy code that just satisfies the intended functionality, reimplement code that stable libraries could support, and spend time debugging code (Brandt a, Brandt b).

A CS student's upper division courses and project work often offers them their first opportunities to satisfy information needs to using these online sources almost exclusively.
And while code examples have been identified as a critical component of CS education (ref), we do not understand the role of the online code example in upper division programming learning.
One reason is that online code examples have only recently become available to programmers on a large scale and with reliable quality, in many ways in part to the creation of StackOverflow, a massive, popular programming Q&A, launched in 2008.

Several important questions about the role of the online code example in non-formal learning are significant to improving CS Education in upper division courses and the ability of newly-graduated programmers to learn on the job.
These questions include:
When copying and pasting is easy, do programmers actually learn new concepts from code examples (Q1), e.g., enough to design new code from the same components (Q2)?
How often do they reuse code that contains bugs, style errors, or non-idiomatic code (Q3)?
How long does this code remain in use (Q4)?
What interventions can supplement information seeking to encourage successful learning (Q5)?
What interfaces can support more successful reuse of code found online (Q6)?

**My proposed research seeks to understand the affordances and pitfalls of student programmers working with code examples, to categorize and count the mistakes made, the frequency of knowledge gained, and the opportunities to build interventions in the form of novel interfaces that can to enable students to effectively work with and benefit from online examples.**

## The General Approach

I can gain deeper, generalizable insight on each of these questions by following standard techniques of observation and systems evaluation from HCI.
In each case, the critical question to the design of my research is **how can I simulate scenarios of web-based code reuse in a controlled setting, and measure behavior with code examples?**
While a variety of techniques are available, I can offer the most knowledge to the academic community by observing reuse habits in two ways.
First, I will conduct controlled lab studies to address Q1-Q4, (e.g., Ichinco &amp; Kelleher, Brandt et al., Head et al.) with dozens of participants sampled from Berkeley's large population of EECS undergraudate students.
Second, I will conduct contextual inquiry with (Meyer & Holzblatt) with members of student groups during implementation prototypes for Berkeley's upper division user interface course, a period where discovery and testing of user interfaces within a team are likely at their prime.

Given this knowledge, I will develop a new generation of web and IDE-based interventions for better supporting learning and reuse from online code examples.
This body of systems will satisfy, I suspect, two major needs:
First, the need to support better understanding of code found in the wild at lower cost via automatic explanations.
This is a need we have already address with the Tutorons infrastructure I built for past work and will be easily adaptable to the problem at hand (Head et al.)
Second, the need to support new forms of mental model-building, learning and interaction with code examples.
Once again, this can be gained supported with in-situ, in-the-browser interactions akin to those.
However, there are challenges to both building automatic help and providing it in a form that will be instantly read within the browser.
We propose that interactions that force close inspection of code prior to pasting will enable better design with these components later on down the road.
We will use standard techniques to measure the quality of code produced (e.g., Brandt et al.), ability to process code found anywhere (e.g., Head et al.), and user ability to complete tasks with the interface (e.g., Head et al.).
The result will be a set of concrete software artifacts and an understanding of how these new interactions better support learning and reuse of code.

## Any Unique Materials Needed

* Access to the student programmer population
* Pilot studies of the program
* Time to work with corpuses and online examples
* Undergraduate student programmers to develop and maintain the code
* Access to student programmer groups in upper division courses
* Additional research into machine learning techniques and data mining (which I'm already in the midst of)

## Potential of Work to Advance Understanding within Science

Surprisingly little is known about these questions.
Recent work has shown reliance on example reuse for end-user programmers (Brandt), as well as hurdles and strategies for and non-programmers (Ichinco).
It is clear from my experience debugging code with students as a student instructor that reuse occurs frequently in the upper division CS classroom, and that hastily pasted code is the cause of confusion and errors.
From speaking with other professors, this is no uncommon occurrence.
While a large body of work in CS Education has proposed and evaluated curricula (CS1), assignments (John DeNero), and textbook examples (Borstler et al.), the online code example is an important learning resource that we don't understand.

The work we produce here will be disseminated by three major means.
Insights gathered about the challenges and strategies of programmers reusing code will be disseminated among the end-user and novice programmer communities at conferences including CHI and VL/HCC.
The systems, interventions, and techniques we generate will be instantiated in software artifacts and published at UIST, the premier conference in novel user interface technology.
Finally, all programming tools developed will be made open source and available for immediate public use.

## Potential for Broader Impacts within Society

Learning new computer science skills "on the job" is a core competency for both professional computer science practitioners (Exter &amp; Turnage) and end-user programmers in a variety of professions (Dorn & Guzdial).
As online snippets increase in quality, it is critical that we understand the .
Developing solid mental models is one of the great challenges of taking on new work as a software engineer.
When online examples threaten to obviate the need for the right mental models to get work done, it is important that we understand the learning opportunities that are missed, the software mistakes that are introduced, and the next generation of systems that can better support the development of these mental models and responsible reuse of code.
This research will produce both this critical understanding, and will evaluate a newly-developed set of interactions to support programmers' increased reliance on the web for programming information seeking.
I have already gained interest from faculty members in the Berkeley department for conducting a lecture on responsible code reuse that could come a result of the proposed research.

## A Revised Outline I

There has been tons of research on resources to support student programmers via textbooks, MOOCs, lectures, and assignments.
However, mystifyingly little is known about the *precise causes* of frustration and mistakes when programmers work in the wild, that is, problem-solve with the aid of online resources.
There is no question that student programmers do this.
Existing studies of programmers in academic settings with academic participants feature programmers who are clearly comfortable searching online.
This work has offered anecdotal evidence of mistakes made when adapting code examples for end-user programmers (reference Brandt, Stylos, etc.)

This is important for two reasons:
First, it ensures greater academic success.
Second, it improves the ability of programmers to understand and reuse code in the future, and overcome design barriers.
Third, it prepares them for their future jobs, which may involve a large amount of code reuse (information on how SE reuse code, Learning on the Job)

Where there is a strong need is in developing an understanding of the exact **cognitive causes** where programmers make mistakes reusing examples from the web, the rate at which these occur, and their severity in terms of insurmountable barriers, time lost, and grades or professional state affected.
This work seeks to develop a strong, principled, observation and experiment-based understanding of the precise errors that cause students to make errors when reusing code.
Furthermore, it seeks to understand representations of code that can best suit programmers' information needs (Pirolli...) in the moment.

This work will focus on such-and-such studies, building on such-and-such theory.
We are interested in the following questions:
* How do note-taking techniques with code influence influence ability to respond to the understanding and design barriers?
* How can we code the classes of errors that programmers encounter on the web (talk about coding)
* What is the trade-off of attention, engagement, and learning outcomes for representations for code?

Experimental work will involve (observation of software engineering teams in Berkeley's UI Design course and software engineering course), in-lab studies with pre-planned reuse tasks using both high- and low-quality crowd documentation with both open-ended and close-ended tasks.

We are deeply interested in the representations that will help programmers to problem-solve best.
This work has been pursued by the Idea Garden.
A major platform I have already built is the perfect test-bed for testing these theories.
It is called Tutorons, and enables the automatic detection and markup of online code.
We can test our, as well as run in-the-wild deployments to monitor time of viewing the examples, whether copying and pasting occurs after viewing the examples, and so on.
Such a plugin may easily fit into the development environments (Android Studio) or the web, used in the current CS160 UI design course.
Interesting questions include additive comments, and integrating with problem-solving strategies.

The findings from this work can be applied to build better end-user programming systems and systems for professional programmers too.

The upshot: We need statistics about in-the-wild programming information seeking for students about causes and effects.  We need tools to support them too.  We have the interest in producing the first, and the ability to produce the second one, too.

Pressing questions:
* Potential to introduce security loopholes
* Introduction of bugs into production code based on the project pursued
* Opportunities for mental model-building when developing code
* Interventions to improve programmers' ability to engage with and learn from code
* How often is code reused, pointing to long-standing bugs or errors?
* How often is code reused from repositories that are non-commercial?  Personal?  That don't have tests?  That are made by one developer?

### Study sheet

SIGCSE, Learning@Scale, ICPC, ICSE
* Students coding as a Bricolage
* Point to state of the art of current CS instructional material

Science Education
* Student engagement with materials and tendencies to skim

CHI, VL/HCC
* Challenges in reusing code
    * Brandt a: programmers work near the example
    * Brandt b: code satisficing to move quickly
    * Kim et al.: personal reuse of code
    * Ichinco: in visual environment, critical moments (this is a great overview)
    * Dorn & Guzdial: a feeling of "getting nowhere"
    * Pragmatic Programmer: bugs come with code
* Points to:
    * Overly verbose code
    * Tendency to skip well-supported practices
    * Potential bugs

Automated Hints and Explanations
* AutomataTutor
* Chris Piech, Rich Bearnik, some Armando

## Revisions

Jingtao's suggestions:

* Tie this into some larger, agreeable societal problem.  For example, STEM enrollments have been decreasing in recent years, perhaps due to student perception of the difficulty of the curriculum.  Will this form of documentation improve enrollments?
* Feel free to shoot high, towards a dream that may or may not be achieved (ambitious, and *perhaps* unrealistic)
* Take a top-down approach.  The systems follow from the dream, and not the other way aroud.  Unify all three of the projects under a dream.
* Consider adding in a mid-term goal to give the direction more definition
* Make sure to differentiate your own focus from Bjoern's, his co-authors', and Peggy's, who all work on similar problems.  Explain why your solution is unique and worth pursuing

My suggestions:

* Make sure that the research findings are relevant and important to a Human-Computer Interaction researcher.  This may require spelling out the point.

## Title: Building Context-Relevant, Summative Forms of Programming Documentation to Support Opportunistic Development

## Background

<!-- * A growing presence of crowd documentation supports opportunistic development practices -->
* Opportunistic development is...
* There are risks of of this type of development---programmers focus on examples and trial and error when programming
* A lack of vested attention in documentation is no surprise to any of us.  This is a problem that has been studied well when Carroll proposed minimal instruction (199.).  It is also encapsulated by Alan Blackwell's Attention Investment model (2006), which describes how end user programmers (those programming for personal purposes) carefully way the costs of engineering activity against the speed of their perceived benefits (2006).  Good software engineering principles often lose in this assessment.

* The presence of online documentation provides new opportunities to both build adaptive documentation that is in-situ for web-based programming information seeking, and that builds on this documentation as a source.
* Anecdotally, this is a trend I have seen increasingly in the classroom.  If programmers unfamiliar with code cannot be compelled to work with documentation, they will miss out on critical learning opportunities to familiarize themselves with the code that they will inevitably need to debug.  Thorough code understanding is a skill programmers must learn before becoming professionals.

* **The purpose of this work is to develop more context-relevant, summative, rapid-access forms of programming documentation that fit directly into fast-paced opportunistic development practices**.  The ultimate goal of this work to enable rapid development of reliable software for end user programmers.

## Proposed Research

* I hypothesize that context-relevant, summative programming documentation for opportunistic development can help in the following two ways:
    * by decreasing the effort to develop solutions to problems that involve unfamiliar software or hardware components
    * by improving users' understanding of unfamiliar libraries

* I propose three systems to embody the ideas context-relevant, summative documentation.  It is my intent to use these systems to demonstrate the technical work needed to produce context-relevant documentation, and it's potential benefits to the opportunistic developer.  One of these systems has been built and results presented at VL/HCC 2015, a conference on end user programming.  A prototype for the other two have been built, and must undergo further development and evaluation.

* Tutorons: context-relevant descriptions of online code.  Programmers may encounter syntax that they don't understand in web tutorials, as an author assumes the audience's prerequisite knowledge.  A Tutoron is a server-side routine that can detect code examples from arbitrary HTML for tutorial pages, parse them, and automatically synthesize English prose, diagrams, and usage examples.  By navigating in a web browser connected to Tutorons with plugins we provide, programmers can view context-relevant explanations of high-level intent of code and its low level syntax.  An initial in-lab usabiliity study has shown that such adaptive explanations can reduce accesses to external documentation on the Web (Fisher's exact test, n = 9, p &lt; .01).

* StackSkim: visual search interface for exploring and selecting code from large collections of similar code examples.  It is often the case that there are many tutorials or code examples that can satisfy a programmer's information need.  StackSkim provides a visual interface to StackOverflow, a popular programming Q&A site with more than 10,000,000 questions, that enables programmers to skim the most popular classes and programming structures used in collections of dozens of related answers to their questions.  While a preliminary usability study revealed positive qualitative feedback, we have not yet applied this to two challenges I believe to be critical for opportunistic developers: (1) highlighting design differences between snippets such as varying approaches and the rationale in the accompanying text. (2) enabling interleaved inspection of instructional examples to real code, the latter which may reveal more realistic exception handling.  The primary technical contribution for both of these steps will revolve around comparison of pre-parsed code examples from the relatively clean repositories of example and production code on StackOverflow and Github, respectively.

* CodeConverter: when developing opportunistically, programmers have a set of go-to tools they rely on to get work done (Brandt et al. 2008).  While langauges may share similar concepts, some have key libraries for performing certain tasks that others don't.  This project proposes an experimental simultaneous method of opportunistic programming langauge learning and application.  With CodeConverter, programmers will be able to program simple statements of one language and see them converted to a new language with accompanying description describing how the code's use varies from typical the source language and how it must be modified.  The evaluation will focus on having programmers from a local hackerspace develop code for an embedded platform with an unfamiliar language but with familiar tasks.  While past work has shown machine translation of programming languages (e.g., ), our contribution will not be in this space, but rather in establishing that for a simple subset of common patterns, programming can be enabled for new platforms on familiar tasks, with improved conceptual knowledge through automatically-generated inline comments instead of external documentation.

# Brainstorming
 
## Evaluation techniques

* Build something new with the tool (d.tools, Drill Sergeant, MixT, Sauron, Midas, Tutorons)
* Have people do work with the interface (DigitalDesk, Telepresence, SceneSkim, NIME, Soylent, Drill Sergeant)
* Collect ratings on the creative works produced (BluePrint, Video Digests, Underscore, Automatically Detecting)
* Observer accuracy of the technology in performing some task (Lamello, Phrase-Based)
* Try it out yourself and make observations (Tangible Bits)

## Observation techniques

* Observe people doing work in a controlled in-lab task (Two Studies, Exploring Example, Tutorons, MHP, Unfamiliar APIs, Selection-based, Reuse, Fitts' Law, Design Right, User Technology, Parallel Prototyping, Lost While Searching, Taxonomy of Errors, End-user Debugging)
* Cluster freely available online behavior information (Personality, Uncovering Trajectories, Tie Strength)
* Observe artifacts, make models and classify (Morphological, Tutorial Authorship, Good Code Example)
* Ask programmers to describe their work habits (Small Matter, Learning on the Job, Opportunistic)
* Split classroom with comparative conditions (Compositions, OEV, Coding with Intention)
* Conduct survey about work habits (Mental Models, Who/What/How, Issue)
* Perform data processing on a large dataset (Design Lessons, Crowd Documentation)
* Observe programmers programming in the wild (Opportunistic, Ethnographic Study)
* Recording and analyzing creative output (Ethnographic Study, Nonoriginal Content)
* Observe the questions you are asked as tech support (Six Barriers, Idea Garden)
* Large-scale controlled experiments and log analysis (Practical Guide, Example-Centric)
* Ask programmers to show you their workspaces (Opportunistic)
* Review themes and findings across multiple disciplines (How Bodies Matter)

# Ethos planned out

* Decorum
    * This work builds on past insights
    * Rigorous methods are necessary to make substantial claims
* Virtue
    * Opportunistic programming is precisely the type of programming often exhibited by people working technology into their lives without a formal profession (Lost While Searching, Brandt's first study)
    * The body of end user programmers is huge (Scaffidi)
    * Opportunistic programming problems may lead to unexpected system performance.  In a qualitative study, it has been observed to result in more work after the fact despite lower up-front cost (Brandt)
* Craft
    * Tutorons progress: Honorable Mention at VL/HCC 2015, a major conference in end-user programming
    * StackSkim progress: a research prototype built and tested through a first iteration
* Disinterest
    * The StackSkim project is yet a prototoype.  There are limitations to building these tools for a source like StackOverflow that frequently have one best answer
    * It is true that much of this work is motivated by recent insights by Brandt
