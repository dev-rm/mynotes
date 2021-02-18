## The keyword super

- it's used to access the overriden method of the super class from the subclass
- it's also used to invoke the superclass constructor
- the syntax is:
  `super()`
  or
  `super(parameter list)`

- the superclass constructor invocation must be the first line in the subclass constructor
  > Note: If a constructor does not explicitly invoke a superclass constructor, the Java compiler automatically inserts a call to the no-argument constructor of the superclass. If the super class does not have a no-argument constructor, you will get a compile-time error. Object does have such a constructor, so if Object is the only superclass, there is no problem. [^1]

  [^1]: https://docs.oracle.com/javase/tutorial/java/IandI/super.html
