# Unexpected Assignment Behavior in Ruby Method Calls

This repository demonstrates an uncommon, yet potentially confusing, behavior in Ruby related to assignments within method calls that also return a value.  The example showcases how assignment modifies the object's internal state and the method call itself returns the assigned value.

This is not necessarily a bug, but rather an aspect of Ruby's design that can lead to unexpected results if not understood.  The solution demonstrates how to explicitly manage this behavior and improve code clarity.

## How to reproduce

1. Clone this repository.
2. Run `ruby bug.rb` to observe the unexpected behavior.
3. Run `ruby bugSolution.rb` to see how the behavior can be addressed.