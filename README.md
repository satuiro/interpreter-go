# Creating an Interpreter in Go

This is an implementation of the Monkey programming language interpreter from the book "Writing An Interpreter In Go" by Thorsten Ball. The project is being built as a way to learn about interpreter design and implementation in Go.

## Current Status

The interpreter is currently in its early stages of development. Implemented components:

- [x] Lexer - Converts source code into tokens
- [x] Token definitions
- [x] Parser
- [ ] AST (Abstract Syntax Tree)
- [ ] Evaluator
- [ ] REPL

## Project Structure

```
.
├── lexer/
│   ├── lexer.go        # Lexical analysis implementation
│   └── lexer_test.go   # Tests for lexer
├── token/
│   └── token.go        # Token type definitions
└── go.mod
```

## Getting Started

### Prerequisites

- Go 1.x or higher

### Running Tests

```bash
go test ./...
```
