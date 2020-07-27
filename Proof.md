# Drafted Notes

Proof of the Theorem

### Jordan Curve Theorem
https://mathworld.wolfram.com/JordanCurveTheorem.html https://en.wikipedia.org/wiki/Jordan_curve_theorem

Let SimpleClosedCurve be a simple closed curve in Square(UnitCircle). then SimpleClosedCurve separates Square(UnitCircle) into two components Component1 and Component2. Each of the sets Component1 and Component2 has Boundary as its boundary; that is, Boundary equals Closure(Component1) without Component2 AND Boundary equals Closure(Component2) without Component1.

## First Definitions

Lets define literally everything because thats the way I like to do it. Just skip to the stuff u dont know.

### Sets
Sets are things that exist lol.
{} is the empty set
{{}} is the set containing the empty set.
{{},{{}}} is the set containing the empty set and the set containg the empty set.

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
A dedekind cut r or /-inf, r/ is defined to be the set of all quotients that are less than quotient (r,1).
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
Subset of cartesian product such that for each ordered pair (InsideDomain,InsideRange) inside of the function, each InsideDomain has a unique InsideRange associated with it. It passes the vertical line test.

### Continuity
Let (Domain,TopDom) and (Range,TopRange) be spaces. Continuous is for each open subset OpenOfRange of (Range,TopRange), u take functionInverse(OpenOfRange) and thats open too.
functionInverse(OpenOfRange) is the set of all points Points of Domain for which function(Points) in OpenOfRange. It is empty if OpenOfRange does not intersect the image set function(Domain) of function.
Go backwards through the function and you get an open set.

### Separation
Let (UnderlyingSet,Topology) be a topological space.
A separation of (UnderlyingSet,Topology) is a pair of disjoint nonempty open subsets of UnderlyingSet whose union is UnderlyingSet.

### Connected
The space (UnderlyingSet,Topology) is said to be connected if there does not exist a separation of (UnderlyingSet,Topology).

### Component
Given space (UnderlyingSet,Topology), define an equivalence relation on (UnderlyingSet,Topology) by setting Point1 is equal to Point2 if there is a connected subspace of (UnderlyingSet,Topology) containing both Point1 and Point2.
The equivalence classes are called the components (or the "connected components") of (UnderlyingSet,Topology).

### Open Set
element of the topology

### Closed Set
A subset Closed of a topological space (UnderlyingSet,Topology) is closed if (UnderlyingSet,Topology) - Closed is open.

### Interior
if u have a subset Subset of a space (UnderlyingSet,Topology) then the union of all open sets contained in Subset is the interior.

### Closure
if u have a subset Subset of a space (UnderlyingSet,Topology) then Closure is the intersection of all closed sets containing Subset.

### Square
Cut times Cut
Cut Plus Cut Plus Cut Plus Cut... Plus Cut, Cut Times.
A Square with Cut as 2 sides.

### Unit Circle
UnitCircle is the set of all elements of RealsHorizontal cartesian product RealsVertical such that square(CutHorizontal) plus square(CutVertical) equals /-inf,1/ . where CutHorizontal is an element of RealsHorizontal and CutVertical is an element of RealsVertical.

### Homeomorphism
function: Domain -> Range 
If function and inverseFunction are both continuous, then function is homeomorphism.

### Simple Closed Curve
a space that is homeomorphic to the unit circle.

### Boundary
If Subset is a subset of (UnderlyingSet,Topology) then
boundary(Subset) is Closure(Subset) Intersect Closure(UnderlyingSet Without Subset)

### Jordan Curve Theorem
https://mathworld.wolfram.com/JordanCurveTheorem.html
https://en.wikipedia.org/wiki/Jordan_curve_theorem

Let SimpleClosedCurve be a simple closed curve in Square(UnitCircle). then SimpleClosedCurve separates Square(UnitCircle) into two components Component1 and Component2. Each of the sets Component1 and Component2 has Boundary as its boundary; that is, Boundary equals Closure(Component1) without Component2 AND Boundary equals Closure(Component2) without Component1. 

### proving the theorem
From any space you can just go to the circle lol.
If you have a random space, the space has balls associated with it that are the same as the balls around a circle.
if u have the circle then u have a ball that a piece of the circle falls inside of. that ball maps to a ball in R. This is because the circle is mapped to by R.
circle: real -> (real,real)

I assume for this theorem u have the one part of the line on the inside of the circle, u take the open ball that the part of the line falls inside of, and then take the union of all open balls inside of the circle, the union of all open balls is the interior aka internal balls. u have the one part of the line on the outside of the circle, u take the open ball that the part of the line falls inside of, and then take the union of all open balls outside of the circle, the union of all open balls is the exterior aka external balls.
