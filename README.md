# Ruby Accessor Method Bug

This repository demonstrates an uncommon bug in Ruby related to how accessor methods behave when only a getter method is defined.  Direct assignment to the accessor method does not modify the internal instance variable.

The `bug.rb` file shows the unexpected behavior, and `bugSolution.rb` demonstrates a fix by adding a setter method.