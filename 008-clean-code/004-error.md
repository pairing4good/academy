# Error Handling

## Discover
-  watch attached video [![YouTube](https://i.ytimg.com/vi/G9kTo7QVScc/default.jpg)](https://www.youtube.com/watch?v=G9kTo7QVScc)
- Read chapters 6, 7 & 8 in Clean Code (http://a.co/d/c31QNpN)

## Apply
- Create User Stories http://codekata.com/kata/kata04-data-munging/ stories on your Trello Board in the "To Do" List.
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
  - AboutAutoboxing
  
## Resources
- https://en.wikipedia.org/wiki/SOLID

## Key Concepts
- SOLID Principles
   - Single responsibility principle: a class should have one, and only one, reason to change.
   - Open/closed principle: "software entities … should be open for extension, but closed for modification."
   - Liskov substitution principle: "objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program." See also design by contract.
   - Interface segregation principle: "many client-specific interfaces are better than one general-purpose interface."[4]
   - Dependency inversion principle: one should "depend upon abstractions, not concretions."
- Objects hide their data behind abstractions and expose functions that operate on that data. 
- Data structure expose their data and have no meaningful functions.
- DTO (Data Transfer Objects): a data structure that has public variables and no functions.
- Error handling is important, but if it obscures logic, it’s wrong.
- The price of checked exceptions is an Open/Closed Principle violation.
- Wrapping third-party APIs is a best practice.
- Avoid passing null in your code whenever possible.
