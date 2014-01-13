Adverb
======

Spice up you code with adverbs!

This module basically just exports a bunch of synonyms for the identity
function. I came to the realization that programmers rarely bind adverbs
because they are imprecise. One may define a brush color as blue, or
with numerical values, but rarely as "very" blue. Or "unfortunately"
blue. I came up with the idea when a friend of mine claimed something
was "very very false." Which now gives the desired result:

```
very very False == False
```

As a bonus, I added a few "doge" modifiers.

Examples
========

```
wow. so reverse $ "egod"
```

```
brutally take 4 [0..]
```

```
carefully readFile "manual"
```

```
stupidly drop 1 ["vase", "hammer", "anvil"]
```

Uses
====

Obviously you can easily add some humor to an otherwise dull codebase,
but I think there may be more use than that. Code is meant to be
expressive, not just for machines but for humans. It could be that
judiciously employing adverbs in code may enable one to express ideas
more completely. Unlike comments, these adverbs can be easily placed
within expressions.

E.g.:

```
if doLogging then wisely runProgram (Just logFile)
else recklessly runProgram Nothing
```

```
case state of
  Impossible -> weirdly error "Dumb programmer."
  n -> handleState . tranquilly $ n
```
