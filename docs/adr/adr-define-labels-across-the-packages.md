# ADR [Number]: Define labels across the packages.

## Status

Proposed

## Submitters

- @bjohansebas
- @ulisesgascon

## Decision owers

- @expressjs/triage

## Context

A medida que el proyecto ha estado integrando a mas personas en el equipo de triage, ha sido complicado saber que etiquetas se deben usarse de acuerdo al issue o pull request, ya que han habido varias labels dentro de algunos repositorios que no tienen un nombre facil de entender y no tienen tampoco una descipción para dar mas contexto

**Why do we need this decision?**

Clarificando los labels que deben tener cada repositorio con su respectiva descripcion ayudara al equipo de triage a tomar mejores decisiones sobre que label de usar en cada caso

## Decision

Nosotro tendremos una lista de labels con su respectiva descripcion para cada repositorio, los cuales definiral 

Todos los repositorios:
- tc agenda
- discuss
- top priority
- meetings
- docs
- questions
- require-triage
- help wanted
- duplicate
- wontfix

Repositiorios que es un paquete npm:

- needs tests
- needs rebase
- needs docs
- ideas
- awaiting more info
- investigate
- semver-major
- semver-minor
- semver-patch 
- release
- future
- bug

Cada repositorio puede tener otros labels de acuerdo a sus necesidades