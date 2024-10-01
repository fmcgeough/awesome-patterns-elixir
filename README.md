# awesome-patterns-elixir
A curated list of libraries and resources for the Elixir programming language focused 
on Pattern and Anti-patterns.

## Language Documentation 

-  [Anti Patterns in Elixir code](https://hexdocs.pm/elixir/main/code-anti-patterns.html)
  
## Books 

- [Elixir Patterns](https://elixirpatterns.dev/)
- [Functional Programming Patterns in Scala and Clojure](https://pragprog.com/titles/mbfpp/functional-programming-patterns-in-scala-and-clojure/)

## Videos 

- [Gang of None - talk by José Valim](https://www.youtube.com/watch?v=agkXUp0hCW8)
- [Typed Design Patterns for the Functional Era](https://www.youtube.com/watch?v=mB2ZhK8tB8Y)

## Web Pages 

- [Functional Programming Design Patterns](https://fsharpforfunandprofit.com/fppatterns/)
- [Domain Modeling Made Functional](https://pragprog.com/titles/swdddf/domain-modeling-made-functional/)
- [Circuit Breaker Pattern](https://martinfowler.com/bliki/CircuitBreaker.html?ref=wellarchitected)

## Research Papers 

- [Typed Design Patterns for the Functional Era](https://arxiv.org/pdf/2307.07069)
- [A Functional Pattern System for Object-Oriented Design](https://homepages.ecs.vuw.ac.nz/~tk/fps/fps-sans-escher.pdf)
- [Sagas (long lived transactions)](https://www.cs.cornell.edu/andru/cs711/2002fa/reading/sagas.pdf)
- [CQRS and Event Sourcing Case Study](https://home.agh.edu.pl/~malawski/DebskiSzczepanik-CQRS-IEEE-Software.pdf)

## Tools / Libraries - Design Patterns

- [sage](https://hexdocs.pm/sage/readme.html), an Elixir implementation of the Sagas pattern.
- [commanded](https://hexdocs.pm/commanded/Commanded.html), CQRS/ES pattern
- [breaker_box](https://hexdocs.pm/breaker_box/BreakerBox.html), implementation of the circuit breaker pattern
- [throttling](https://hex.pm/packages/ex_sleeplock), allow concurrent throttling using a named lock

## Tools / Libraries - General 

- [Credo](https://hexdocs.pm/credo/overview.html), a static code analysis tool for the Elixir language with a focus on teaching and code consistency.
- [Dialyzer](https://www.erlang.org/doc/apps/dialyzer/dialyzer.html), DIscrepancy AnaLYZer for ERlang programs. Dialyzer is a static analysis tool that identifies software discrepancies, such as definite type errors, code that is unreachable because of programming errors, and unnecessary tests in single Erlang modules or an entire codebase.
- [Dialyxir](https://hexdocs.pm/dialyxir/readme.html), a wrapper around dialyzer for the Elixir language
