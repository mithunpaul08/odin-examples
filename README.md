# Rule-based event extraction with `odin`

This project provides an introduction of how to use `odin` and `rune` with several domains.

## What is `odin`?
`odin` is a system for open-domain information extraction.  
It uses a novel rule language (`rune`) to define regex-style patterns over both underlying syntactic structures and surface structures (sequences of tokens).  
Though it can be used as a standalone named entity recognizer, `odin`'s true strength is event extraction.

Primary authors:
 - [Marco Valenzuela](https://github.com/marcovzla)
 - [Gus Hahn-Powell](https://github.com/myedibleenso)
 - [Mihai Surdeanu](http://surdeanu.info/mihai/)

## What you'll need...
  1. [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html)
  2. [sbt](http://www.scala-sbt.org/release/tutorial/Setup.html)
  3. [`processors`](https://github.com/clulab/processors.git).

## Example domains

The domain examples are found under [`toydomains`](src/main/scala/toydomains).  The corresponding grammars should be under [`resources/grammars`](src/main/resources/grammars).

Run any of the examples with `sbt run`

|__Domain__ | __Description__|
|--------|----------------|
|[`bio`](src/main/scala/toydomains/bio) | A very simple introduction that uses the biology domain |
| [`likelihood`](src/main/scala/toydomains/general) | How likely or reliable is an event mention?  In this example, we look at how we might label events in terms of their likelihood.  This example also shows how to use a grammar with a master file, taxonomy, imports, and variables. |

## Project skeletons

Ready to get serious?  Use one of these branches to start your own project with `odin`.

|__Branch__ | __Description__|
|--------|----------------|
| `skeleton` | A bare-bones project for you to fork |


## `rune`
Learn more about our rule language.

_coming soon_

## Contribute

Help us spread the good word.  Fork this repo, develop your own example project, and put in a pull request.