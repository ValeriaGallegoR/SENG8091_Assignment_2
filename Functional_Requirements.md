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


### 2. Categorize questions

**ASSUMPTION:**

It is assumed that the training model does not have questions categorized according to predefined topics. 

**VALIDATIONS (QUESTIONS):**

- How are the questions currently organized? Under what criteria?
-	Do you have categories and/or subcategories to classify the questions?
-	Based on the history of questions, what are the most common topics?
-	Have you previously tried to implement categorization of questions? If so, how did you do it and what was the result?

**PRELIMINARY TASKS:**
- [ ] Gather information about how the questions are currently classified.
- [ ] Define which are the most relevant topics among the questions asked.
- [ ] Based on the relevant topics, determine the categories and/or subcategories to classify the questions.
- [ ] Implement a system for automatic and manual categorization of questions.
- [ ] Determine the storage format of the questions according to the category and/or subcategory to which they belong.
- [ ] Integrate the categories into the training model.
- [ ] Evaluate if it is possible to implement a search motor to speed up the process of searching for questions.
- [ ] Analyze possible improvements to the process

**REQUIREMENTS:**

**REQ_02:**

**As** AI developer

**I want** categorize training questions according to predefined topics

**To** structure the learning process in a better way and increase the accuracy of the model

- **_Task2_01:_** Define a clear and structured list of topics to categorize questions.

- **_Task2_02:_** Ensure that the model classifies questions correctly

- **_Task2_03:_** Implement a system that identifies and classifies questions automatically

**REQ_03:**

**As** AI developer

**I want** to store questions by category

**To** optimize the search for relevant questions by each category

- **_Task3_01:_** Implement a system that organizes and stores the questions in a searchable and efficient way.

- **_Task3_02:_** Integrate a search motor according to the category of each question.

- **_Task3_03:_** Develop a graphical interface to efficiently search questions by category.