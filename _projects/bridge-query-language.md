---
title: "MathQL"
weight: 2
---

[MathQL](https://github.com/IMFM-SI/bridge-query-language) is a typed query language for asking questions about databases of mathematical objects.

A query names the objects it speaks about (graphs, maniplexes, and so on), states a condition they must satisfy, and says what to compute about each of them: the trees on five vertices, or the number of edges of every graph with more vertices than edges. MathQL type-checks the query, compiles it to SQL, and runs it against whatever database holds the objects. The engine is prototyped in Python, and the language is formalised in Lean, which serves as its precise specification.

MathQL is the query language spoken by [Bridge MCP](/projects/mcp/), through which AI agents ask their questions.
