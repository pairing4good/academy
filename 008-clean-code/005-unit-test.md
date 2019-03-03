# Unit Tests

## Discover
-  watch
   - [![YouTube](https://i.ytimg.com/vi/-I1Yh4Q2hTM/default.jpg)](https://www.youtube.com/watch?v=-I1Yh4Q2hTM)
   - [![YouTube](https://i.ytimg.com/vi/xahwVmf8itI/default.jpg)](https://www.youtube.com/watch?v=xahwVmf8itI)
   - [![YouTube](https://i.ytimg.com/vi/qL2-5g_lJTs/default.jpg)](https://www.youtube.com/watch?v=qL2-5g_lJTs)
- Read chapters 9 & 10 in Clean Code (http://a.co/d/c31QNpN)

## Apply
- Create User Stories https://github.com/garora/TDD-Katas/blob/master/KatasReadme.md#lcd-digits- stories on your Trello Board in the "To Do" List.
- Move each story from "To Do" to Doing when you start working on it. Then move it to "Done" once you complete the story.
- Commit to Git every Red -> Green -> Refactor cycle.
- Once you’ve Test Driven your code, create a video demonstration of your working code.

## Turn In Your Assignment
- Add a link to your Trello Board
- Add a link to your GitHub repository
- Add links to your story demo videos

## Extra
- Site: https://github.com/pairing4good/java-koans
- Complete
  - AboutCollections
  
## Key Concepts
- Three Laws of TDD (Test Driven Development)
    - First Law: You may not write production code until you have written a failing unit test.
    - Second Law: You may not write more of a unit test than is sufficient to fail, and not compiling is failing.
    - Third Law: You may not write more production code than is sufficient to pass the currently failing test.
- Test code is just as important as production code.
- It is unit tests that keep our code flexible, maintainable, and reusable. The reason is simple. If you have tests, you do not fear making changes to the code!
- We want to test a single concept in each test function.
- Clean tests follow the 5 F.I.R.S.T. Rules:
    - Fast Tests should be fast. They should run quickly. When tests run slow, you won’t want to run them frequently. If you don’t run them frequently, you won’t find problems early enough to fix them easily. You won’t feel as free to clean up the code. Eventually the code will begin to rot.
    - Independent Tests should not depend on each other. One test should not set up the conditions for the next test. You should be able to run each test independently and run the tests in any order you like. When tests depend on each other, then the first one to fail causes a cascade of downstream failures, making diagnosis difficult and hiding downstream defects.
    - Repeatable Tests should be repeatable in any environment. You should be able to run the tests in the production environment, in the QA environment, and on your laptop while riding home on the train without a network. If your tests aren’t repeatable in any environment, then you’ll always have an excuse for why they fail. You’ll also find yourself unable to run the tests when the environment isn’t available.
    - Self-Validating The tests should have a boolean output. Either they pass or fail. You should not have to read through a log file to tell whether the tests pass. You should not have to manually compare two different text files to see whether the tests pass. If the tests aren’t self-validating, then failure can become subjective and running the tests can require a long manual evaluation.
    - Timely The tests need to be written in a timely fashion. Unit tests should be written just before the production code that makes them pass. If you write tests after the production code, then you may find the production code to be hard to test. You may decide that some production code is too hard to test. You may not design the production code to be testable.

