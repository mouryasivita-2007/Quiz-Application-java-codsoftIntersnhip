# Quiz-Application-java-codsoftIntersnhip
Quiz Application with timer developed  using java in vs studio as a part of internship at codsoft

# Quiz Application with Timer (Java)

**Name:** SIVITA MOURYA  
**Company:** CODSOFT  
**Domain:** Java Programming  
**Duration:** August 2026 – September 2026  

## Overview of the Project

The objective of this project is to develop an interactive **Quiz Application using Java**. The application presents multiple-choice questions with four options and provides a **10-second time limit for each question**.

This project focuses on strengthening Java concepts such as **arrays, 2D arrays, input validation, multithreading, ExecutorService, Future, exception handling, and score calculation** while creating an interactive and time-based quiz system.

## Key Activities

### 1) Planning & Designing
- Designed the quiz flow and question structure.
- Planned arrays and 2D arrays for storing questions and options.
- Decided the scoring, timing, and result calculation logic.

### 2) Implementation
- Created multiple-choice questions with four options.
- Stored correct answers using an integer array.
- Implemented user input and input validation.
- Added correct and incorrect answer feedback.

### 3) Timer & Multithreading
- Implemented a **10-second time limit** for each question.
- Used `ExecutorService` for multithreading.
- Used `Future` to handle user input within the time limit.
- Added per-question time calculation.
- Handled `TimeoutException`, `InterruptedException`, and `ExecutionException`.

### 4) Result & Interface Enhancement
- Calculated correct, wrong, and unanswered questions.
- Calculated the final score and percentage.
- Displayed total quiz completion time.
- Added performance feedback based on the score.
- Enhanced the console interface using ANSI color formatting.
- Shut down the thread pool after quiz completion.

### 5) Testing & Debugging
- Tested correct and incorrect answers.
- Tested invalid inputs outside the 1–4 range.
- Tested unanswered questions and timeouts.
- Verified score, percentage, and timing calculations.
- Debugged exceptions and improved the overall program flow.

## Technologies Used

1) **Java:** Used for implementing the quiz logic, arrays, input handling, multithreading, timing, and result calculation.

2) **ExecutorService & Future:** Used to implement time-limited user input and multithreading.

3) **VS Code / IntelliJ IDEA / Eclipse:** Used for writing, compiling, testing, and executing the application.

## Features

- Multiple-choice quiz with four options.
- Questions and options stored using arrays and 2D arrays.
- Correct answers stored using an integer array.
- Input validation for options from 1–4.
- Correct and incorrect answer feedback.
- Displays the correct answer for incorrect responses.
- 10-second time limit for each question.
- Per-question time calculation.
- Multithreading using `ExecutorService`.
- Time-controlled input using `Future`.
- Exception handling for timeout and thread-related errors.
- Calculates score, percentage, correct, wrong, and unanswered questions.
- Displays total quiz completion time.
- Provides performance feedback based on score.
- ANSI color-coded console interface.
- Proper thread-pool shutdown after quiz completion.

## Output Example

Question and four options are displayed → User selects an answer within 10 seconds → Program validates the input and provides feedback → Score and time are recorded → After all questions, the final score, percentage, answer statistics, completion time, and performance feedback are displayed.

## Learning Outcome

This project improved my understanding of **Java arrays, 2D arrays, input validation, multithreading, `ExecutorService`, `Future`, exception handling, and time-based program execution**. It also helped me learn how to combine multiple Java concepts to build a more interactive and efficient application.
