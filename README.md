
#### The Tree-sitter project itself provides four core pieces:

- A JavaScript library for writing grammars
- A tool for converting grammars into parsers
- A library for applications to use those parsers to parse text into syntax trees
- A Query language for introspecting the contents of those syntax trees
- [ref four core pieces](https://docs.nova.app/syntax-reference/tree-sitter/)

### To generate out the parser see this list of commands

[See this list of commands](https://github.com/tree-sitter/tree-sitter/blob/master/cli/README.md#commands)

### In the [tree-sitter-rust](https://github.com/stormasm/tree-sitter-rust) scripts directory run these scripts

* fetch-examples
* parse-examples

You can drop in the examples directory

* arrow-datafusion
* nushell

So that this rust code gets tested being parsed.
