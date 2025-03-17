# Side Notes

The mean (average) of a data set is found by adding all numbers in the data set and then dividing by the number of values in the set. The median is the middle value when a data set is ordered from least to greatest. The mode is the number that occurs most often in a data set.

---

The Any type docstring states that object is a subclass of Any and vice-versa:

> > > import typing
> > > print(typing.Any.**doc**)
> > > Special type indicating an unconstrained type.

    - Any object is an instance of Any.
    - Any class is a subclass of Any.
    - As a special case, Any and object are subclasses of each other.

However, a proper typechecker (one that goes beyond isinstance() checks, and which inspects how the object is actually used in the function) can readily object to object where Any is always accepted.

---
