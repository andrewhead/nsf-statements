# Outline

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