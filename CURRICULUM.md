# Curriculum

My goal is to strengthen my foundations in software development and understand the AI systems I use. This plan combines coursework with programs I can write, test, explain, and improve independently.

The first three months build toward a working Python application. Months four through six extend that work through machine learning or web development. The sequence is flexible, and I'll adjust the pace based on what I can demonstrate independently.

## Current starting point

- **In progress** — KodeKloud's GIT for Beginners.
- **Next** — Zero To Mastery's Complete Python Developer.
- **Early AI study** — Zero To Mastery's How LLMs Work.

Checkboxes below track work I have demonstrated. Course completion and independent practice will be recorded separately in my notes.

## Study rhythm

When work is slow, I may have four to eight hours available in a day. A typical four-hour session will include about one hour of coursework, one hour of guided practice, and two hours of independent coding. Additional time can go toward experiments, tests, reading, and revisiting earlier problems.

Each week, I'll review one piece of code and explain how it works, attempt a variation without following the lesson, and record what I need to practice next. At the end of a session, I'll leave a short note with the next step so I can resume on either MacBook.

## Learning with AI

- Make an attempt and identify the specific difficulty before asking for help.
- Use explanations, hints, review, and additional exercises to deepen understanding.
- Check suggestions against documentation, tests, and observed behavior.
- Record substantial AI assistance and revisit the relevant code independently.
- Identify guided course exercises and independent work in project notes.

## First milestone — Git and a repeatable workflow

