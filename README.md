# Shun-san
My pesonal DISMATH portfolio

![alt text](http://orig09.deviantart.net/1ba9/f/2015/012/3/b/lelouch_vi_britannia_by_aura_blade4-d8dm7s0.gif " Logo Title Text 1")

##Week 1
+ We had our first introductions in this subject. At first I thought to myself, "What kind of subject is this" or "Is this even a subject".But it was actually an interesting subject about using logic and dealing with the unknown. I was really deep in thought when Melvin-san showed us the example of the knights and knaves. It was a question that is uncommon and we need to use the deepest part of our brains.  

+ We also discussed the first topics on this course: **Truth tables and propositions**. 

| p             | q             | p^q  |pvq  |p→q|
| ------ |:-----:| -----:| -------: | ------:|
| T      | T| T |T |T|T|
| T      | F     |F    |T |F|
| F      | T      |F     |T |T|
| F      | F      |F   |F |T|

##Week 2
+ Another refreshing week, I have now been introduced to **Logical Equivalences** and tried to prove the laws behind it. Actually, it was really similar to algebra laws so it's kinda easy to learn and it was really fun proving these kinds of stuff.
+ I also learned existential and universal truths. It was really cool since all theories are cycling in these truths.
+ Yet again, this is a fun week on my DISMATH journey.

|Name |	Equivalence|
| -----:| :-----|
|Identity laws |<ul><li> p ∧ T ≡ p	<li> p v F ≡ p</ul>|
|Domination laws |<ul><li> p v T ≡ T <li>p ∧ F ≡ F</ul>|
|Negation laws |<ul><li> p v ¬p ≡ T <li> p ∧ ¬p ≡ F</ul>|
|Double negation law	|<ul><li> ¬(¬p) ≡ p</ul>|
|Idempotent laws	|<ul><li>	p v p ≡ p	<li> p ∧ p ≡ p</ul>|
|Commutative laws |<ul><li>	p v q ≡ q v p <li> p ∧ q ≡ q ∧ p</ul>|
|Associative laws	|<ul><li>	(p v q) v r ≡ p v (q v r)	<li>(p ∧ q) ∧ r ≡ p ∧ (q ∧ r)</ul>|
|Distributive laws	|<ul><li>	p v (q ∧ r) ≡ (p v q) ∧ (p v r)	<li> p ∧(q v r) ≡ (p ∧ q) v (p ∧ r)</ul>|
|De Morgan's laws	|	<ul><li> ¬(p ∧ q) ≡ ¬p v ¬q	<li> ¬(p v q) ≡ ¬p ∧ ¬q</ul>|
|Absorption laws	| <ul><li> p v (p ∧ q) ≡ p	<li> p ∧ (p v q) ≡ p</ul>|

##Week 3
**3rd week** in my DISMATH journey starts...
+ I learned about the different **Rules of Inference**:

|Type|	Rule of Inference	|Tautology|
| -----:| -----:|----------:|
|Modus Ponens	|p, p → q ∴ q	|[p ∧ (p → q)] → q|
|Modus Tollens|	¬q, p → q ∴ ¬p|	[¬q ∧ (p → q)] → ¬p|
|Hypothetical Syllogism	|p → q, q → r ∴ p → r	|[(p → q) ∧ (q → r)] → (p → r)|
|Disjunctive Syllogism|	p ∨ q, ¬p ∴ q	|[(p ∨ q) ∧ ¬p] → q|
|Addition	|p ∴ p ∨ q|	p → p ∨ q|
|Simplification|	p ∧ q ∴ p	|(p ∧ q) → p|
|Conjunction|	p, q ∴ p ∧ q|	[(p) ∧ (q)] → (p ∧ q)|
|Resolution|	p ∨ q, ¬p ∨ r ∴ q ∨ r	|[(p ∨ q) ∧ (¬p ∨ r)] → q ∨ r|
+ I also learned about the 4 methods of proof: Direct proof, Proof by Contaraposition, as well as, Vacuuos and Trivial Proof.

##Week 4
+ **Congratulations** for a month in my DISMATH journey!
+ This week was a week full of in depth lectures on the methods of proof and also multiple examples of each and also combination examples. I learned about **Mathematical Induction** which is already taught in ENGALG2, so I easily got the heart of the problems here.
+ A tip for mathematical induction is that you always need to have a basis before proving the problem stated since you will go into a loop if the first step is ignored.
+ Also, **Recursive statements** are also introduced which follows the arithmetic sequencs (also taught in high school), so its still easy-mid difficulty.
+ **Looking forward** to the next meetings of my DISMATH journey!

|Method of Proof|Steps|
|:-----|:-------|
|Direct Proof (p → q)|<ol type="1"><li> Assume p is true. <li> Show that q is true (based on 1).	</ol>	|
|Proof by Contraposition (¬q → ¬p)|<ol type="1"><li> Assume ¬q is true. <li> Show that ¬p is true(based on 1).</ol>|		
|Proof by Contradiction|<ol type="1"><li>	Assume ¬p is true. <li> Show that 1. ends up in a contradiction.</ol>	|
|Vacuous Proof (¬p → (p → q))| 1. Show that p is false, because (p → q) must be true when p is false.|
|Trivial Proof (q → (p → q))|	1. how that q is true, it follows that (p → q) must also be true.		|

##Week 5
+ What I've learned this week:
+**Negation of Implication** (¬(p → q) → (p ∧ ¬q))
+ **Contradiction and Implication**
  + “If *p* s true, then *q* is true” using a **proof by contradiction**:
    1. Assume that *p≡T* and that *q≡F*.
    2. Derive a contradiction.
    3. Conclude that if *p* is *true*, *q* must be *as well*.
+ **Proof by Equivalence (Biconditionals)**
  - To prove a theorem that is a biconditional statement *(p ↔ q)*, we show that: *(p → q) → [(p → q) ∧ (q → p)]*
  - Ex 1. "If n is an integer, n is even iff n^2 is even." (r ↔ s)
    - For biconditional statement, we should prove (r → s) and (s → r) are both *true*.

##Week 6
+ This week, we discussed some ENGALG1 stuff and related it to DISMATH...
+ **SUMMATION**
    - The notation for sum of _a<sub>m</sub>, a<sub>m+1</sub>, ..., a<sub>n</sub>_ is _∑<sup>a</sup><sub>i=m </sub>a<sub>i</sub>_ where _i_ is the index of summation.

+ **RECURSIVE/INDUCTIVE DEFINITION**
    - Basis step: Specify the value of the function at zero
    - Recursive step: Give a rule for finding its value at an integer from its values at smaller integers

+ **RECURSIVE ALGORITHMS**
    - It solves a problem by reducing it to an instance of the same problem with smaller input.
        - Recall: <u>Algorithm</u> - finite set of precise instructions for performing a computation/solving a problem.
 integer.

##Week 7
+ This week, we had an introduction to set theory: (Here are some Terminologies)
    - A _set_ is an unordered collection of distinct objects, which may be anything (including other sets).
        - {a,b,c,d,e}
        </br>    ↳ *Set Notation:* curly braces with commas separating out the elements 
+ **Empty Set**
</br>   ↳ { } = ∅
    - no elements
    * **Set Builder Notation**
    </br>    ↳ {x | some property x satisfies}

##### SET IDENTITIES TABLE
|  **LAW**  |  **IDENTITY**  |
| :------: | :-----------------------------: |
|  _Identity Laws_  |  A ⋂ U ≡ A  <br>  A ⋃ ∅ ≡ A  |
|  _Domination Laws_  |  A ⋃ U ≡ U  <br>  A ⋂ ∅ ≡ ∅  |
|  _Idempotent Laws_  |  A ⋃ A ≡ A  <br>  A ⋂ A ≡ A  |
|  _Complementation Law_  |  (A¯)‾ ≡ A  |
|  _Commutative Laws_  |  A ⋃ B ≡ B ⋃ A  <br>  A ⋂ B ≡ B ⋂ A  |
| _Associative Laws_  |  A ⋃ (B ⋃ C) ≡ (A ⋃ B) ⋃ C  <br>  A ⋂ (B ⋂ C) ≡ (A ⋂ B) ⋂ C  |
|  _Distributive Laws_  |  A ⋃ (B ⋂ C) ≡ (A ⋃ B) ⋂ (A ⋃ C) <br>  A ⋂ (B ⋃ C) ≡ (A ⋂ B) ⋃ (A ⋂ C)  |
|  _De Morgan's Laws_  |  (A ⋂ B)‾ ≡ A‾ ⋃ B‾  <br>  (A ⋃ B)‾ ≡ A‾ ⋂ B‾  |
|  _Absorption Laws_  |  A ⋃ (A ⋂ B) ≡ A  <br>  A ⋂ (A ⋃ B) ≡ A  |
|  _Complement Laws_  |  A ⋃ A‾ ≡ U  <br>  A ⋂ A‾ ≡ ∅  |

+ **SUBSETS**: A set _S_ is a subset of a set _T_ (denotes S ⊆ T) if all elements of _S_ are also elements of _T_.
+ **POWER SET**: A set of all subsets.
+ **CARDINALITY**: The number of element it contains. If _S_ is a set, we denote its cardinality by writing |S|.
    - **Infinite Cardinalities**: alaph-null (0,1,2,3,...)

+ **FUNCTIONS**
    - _A_ & _B_ are sets
    -  A function _f_ from _A_ to _B_ is an assignment of exactly one element of _B_ to each element of _A_.
    -  Functions are also called MAPPINGS or TRANSFORMATIONS.
        - f: A to B </br>
            ↳ A: domain </br>
            ↳ B: co-domain
        - **Range** - actually occuring values

+ **IMAGE**
    - If _f(a) = b_, _b- is the image of _A_.
    - The range of _f_ is the set of all images of elements of _a_.

+ **TYPES OF FUNCTIONS**
    - One - to - one Function (_Injection_)</br>
        ↳ functions that never assign the same value to two different domain elements.
    - Onto Function (_Surjective_)</br>
        ↳ functions have equal range & co-domain.
    - One - to - one Correspondence (_Bijection_)</br>
        ↳ function is both one - to - one and onto.

##Week 8
+ I can't believe it's already two months since I started DISMATH. There are so many things that I have learned since Day 1 and now we now proceed to Algorithms...
+ ALGORITHMS - A finite set of precise instructions for performing a computation or for solving a problem.
    - *Properties of Algorithms*
      - INPUT - has input values from a specified set 
      - OUTPUT - solution to the problem 
      - DEFINITENESS - defined precisely 
      - CORRECTNESS - produce the correct output values 
      - FINITENESS - produce the desired output 
      - EFFECTIVENESS - perform exactly and in a finite amount of time 
      - GENERALITY - applicable for all problems of the desired form
+ PSEUDOCODE
    - high - level desciption of an algorithm that uses the structural conventions of a programming language 
    - intended for human reading
    - Preconditions - describe valid input
    - Postconditions - conditions that the output should satisfy
+ Algorithm example: Finding the Maximum {5,4,1,8,3}
  - Input: ({a1, a2, a3,..,an} ∈ , Z)
  - Output: largest 8
  - Pseudocode

    > max = a1; </br>
    > for i: 2 to n { </br>
    >   if(max < ai) </br>
    >       max = ai} </br>

##Week 9
+ This week, we continued discussing Algorithms which include the searching algorithms, the sorting alogrithms and greedy algorithms...

+ **SEARCHING ALGORITHMS** </br>
    ↳ Problem of locating an algorithm in an ordered list
    - **Binary Search** - comparing the middle values of a list then repeated until the desired output is found.

+ **SORTING ALGORITHMS** </br>
    ↳ Problem of assorting elements into increasing order
    - **Bubble Sort** - compares the first two elements then interchanging them if they are in the incorrect order.
    - **Insertion Sort** - compares the second element with the first and inserts it before the first element if it is less. Otherwise, it is inserted after the first element.

+ **GREEDY ALGORITHMS** </br>
    ↳ Algorithms that make what seems to be the "best" choice at each step.

##Week 10
Last 3 week before DISMATH ends....
I am surprised that we have already gotten this far and now we are discussing the time compexities of the different algorithms discussed in class...

+ Big-O Notation
    - Let f and g be functions from R-R; _f(x)_ is _O(g(x))_ if there are constants C and k such that:
        |f(x)| ≤ C|g(x)| 
    whenever x > k.
    - Example: f(x)=x^2 + 2x + 1; O(x^2); k=1, C=4
+ Big-Omega and Big-Theta Notation
    - Big-O Notation does not provide a lowerbound for the size of f(x). 
        - Big-Omega (Big-Ω) - lower bound
        - Big-Theta (Big-Θ) - both upper and lower bound

+Algorithm Time Complexity - can be expressed in terms of the number of operations used by the algorithm when the input has a particular size.
- Division and Modulo Operator
  - let a be an integer and d positive integer. Then there is a unique Q and r with 0 ≤ r < d such that a = dQ + r
  - Q = a div d
  - r = a mod d

##Week 11
+ This week was a week for us to place our thoughts to God. (HOLY WEEK)...

##Week 12
This week, my quiz was returned and to my surprise I still failed. I'm really nervous on my future in DISMATH. But I need to take things seriously and move on...
+ Anyway, we discussed the graph theory in a span of 1 week(2 meetings) and now we are about to take Quiz 3!
+**Graph Theory**
    - Easiest coverage for the quiz
    - _Degree_ - number of degrees at a node/vertex
    - _Handshaking Theory_ - 2e = ∑deg(v)
    - _Path_ - sequence of edges travelling from vertex to vertex along the edges
    - _Euler Circuit_ - passess through every edge and goes back to starting point
    - _Euler Path_ - simple path containing every edge of the graph
    - _Hamilton Path_ - passes through every vertex
    - _Hamilton Circuit_ - passes through every vertex then goes back to the starting point
    - _Matrices of Graphs_ - 1 for adjacent; 0 for non-adjacent
    - _Incidence of Matrices_ - Matric between vertices and edges
    - _Isomorphism of Graphs_ - "rubberband"

+ **Planar Graph**
    - no edges cross in a graph
    - _Euler's Formula_ - regions = edges - vertices + 2
    - _Euler's Characteristic_ - ℵ = regions - |edges| + |vertices| = 2

+ **Homeomorphic Graphs**
    - can be obtained from the same graph by a sequence of elementary subdivisions
        - _Elementary Subdivision_ - everything is planar graph
    - _Kuratowski's Theorem_ - nonplanar if and only if it contains a subgraph homeophobic to K<sub>3,3</sub> and K<sub>5</sub>

##Week 13 (A.K.A The final week)
+ Congratulations on the Final week!
+ Alas, it now the final week in DISMATH. It is now time to go all out for the finals and finally be free. 
+ This week, we discussed the final lessons for the coverage of the finals(starting from Graph coloring to the vending machine problem).
+ **Graph Coloring**
    - assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color
    - _Four Color Theorem_ - the chromatic number of a planar graph is no greater than four

+ **Trees**
    - connected undirected graph with no simple circuits
    - data structure that emulates a heirarchical tree structure with a set of linked notes
    - used to construct efficient algorithms for locating an item in a set
    - _Forest_ - multiple trees
    - _Rooted Tree_ - a tree in which one vertex has been designated as the root and every edge
        - leaves - nodes that do not have children
        - ancestors - nodes on top
        - descendants - children/grandchildren
    - _Subtree_
    - _M-ary tree_ - if every internal vertex has no more than m children
        - an m-ary tree with m = 2 is called a _binary tree_

+ **Modeling Computation**
    - _Language and Grammars_
        - Grammars - used to generate the words of a language and to determine whether a word is in a language
        - Compiler - reads a program written in a source language and translate it into an equivalent program in a target language.
        - Formal Language - automatic translation of one language to another
            - well defined set of rules

+ **Alphabet & String**
    - common way to talk about words, numbers, etc.

+ **Automata Theory**
    - studies the law of computation
    - Finite Automata - simplest model of automata
        - initial state
        - final/acceptance state
        - dead/stuck state
        - transition

+ **Lexical Analysis**
    - process where the stream of characters making up the source program into a sequence of "words" that make up the source code.

+ **Finite State Machine**
    - finite-state automaton (FSA, plural: automata), or simply a state machine, is a mathematical model of computation used to design both computer programs and sequential logic circuits. It is conceived as an abstract machine that can be in one of a finite number of states.

+ In the end, I learned a lot in this course. All the fun times with Melvin-san was unreplacable. I know he really enjoys teaching us and I hope he can also show his enthusiasm for the next batch of engineers. I hope we can all apply our learnings here in this course in the future.
+ Thank you Melvin-san for your hard work! Arigatou Gozaimasu!


![alt text](https://s-media-cache-ak0.pinimg.com/736x/dd/87/30/dd873042a0370e682252fb18d0b6cb09.jpg " Logo Title Text 1")
