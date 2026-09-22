+++
date = 2024-02-06
title = "From combinators to concatenative and back again"

[extra]
authors = "Daniel Kiyoshi Hashimoto, Hugo Musso Gualandi"
where = "Trabalho de Conclusão de Curso, BCC/UFRJ"
url = "http://hdl.handle.net/11422/22871"
+++
Tacit or point-free programming is a programming style which avoids named variables, by
using combinators to compose smaller functions. Two models of tacit programming are
concatenative calculus and combinatory logic. The concatenative calculus is related to
stack-based languages, who are used in various contexts, including bytecode for virtual
machines and embedded systems. Combinatory logic is an applicative computation
model more similar to the lambda calculus. These two tacit models are frequently
compared to each other. The elementary combinators of combinatory logic are often
paired to stack-manipulation instructions: for instance, C looks similar to swap, and W is
similar to dup. In this work, we generalize this connection to all combinator expressions
and stack programs. We describe three algorithms to convert between the two tacit
models. The first translates any combinatory logic expression into a concatenative
expression using either the call-by-name or the call-by-value evaluation order. The
second algorithm is specialized to a subset of combinators that receives a callback
function as the first argument. It produces shorter and more intuitive stack programs.
Lastly, the third algorithm is a backwards version of the second one, converting any
concatenative calculus program back to a combinatory logic expression. Because our
algorithms preserve the reduction order, we show that each model is able to simulate
the other.
