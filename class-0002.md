# Arrays, Loops, Imports

* ## Imports

**Package = directory. Java classes can be grouped together in packages.**


### Package declaration

**The first statement, other than comments, in a Java source file, must be the package declaration.**

### Package declaration syntax

1. Package statment (optional).
2. Imports (optional).
3. Class or interface definitions.

## Imports: three options:
1. he most common programming style:

`import javax.swing.*; ` The wildcard character (*) is used to specify that all classes with that package are available to your program.

2. Classes can be specified explicitly on import instead of using the wildcard character: 

`import javax.swing.JOptionPane;`

3. Alternately we can the fully qualified class name without an import.

`javax.swing.JOptionPane.showMessageDialog(null, "Hi");`


--------


* # A Guide to Java Loops

## Loops
 **looping is a feature which facilitates the execution of a set of instructions until the controlling Boolean-expression evaluates to false.**

 ##  types of loops

1. **Simple for loop** :control structure that allows us to repeat certain operations by incrementing and evaluating a loop counter.

2. **Enhanced for-each loop** : control flow statement for traversing items in a collection.

3. **While loop**: repeats a statement or a block of statements while its controlling Boolean-expression is true.


4. **Do-While loop**: works just like the while loop except for the fact that the first condition evaluation happens after the first iteration of the loop.

