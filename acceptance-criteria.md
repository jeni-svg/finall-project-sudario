# Acceptance Criteria
<!--
Acceptance criteria tell you when a user story is DONE. Each one must be testable: pass or fail.
Write 2–3 criteria for every user story using this format:

Given [a situation], when [the user does something], then [this should happen].

Tips:
- Number them under their story: AC1.1 and AC1.2 belong to US1.
- Describe what the user SEES, not how the code works.
- Include at least one "what if it goes wrong" case per story (empty input, no results).
- Avoid vague words like "fast," "nice," or "easy." Could a classmate test it and agree it passed?

Example:
## US1: View today's menu
- AC1.1: Given I open the App page, when it loads, then I see each dish with its name, photo and price.
- AC1.2: Given no dishes are added yet, when I open the menu, then I see "No dishes today yet."

AC - Acceptance Criteria
-->

### Feature: Note
US1:
- AC1.1:  Given I am on the Notes page, when I enter text in the note area and click "Save", then I see my note in the "My Notes" list, and it remains visible even after reloading the page.
- AC1.2: Given I have a saved note, when I click "Edit" and save my changes or click "Delete", then the note is updated or removed from the "My Notes" list.
- AC1.3: Given the note area is empty, when I click "Save", then I see a message telling me to enter text before saving.

### Feature: Question Management
US2:
- AC2.1: Given I am on the Create Question page, when I select "Multiple Choice" or "Identification", enter the question and correct answer, and click "Save", then I see the saved question with its details under "My Questions".
- AC2.2: Given I have saved questions under "My Questions", when I click "Edit" and save my changes or click "Delete", then the question is updated or removed from the list.
- AC1.3: Given I have not entered the required question or correct answer, when I click "Save", then I see a message asking me to complete the required fields, and the question is not saved.

### Feature: Interactive Quiz Practice
US3:
- AC3.1: Given I have saved custom questions, when I click "Start Quiz", then I see one question at a time in randomized order with the appropriate answer controls and a "Next Question" button.
- AC3.2: Given I am answering quiz questions, when I select an answer and click "Next Question", then I proceed to the next question until all questions have been answered.
- AC1.3: Given I have completed the final question, when I finish the quiz, then I see the Quiz Result screen displaying my score, number of correct and wrong answers, and a review showing my selected answers alongside the correct answers.
