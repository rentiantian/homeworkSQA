#Understanding of Formal Methods in General and Model Checking in Particular

##Formal Methods

In computer science, specifically software engineering and hardware engineering, formal methods are a particular kind of mathematically based techniques for the specification, development and verification of software and hardware systems. The use of formal methods for software and hardware design is motivated by the expectation that, as in other engineering disciplines, performing appropriate mathematical analysis can contribute to the reliability and robustness of a design.

Formal methods are best described as the application of a fairly broad variety of theoretical computer science fundamentals, in particular logic calculi, formal languages, automata theory, and program semantics, but also type systems and algebraic data types to problems in software and hardware specification and verification.


##Model Checking

Model checking is a very important technique in automatic verification. It is most often applied to hardware designs. For software, because of undecidability the approach cannot be fully algorithmic, typically it may fail to prove or disprove a given property.

Formally, the problem can be stated as follows: given a desired property, expressed as a temporal logic formula p, and a structure M with initial state s, decide if M,s \models p. If M is finite, as it is in hardware, model checking reduces to a graph search.
