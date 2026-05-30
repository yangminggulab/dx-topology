## Overall Roadmap

Following the MIT 18.901 topology description, topology studies geometric properties that do not depend on distance or angle. Its core objects include topological spaces, continuous maps, compactness, and path structure. This tree matches the repository's notes on set foundations, topological spaces, continuous maps, connectedness, compactness, and separation.

```text
Topology = studying continuity and spatial structure without relying on distance
|
+-- The central problems
|   +-- Without a distance, how can nearby and continuous be defined?
|   |   +-- Use open sets, neighborhoods, bases, and subbases to define topological spaces.
|   +-- How can two spaces be judged essentially the same?
|   |   +-- Use continuous maps, homeomorphisms, open maps, and closed maps.
|   +-- Which properties survive continuous deformation?
|       +-- Use connectedness, compactness, and separation to describe intrinsic structure.
|
+-- Tool 1: sets and basic language -> preparation for abstract spaces
|   +-- Sets and cardinality distinguish finite, countable, and uncountable
|   +-- Order and induction handle ordered constructions
|   +-- Basic exercises turn set language into a usable tool
|
+-- Tool 2: topological spaces -> defining spaces by open sets
|   +-- Bases and subbases generate a topology from fewer open sets
|   +-- Neighborhoods, closure, interior, boundary describe local set relations
|   +-- Subspace topology restricts structure from a larger space to a subset
|   +-- Product spaces combine topological structures
|   +-- Countability controls complexity through first/second countability and separability
|
+-- Tool 3: continuous maps -> structure-preserving functions
|   +-- Equivalent forms of continuity use open sets, closed sets, and closure
|   +-- Open and closed maps study how maps transport open and closed structure
|   +-- Homeomorphisms decide when two spaces are topologically equivalent
|
+-- Tool 4: core properties -> what remains under continuous deformation
    +-- Connectedness and path-connectedness describe whether a space can be split
    +-- Compactness controls infinite objects through finite subcovers
    +-- Perfect maps and category deepen the study of size and compactness
    +-- Separation axioms distinguish points from points and points from closed sets
```

# dx's Topology

## Preface

Topology is easily misunderstood as a course that only invents new words. Open sets, bases, neighborhoods, closure, interior, compactness, connectedness, separation axioms, homeomorphisms, and countability conditions can feel scattered when first encountered.

The aim of this book is to pull out the main line: how a space is specified, how openness is defined, how continuity is built from openness, and how connectedness, compactness, and homeomorphism compare spaces.

## Why This Book Is Written This Way

A topology text that is only a directory of definitions quickly loses direction. Once the definitions are connected to their purposes, the subject becomes a single structure.

The recurring action is: decide which sets are open, study what properties this decision creates, and then ask which of those properties maps preserve. Bases, subspaces, product spaces, continuous maps, homeomorphisms, countability, compactness, and connectedness then become branches of the same tree.

## What This Book Keeps

The notes begin with sets, topologies, bases, and subspaces. They then move to continuous maps, open maps, closed maps, quotient maps, and homeomorphisms. Later chapters develop connectedness, compactness, separation, and countability conditions.

Homework, review plans, and exam notes are kept because topology intuition often forms while repeatedly deciding whether a set is open, a map is continuous, or a space is homeomorphic to another.

## Intended Readers

This book is for readers who feel they understand each topology chapter separately but cannot yet see the whole map. It tries to make the map grow gradually.

## Repository Notes

- The main entry is `main.tex`.
- The body covers foundational topology, continuous maps, connectedness, compactness, separation, and countability.
- Homework and review materials are kept separately.
- For local compilation, running `xelatex main.tex` twice is usually enough.
