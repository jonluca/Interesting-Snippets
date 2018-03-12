# Interesting Snippets

## On Altruism 

From [Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/altruism/#DesiMoti):

*This thesis that what motivates us to act is always a desire should be accepted only if we have a good understanding of what a desire is. If a desire is simply identified with whatever internal state moves someone to act, then the claim, “what motivates us to act is always a desire”, when spelled out more fully, is a tautology. It says: “the internal state that moves us to act is always the internal state that moves us to act”. That is not a substantive insight into human psychology, but a statement of identity, of the form “A = A”. We might have thought we were learning something about what causes action by being told, “what motivates people is always a desire”, but if “desire” is just a term for whatever it is that motivates us, we are learning nothing (see Nagel 1970: 27–32).*


## On Perfect Secret Sharing

From [Adi Shamir's 1979 Perfect Secret Sharing paper](shamir.pdf)

*Some of the useful properties of this (k, n) threshold scheme (when compared to the mechanical locks and keys solutions) are: 

 (1) The size of each piece does not exceed the size of the original data. 

 (2) When k is kept fixed, D~ pieces can be dynamically added or deleted (e.g., when executives join or leave the company) without affecting the other D i pieces. (A piece is deleted only when a leaving executive makes it completely inaccessible, even to himself.) 

 (3) It is easy to change the D i pieces without changing the original data D--all we need is a new polynomial q(x) with the same free term. A frequent change of this type can greatly enhance security since the pieces exposed by security breaches cannot be accumulated unless all of them are values of the same edition of the q(x) polynomial. 

 (4) By using tuples of polynomial values as Di pieces, we can get a hierarchical scheme in which the number of pieces needed to determine D depends on their importance. For example, if we give the company's president three values of q(x), each vice-president two values of q(x), and each executive one value of q(x), then a (3, n) threshold scheme enables checks to be signed either by any three executives, or by any two executives one of whom is a vice-president, or by the president alone.*