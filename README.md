1. Izračunavanje metrike LOC
   
calculator.java - 134 LOC

start.java - 19 LOC

Zbir - 153 LOC


2. Statička analiza pomoću alata SonarQube:

calculator.java - 1 - Move this file to a named package.

calculator.java - 4 - Immediately return this expression instead of assigning it to the temporary variable "textResult".

calculator.java - 18 - Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object". (Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.)

calculator.java - 24 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.

calculator.java - 63 - Replace "exc" with an unnamed pattern.

calculator.java - 70 - Immediately return this expression instead of assigning it to the temporary variable "textResult".

calculator.java - 74 - Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'.

calculator.java - 183 - Remove this redundant jump.

start.java - 1 - Move this file to a named package.

start.java - 6 - Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'.

start.java - 8 - Replace this use of System.out by a logger.

start.java - 19 - Replace this use of System.out by a logger.
