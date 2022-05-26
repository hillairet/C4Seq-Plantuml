# C4Seq-PlantUML
C4Seq allows you to create sequence diagrams with the same appearance and syntax as
the [C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML) library to have a uniform
style for all the diagrams in your project.

![Example sequence diagram using C4Seq](./example.png)

See [example.puml](./example.puml) for the code.

## Why C4Seq

The [C4 model](https://c4model.com/) is an amazing solution to visualize all the elements
involved in architecture of a software project.
The dynamic diagram from the C4 model used to display the sequence of interactions
between the elements of a project is nowhere near as practical and readable as the sequence
diagram from the UML specification. Sequence diagrams are a natural complement to the
C4 model diagrams.

PlantUML is the ideal tool to create C4 model diagrams using its
[C4 standard library](https://github.com/plantuml-stdlib/C4-PlantUML) and also sequence diagrams.
However C4-PlantUML has logically implemented only the diagrams from the C4 model
therefore sequence diagrams would look very different and disconnected from the C4 diagrams
in the documentation of a software architecture.

The C4Seq-PlantUML library provides the same syntax and visual style for sequence diagrams.
It is currently totally standalone although it would be great to see it integrated to C4-PlantUML
