## FUNCTIONAL REQUIREMENTS

> [!IMPORTANT]
> Since three different concerns are identified that the AI developer is presenting: Separating questions from answers, Categorization of questions and Ensure that the data > used is “balanced”; the requirements will be broken down considering these issues.

### 1. Separate questions and answers

**ASSUMPTION:**

Assume that the training model does not currently have a separate question and answer structure.

**VALIDATIONS (QUESTIONS):**
-	Describe how the training model is currently managed
-	Are the questions separated from the answers?
-	How do you differentiate questions from answers? Explain how you identify and what format you use.
-	What are the criteria for separating questions from answers?
-	How to identify that the answers correspond to the questions?
-	Have you previously tried to implement this mechanism? If so, how did you do it and what was the result?

**PRELIMINARY TASKS:**
- [ ] Gather information on how questions and answers are currently handled.
- [ ] Identify what the criteria are for relating and/or separating a question from an answer.
- [ ] Evaluate a mechanism for separating questions from answers correctly.
- [ ] Determine how the questions and answers are identified.
- [ ] Compare the format used for questions and answers.
- [ ] Analyze possible improvements to the process.
- [ ] Determine the data storage format to be used, either through files or databases.

**REQUIREMENT:**

**REQ_01:** 

**As** AI developer
**I want** separate training questions from answers
**To** facilitate the ability to evaluate and validate knowledge thus identifying areas for improvement.

- **_Task1_01:_** Define a format for storing data organized in such a way that questions and answers are separated.

- **_Task1_02:_** Establish a mechanism to link the questions with the correct answers.

- **_Task1_03:_** Develop a graphical interface to manage the questions and answers
