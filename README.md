# Sonata
A modern programming designed for precision, a subset of Fugue.

* measurements (consisting of a magnitude and units) are first-class
    * base dimensions are keywords
    * units can be defined based on dimensions
* data types
    * dimension
    * unit (tied to one or more dimensions)
    * boolean
    * byte
    * rune
    * string
    * number (int, big int, float, double, complex, imaginary)
    * support for infinity
    * measurement (number + unit)
    * null
    * function
    * type
    * object
    * pointer
    * record
    * vector
    * never
* operators
    * +, -, \, *
    * - for negation
      - <, <=, >, >=
      - == for equality
      - "and" and "or" for logical "and" and "or", or for control
      - "not" or "!" for logical not
      - "!=" for logical xor (not equal)
      - & for bitwise and
      - | for bitwise or
      - ^ for bitwise xor
      - ~ for bitwise not
      - support for mathematical multiplication notations, such as x(y)
* syntax
    * expressions use infix notation
    * statements are newline terminated, no multiple statements per line
    * line continuation uses single backslash character
    * libraries are imported using "use package", "use package.class", "use package.class.method", or "use package.function"
    * blocks use braces, { and }
    * indentation is free-form
* comments
    * inline comments use --
    * block comments use /-- and --/
    * doc comments (dev) use ===
    * doc comments (public) use ==
    * comments can be nested
    * precedence and grouping uses ( and )
* variables
    * immutable by default
    * declared as "name: type = value"
    * default values are null if not declared
* type system
    * strongly types
    * refinement types
    * dependent types
    * inference and coercion
* object-oriented
* supports functional programming
* supports imperative and declarative syntax
* interpreted
* transpiles to JavaScript
* domain specific for scientific, AI, and game development (these come together in the domain of procedural generation)
* standard library
* toolchain (transpiler, package manager, VS Code extension for syntax highlighting and intellisense, Visual Studio extension for syntax highlighting and intellisense)
* macros
* generics
* result types and exceptions
* algebraic types


## References and Inspirations
* Diehl, Stephen. [Exotic Programming Ideas](https://www.stephendiehl.com/posts/exotic01.html)
* Sinclair, James. [Things I Wish Someone Had Explained About Functional Programming](https://jrsinclair.com/articles/2019/what-i-wish-someone-had-explained-about-functional-programming/)