Complete the course I have already started, with particular attention to branches, remotes, pull requests, fetching, pulling, and conflicts. [KodeKloud — GIT for Beginners](https://kodekloud.com/courses/git-for-beginners/)

- [ ] Finish the course and its exercises.
- [ ] Explain the difference between a local commit, a pushed branch, and a pull request.
- [ ] Create a branch, commit a small change, push it, and merge a PR independently.
- [ ] Bring the merged changes into my local checkout.
- [ ] Resolve a deliberate merge conflict in a practice exercise.
- [ ] Clone this repository on both MacBooks and practice pulling before work and pushing afterward.

**Evidence to keep** — My own command notes, a practice PR, and a short explanation of a conflict and how I resolved it.

## Month 1 — Python foundations

Use Complete Python Developer as the main programming course. Focus on variables, conditions, loops, lists, dictionaries, functions, modules, virtual environments, files, error handling, debugging, and testing. Practice object-oriented programming as the course introduces it. [ZTM — Complete Python Developer](https://zerotomastery.io/courses/learn-python/)

Use Python Basics for additional exercises when I need more repetition on a particular concept. [KodeKloud — Python Basics](https://kodekloud.com/courses/python-basics)

Study tokens, next-token prediction, transformers, training, and model limitations alongside the programming work. [ZTM — How LLMs Work](https://zerotomastery.io/ai/courses/how-llms-work/)

**Project** — Build a command-line tool that reads fictional support tickets from a CSV file and lists open tickets by priority. The project will evolve over the following months.

- [ ] Write the first version from a blank file using functions, lists, and dictionaries.
- [ ] Load tickets from a CSV file and add a priority filter.
- [ ] Handle empty input, missing fields, and malformed rows deliberately.
- [ ] Write tests for expected output and at least one failure case.
- [ ] Diagnose a failure using the traceback and a small reproduction.
- [ ] Rebuild a smaller version independently and explain my choices.
- [ ] Explain training and inference, and why a fluent model response can contain errors.

**Evidence to keep** — Source code, sample data, tests, run instructions, and a reflection on one bug I understood and fixed.

## Month 2 — Databases and APIs

Start with tables, primary and foreign keys, CRUD operations, filtering, joins, and database design. Use the labs to practice these ideas with a real database. [KodeKloud — Database Fundamentals](https://kodekloud.com/courses/database-fundamentals)

Use selected SQL fundamentals, joins, grouping, and database-design exercises for deeper practice as the project needs them. [ZTM — Complete SQL + Databases Bootcamp](https://zerotomastery.io/courses/sql-bootcamp/)

Then work through Python setup, FastAPI Basics, Working with Databases, Databases with Python, and relevant Testing lessons. Learn how HTTP requests, status codes, validation, and JSON responses fit together. [KodeKloud — Python API Development with FastAPI](https://kodekloud.com/courses/python-api-development-with-fastapi)

**Project** — Extend the ticket tool with a database and a small API.

- [ ] Model tickets and their updates as related tables.
- [ ] Query open tickets by priority and retrieve a ticket's history.
- [ ] Build endpoints to list tickets and retrieve one ticket by ID.
- [ ] Validate incoming data and return a useful response for a missing ticket.
- [ ] Test an existing ticket, a missing ticket, and a ticket with no updates.
- [ ] Explain how a request travels through the application to the database and back.
- [ ] Document setup, database initialization, and example requests.

**Evidence to keep** — Schema, queries, API code, tests, and a worked request showing each step through the application.

## Month 3 — AI applications and evaluation

Begin after I can write Python functions, use modules, and interpret JSON responses. Select the sections on virtual environments, Requests and Pandas, LLMs and APIs, Python API calls, and prompting. Choose one model provider for the initial implementation. [ZTM — AI Engineering: Building AI Applications](https://zerotomastery.io/courses/ai-application-development/)

Use the CLI, REST API, and application labs to explore a local model. This gives me an option for project experiments without per-call inference charges. [KodeKloud — Running Local LLMs With Ollama](https://kodekloud.com/courses/running-local-llms-with-ollama)

**Project** — Add a ticket handoff summary that identifies the issue, latest action, and unresolved questions from the supplied history.

- [ ] Call a model from Python and handle a failed request.
- [ ] Define the facts a good summary must preserve for ten fictional tickets.
- [ ] Evaluate summaries for preserved facts, omissions, and invented details.
- [ ] Include incomplete and contradictory histories in the examples.
- [ ] Change one part of the implementation and compare results on the same examples.
- [ ] Record the model, settings, prompts, and evaluation results.
- [ ] Explain where the feature helps and where human review is needed.

**Three-month milestone** — Another person can follow the README, run the application, and try a sample ticket. I can trace its behavior, explain its limitations, and implement a small change independently.

## Months 4–6 — Extend the foundations

At the three-month review, choose a main direction based on what I enjoyed and what needs more practice. Machine learning is the proposed starting preference. The web-development direction is available if building interfaces becomes the stronger interest.

### Direction A — Machine learning

Focus on the introductory machine-learning workflow, Pandas, scikit-learn, classification, and evaluation sections. Learn training and test splits, overfitting, and appropriate evaluation metrics. [ZTM — Complete A.I. Machine Learning and Data Science](https://zerotomastery.io/courses/machine-learning-and-data-science-bootcamp/)

**Months 4–5 project** — Build a ticket-category classifier using labeled examples. Compare it with a simple keyword rule. Keep test examples out of training and tuning, and inspect errors to understand what each approach misses.

- [ ] Prepare a labeled dataset and describe its limitations.
- [ ] Train a simple classifier and compare it with the keyword baseline.
- [ ] Report results on held-out examples with suitable metrics.
- [ ] Explain false positives, false negatives, and the effect of uneven category sizes.
- [ ] Write a recommendation supported by the results.

### Direction B — Web development

Focus on HTML, CSS, JavaScript fundamentals, and browser requests before building a small interface for the Python API. [ZTM — Complete Web Developer](https://zerotomastery.io/courses/coding-bootcamp/)

- [ ] Build an interface for viewing tickets and requesting summaries.
- [ ] Handle loading, empty results, and request failures visibly.
- [ ] Explain the request and response between browser and API.
- [ ] Observe someone completing a task and improve one confusing interaction.

### Month 6 — Independent project and review

Build a new, small project or a substantial extension based on the chosen direction. Write a brief problem statement before implementation and keep a record of design decisions, tests, and assistance used.

- [ ] Deliver a runnable project with setup instructions and sample input.
- [ ] Demonstrate its behavior and explain the main implementation decisions.
- [ ] Record a meaningful failure and how I investigated it.
- [ ] Ask someone to try it and address useful feedback.
- [ ] Review my progress against the original goals and plan the next learning cycle.

## Readings and reflections

Reading will run alongside the technical work. My notes will connect specific arguments to questions about learning, human agency, and how I choose to use AI. I'll record reading progress and questions separately from course progress.

- **Finished** — Ethan Mollick, *Co-Existence*.
- **In progress** — Kevin Roose, *The AGI Chronicles*.
- **In progress** — Jill Lepore, *The Rise and Fall of the Artificial State*.
- **Also informing my thinking** — Gil Durán, *The Nerd Reich*.

## Recording progress

For each substantial exercise or project, keep the problem, my approach, how I checked the result, help I used, and what I can now do independently. Course names and links will identify the source of guided work.

At each monthly review, update the checkboxes with links to evidence as it becomes available, identify gaps, and adjust the next month's scope. The dates and pace may change as work demands and learning needs become clearer.
