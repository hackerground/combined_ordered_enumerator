combined_ordered_enumerator
===========================

The file contains some tests. You know the drill. Fork the code. Make the tests pass. 
Send a Pull Request. Go celebrate with a beer :)

The aim of this class is to take a number of ordered enumerators and then 
emit their values in ascending order.

Some assumptions:
  * The enumerators passed in emit their values in ascending order.
  * The enumerators emit values which are Comparable[1] with each other.
  * The enumerators can be finite *or* infinite.

This requires Ruby 1.9. The Enumerator[2] documentation might be useful.

[1] http://www.ruby-doc.org/core-1.9.3/Comparable.html
[2] http://www.ruby-doc.org/core-1.9.3/Enumerator.html

This is a stub implementation that causes failures in in the test suite, but
no errors.

You can run the test suite with: `ruby combined_enumerator.rb`.
