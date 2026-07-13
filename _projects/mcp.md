---
title: "Bridge MCP"
weight: 1
---

[Bridge MCP](https://github.com/IMFM-SI/bridge-mcp) is a Model Context Protocol (MCP) server that enriches AI agents with mathematical knowledge.

It gives agents access to collections of mathematical objects through MathQL, a small, typed query language. A MathQL query names one or more domains of objects, states a condition the objects must satisfy, and lists the expressions to return; it is type-checked, compiled to SQL, and run against a bundled database of mathematical objects. The server installs as a single command and works with any MCP client, such as Claude Desktop.
