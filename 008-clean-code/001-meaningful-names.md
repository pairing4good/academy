# Test Driven Development (TDD)

## Discover
-  watch [![YouTube](https://i.ytimg.com/vi/jGVfCYlz3ZM/default.jpg)](https://www.youtube.com/watch?v=jGVfCYlz3ZM) _Uncle Bob, the author of Clean Code, speaking about the [SOLID principles](https://en.wikipedia.org/wiki/SOLID) at Yale_
- Read chapters 1 & 2 in Clean Code (http://a.co/d/c31QNpN)
- Read https://www.baeldung.com/java-final-finally-finalize

## Apply
- Create User Stories http://codekata.com/kata/kata01-supermarket-pricing/ stories on your Trello Board in the "To Do" List.
- Move each story from "To Do" to Doing when you start working on it. Then move it to "Done" once you complete the story.
- Commit to Git every Red -> Green -> Refactor cycle.
- Once you’ve Test Driven your code, create a video demonstration of your working code.

## Turn In Your Assignment
- Add a link to your Trello Board
- Add a link to your GitHub repository
- Add links to your story demo videos

## References
- https://en.wikipedia.org/wiki/SOLID

## Key Concepts
- Meaningful naming is cruitial in building clean code.
- Use Intention-Revealing Names
- The name of a variable, function, or class, should answer all the big questions.
   - why it exists, 
   - what it does, 
   - and how it is used. 
- If a name requires a comment, then the name does not reveal its intent.
- Avoid names that create disinformation.
- Use pronouncable names so that developers can easily talk about and understand the code.
- Use easily searchable names
- Avoid variable member prefixes
- Classes and objects should have noun or noun phrase names
- Methods should have verb or verb phrase names
- Choose clarity over cute or entertaining names.
- Pick a single name for each concept. Avoid using the same word for two purpose.
- Place names in context for your reader by enclosing them in well-named classes, functions, and namespaces.
- The hardest thing about choosing good names is that it requires good descriptive skills and a shared cultural background.
- We can apply the final keyword to class, method, field, variable and method parameter declarations.
- Making a class final means that it won’t be possible to extend that class
- Adding final to a method means that it won’t be possible to override that method
- Finally, putting final in front of a field, a variable or a parameter means that once the reference has been assigned then it cannot be changed
- The finally block is an optional block use with a try/catch statement that is always called even if an exception is thrown.
- And finally, the finalize method is a protected method, defined in the Object class. It’s called by the garbage collector on objects that aren’t referenced anymore and have been selected for garbage collection.
