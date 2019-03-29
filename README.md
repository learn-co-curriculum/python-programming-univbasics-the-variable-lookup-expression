# The Variable Lookup Expression

## Learning Goals

* Define the Variable Lookup Expression

## Introduction

The final of our _essential three_ expressions is the variable lookup
expression. Like the _constant expession_, it rounds out the “essential three”
by being boring, yet profound.

It retrieves the value that we set with the _assignment expression_ from the
name or "bare word" we assigned.

> **NOTE**: When we say "variable lookup" that also includes symbolic
> constants.

## Define the Variable Lookup Expression

To lookup the value in a variable we simply type it.

```ruby
# Assignment expression that returns 32
age = 32 #=> 32

# Type in the name
age #=> 32
```

That’s it. The values we associate with the assignment expression can be gotten
back out of their variable or constant by simply typing the variable or
constant’s name.

## Variable Lookup as Conversation

Think about, again, a baby learning to talk. They learn the constant or value
of their parent (_constant expression_). The parent repeats a thousand times
their (bare word) name: `MAMA` or `DADA`. Eventually a magical thing happens in
the baby's brain and they realize...

```ruby
MAMA = :the_person_in_front_of_me_who_keeps_saying_mama
```

> **ASIDE**: We snuck in a new type of constant just then called a `Symbol`.
> It's like a name, but it starts with a `:`.  We'll learn more about them
> later, but we want to excite you about constants that _aren't_ simple
> numbers!


And then at some random moment the baby repeats the (bare word) name: `MAMA`.
Suddenly the parents stream tears of joy. With a bit more practice baby will be
learning from "Sesame Street," from parents and friends, to grow their world of
bare-words so that they can have richer experiences in the world.

Consider this scenario. Look for the _essential three_ expressions in here.

<!-- Don't trim trailing whitespace, used to force newline -->

Parent: See the doggie? That’s a doggie.  
Child: Doggie?  
Parent: That’s right, that’s a doggie. Doggies say “Woof-woof!”  
Child: Doggie?  
Parent: Right. Doggie.  

_Some time later_

Child: Doggie!  
Parent: That’s right. Doggie!  

If you think about it, most of children's education until early elementary
school is giving them thousands of assignment expressions so they can
participate in the world: "Red," "one," "eleven," "far."

It turns out, Ruby is no different.

In a brand new session of IRB, Ruby knows about rules of expression evaluation,
some operators, and some special words. Everything else you have to "load into"
Ruby. The tool for this is the _assignment expression_

Let’s compare teaching a baby a four-legged animal's name and teaching Ruby
that `a` is `4`.

|Expression|Real-Life Conversation|Ruby Conversation|
|----------|----------------------|-----------------|
|Value Expression|Parent points "Doggie"|`4 #=> 4`|
|Assignment Expression|"Doggie" = ![Puppy Picture](https://curriculum-content.s3.amazonaws.com/programming-univbasics/the-variable-lookup-expression/small_puppy.JPG)|`a = 4 #=> 4`|
|Variable Lookup|Child Says: "Doggie!"|`a #=> 4`|

## Conclusion

With the _essential three_ expressions under your control, we're going to start
rapidly building up the richness of things you can do using expressions. In
fact, in the rest of this module, **everything** will be an expression of some
sort. It turns out we can write programs of high levels of sophistication
without using anything more than expressions.

> **FUTURE DIRECTIONS**: Whole programming languages are built around executing
> by means of evaluating expressions! Languages that work this way are called
> "functional languages" and they are some of the first programming languages
> ever created.

Lets expand the world of _constants_ we know about beyond numbers. While
they're handy when we're learning, there's a lot more to say about the world!
