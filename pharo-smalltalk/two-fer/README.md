# Two Fer

Welcome to Two Fer on Exercism's Pharo Track.
If you need help running the tests or submitting your code, check out `HELP.md`.

## Instructions

`Two-fer` or `2-fer` is short for two for one. One for you and one for me.

Given a name, return a string with the message:

```text
One for name, one for me.
```

Where "name" is the given name.

However, if the name is missing, return the string:

```text
One for you, one for me.
```

Here are some examples:

|Name    |String to return
|:-------|:------------------
|Alice   |One for Alice, one for me.
|Bob     |One for Bob, one for me.
|        |One for you, one for me.
|Zaphod  |One for Zaphod, one for me.

In Pharo, classes are objects that can have instance and class methods, however unlike HelloWorld the tests for TwoFer have been written to call instance methods. Typically class methods are used for constructing new objects (like a contructor in other languages).

## Source

### Created by

- @macta

### Contributed to by

- @bencoman

### Based on

https://github.com/exercism/problem-specifications/issues/757