# Fragile Base Class Problem

- [fundamental architectural design problem with inheritance in Object Oriented Programming systems][1]
- the base classes (superclasses) are "fragile" as modifications to the superclass may break the subclasses (derived classes)
- It is hard to determine from the base class if the modifications made to it are safe just by examining the methods of the base class in isolation.
- The solution is to use Composition (has-a) instead of Inheritance (is-a).
- The other way is to use the "final" keyword when declaring a class in Java to prevent it from being inherited.
- [This] explains the Fragile Base Class problem with an appropriate example.

[1]: <https://en.wikipedia.org/wiki/Fragile_base_class>
[This]: <https://dzone.com/articles/problems-with-inheritance-in-java>