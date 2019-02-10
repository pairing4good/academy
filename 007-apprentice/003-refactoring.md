# Refactoring

## Discover
-  watch
   - [![YouTube](https://i.ytimg.com/vi/D4auWwMsEnY/default.jpg)](https://www.youtube.com/watch?v=D4auWwMsEnY) **(The first 14 minutes)
   - [![YouTube](https://i.ytimg.com/vi/RiRrcCUyn4M/default.jpg)](https://www.youtube.com/watch?v=RiRrcCUyn4M)
- Read chapters 4, 5 & 6 in Extreme Programming Explained (http://a.co/d/5RExPZU)

## Apply
- Create User Stories http://agilekatas.co.uk/katas/RockPaperScissors-Kata stories (green) on your Trello Board in the "To Do" List.
- Move each story from "To Do" to Doing when you start working on it.  Then move it to "Done" once you complete the story.
- Commit to Git every Red -> Green -> Refactor cycle.
- Once you’ve Test Driven your code, create a video demonstration of your working code.

## Extra
- Site: https://github.com/pairing4good/java-koans
- Complete
  - AboutConstructors
  
## Turn In Your Assignment
- Add a link to your Trello Board
- Add a link to your GitHub repository
- Add links to your story demo videos

## Walkthrough
- Kata [![YouTube](https://i.ytimg.com/vi/5oE1Itmmhtc/default.jpg)](https://www.youtube.com/watch?v=5oE1Itmmhtc)
- Koan [![YouTube](https://i.ytimg.com/vi/lXtFg4TEOaM/default.jpg)](https://www.youtube.com/watch?v=lXtFg4TEOaM)

## Resources
- https://refactoring.guru/refactoring

## Key Concepts
1. Code Smell: any characteristic in the source code of a program that possibly indicates a deeper problem.
1. Bloaters: code, methods and classes that have increased to such gargantuan proportions that they’re hard to work with. 
   1. Long Method: A method contains too many lines of code. Generally, any method longer than ten lines should make you start asking questions.
   1. Large Class: A class contains many fields/methods/lines of code.
   1. Data Clumps: Sometimes different parts of the code contain identical groups of variables (such as parameters for connecting to a database). These clumps should be turned into their own classes.
   1. Long Parameter List: More than three or four parameters for a method.
   1. Primative Obsession
      1. Use of primitives instead of small objects for simple tasks (such as currency, ranges, special strings for phone numbers, etc.)
      1. Use of constants for coding information (such as a constant USER_ADMIN_ROLE = 1 for referring to users with administrator rights.)
      1. Use of string constants as field names for use in data arrays.
1. Object-Orientation Abusers: All these smells are incomplete or incorrect application of object-oriented programming principles.
   1. Switch Statements: You have a complex switch operator or sequence of if statements.
   1. Temporary Field: get their values (and thus are needed by objects) only under certain circumstances. Outside of these circumstances, they’re empty.
   1. Refused Bequest: If a subclass uses only some of the methods and properties inherited from its parents, the hierarchy is off-kilter. The unneeded methods may simply go unused or be redefined and give off exceptions.
   1. Alternative Classes with Different Interfaces: Two classes perform identical functions but have different method names.
1. Change Preventers: These smells mean that if you need to change something in one place in your code, you have to make many changes in other places too. Program development becomes much more complicated and expensive as a result.
   1. Divergent Change: You find yourself having to change many unrelated methods when you make changes to a class. For example, when adding a new product type you have to change the methods for finding, displaying, and ordering products.
   1. Shotgun Surgery: Making any modifications requires that you make many small changes to many different classes.
   1. Parallel Inheritance Hierarchies: Whenever you create a subclass for a class, you find yourself needing to create a subclass for another class.
1. Dispensables: something pointless and unneeded whose absence would make the code cleaner, more efficient and easier to understand.
   1. Comments: A method is filled with explanatory comments.
   1. Duplicate Code: Two code fragments look almost identical.
   1. Lazy Class: Understanding and maintaining classes always costs time and money. So if a class doesn’t do enough to earn your attention, it should be deleted.
   1. Data Class: A data class refers to a class that contains only fields and crude methods for accessing them (getters and setters). These are simply containers for data used by other classes. These classes don’t contain any additional functionality and can’t independently operate on the data that they own.
   1. Dead Code: A variable, parameter, field, method or class is no longer used (usually because it’s obsolete).
   1. Speculative Generality: There’s an unused class, method, field or parameter.
1. Couplers: All the smells in this group contribute to excessive coupling between classes or show what happens if coupling is replaced by excessive delegation.
   1. Feature Envy: A method accesses the data of another object more than its own data.
   1. Inappropriate Intimacy: One class uses the internal fields and methods of another class.
   1. Message Chains: In code you see a series of calls resembling $a->b()->c()->d()
   1. Middle Man: If a class performs only one action, delegating work to another class, why does it exist at all?
1. Favor composition over inheritance
1. Inheritance: enables new objects to take on the properties of existing objects. This is a "Is a" relationship.
1. Composition: a way to combine objects or data types into more complex ones. This is a "Has a" relationship
1. The four XP values
   1. Communication
   1. Simplicity
   1. Feedback 
   1. Courage
1. XP principles
   1. Humanity: balancing individual and team needs
   1. Economics: built on the time value of money and the option value of systems and teams
   1. Mutual benefit: "the most important XP principle and the most difficult to adhere to"
   1. Self-similarity: make the small echo the large (and vice versa)
   1. Improvement
   1. Diversity
   1. Reflection
   1. Flow: from lean manufacturing, not from psychology – deliver a steady flow of value by engaging in all development activities simultaneously
   1. Opportunity: see problems as opportunities
   1. Redundancy
   1. Failure: "If you’re having trouble succeeding, fail."
   1. Quality
   1. Baby steps
   1. Accepted responsibility
