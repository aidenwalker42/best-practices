Best Practices in java

Camel Casing
Avoid Global Variables 
    Minimize the use of global variables.
    This includes all data types, objects, and functions.
    Global variables and functions can be overwritten by other scripts.
    Use local variables instead, and learn how to use closures.

Always Declare Local Variables

Comments

Good Variable Names

=== instead of ==

Wrap loose declarations in blocks
    You can avoid name clash and loose temporary declarations access by wrapping a quickly logic in its own scope.

Keep your code uniform

Don't initialize things with “undefined”
    Something is “undefined” when it lacks value. Let’s agree that assigning “no value” as a “value” for something is a pretty weird concept right? Since Javascript already makes things “undefined” how can you tell whether something is undefined because of you or Javascript? It makes it hard to debug why things are “undefined” so prefer setting things to “null” instead.

Use Typescript
    Typescript can help you a lot in delivering better code. It will need some getting used to if you never tried a type system but it pays off in the long run.

Use semicolons ;

Use shortcuts

Modularizing your code
    using functions

Avoid duplicating code
    theres probably a better solution

