# Drafted Notes

The goal of this document is to begin our investigation of understanding wtf the Jordan Curve Theorem ( JCT ) is even talking about!

## First Definitions

To establish context, we will define the following:

* Separation
* Connectedness
* Components
* JCT

### Sets
Sets are things that exist lol.

### Ordered Pair
Ordered pair (a,b) is {a,{a,b}}

### Zahlen
Zahlen is subsequent subsets of null set.
{} equals 0
{{}} 1
{{{}}} -1
{{{{}}}} 2

### Quotients
Quotients are ordered pairs of integers
(Top, Bottom) with equivalence relation making equivalent fractions equal
(2,4) is equal to (-1,-2)

### Reals
A dedekind cut r is defined to be the set of all quotients that are less than quotient (r,1).
Let R be the set of all dedekind cuts of quotients.

### UnderlyingSet
The UnderlyingSet is any set you want! ;) It is the set you want to work with!

### Open Set
The open sets are subsets of the UnderlyingSet.

### Topology
A Topology is a set of open sets.

### Topological Space
(UnderlyingSet,Topology)

### Cartesian Product
Set of all possible ordered pairs for two different sets.

### Function
Subset of cartesian product such that its a function.

### Continuity
Let (Domain,TopDom) and (Range,TopRange) be spaces. Continuous is for each open subset OpenOfRange of (Range,TopRange), u take functionInverse(OpenOfRange) and thats open too.
functionInverse(OpenOfRange) is the set of all points Points of Domain for which function(Points) in OpenOfRange. It is empty if OpenOfRange does not intersect the image set function(Domain) of function.
Go backwards through the function and you get an open set.

### Separated
Let $X$ be a topological space.
A $\bold{separation}$ of $X$ is a pair $U,V$ of disjoint nonempty subsets of $X$ whose uninon is $X$.

### Connected
The space $X$ is said to be $\bold{connected}$ if there does not exist a separation of $X$.

### Component
Given $X$, define an equivalence relation on $X$ by setting $x ~ y$ if there is a connected subspace of $X$ containing both $x$ and $y$.
The equivalence classes are called the $\bold{components}$ ( or the "connected components") of $X$.

### Open Set
element of the topology

### Closed Set
A subset Closed of a topological space (UnderlyingSet,Topology) is closed if (UnderlyingSet,Topology) - Closed is open.

### Interior
if u have a subset Subset of a space (UnderlyingSet,Topology) then the union of all open sets contained in Subset is the interior.

### Closure
if u have a subset Subset of a space (UnderlyingSet,Topology) then Closure is the intersection of all sets containing Subset.

### Unit Circle

### Homeomorphism
function: Domain -> Range 
If function and inverseFunction are both continuous, then function is homeomorphism.

### Simple Closed Curve
a space that is homeomorphic to the unit circle.

### Boundary
### proving the theorem
if u have the circle then u have a ball that a piece of the circle falls inside of. that ball maps to a ball in R. This is because the circle is mapped to by R.
circle: real -> (real,real)

### JCT
$\mathbf{X}$

https://mathworld.wolfram.com/JordanCurveTheorem.html

###
I assume for this theorem u have the one part of the line on the inside of the circle, u take the open ball that the part of the line falls inside of, and then take the union of all open balls inside of the circle, the union of all open balls is the interior aka internal balls. u have the one part of the line on the outside of the circle, u take the open ball that the part of the line falls inside of, and then take the union of all open balls outside of the circle, the union of all open balls is the exterior aka external balls.
