# python-core#

## Purpose
Your Python depth lab. Every core Python concept gets a small file here with tests, then a CLI tool at the end proves you can use them together.

## Tracker tasks
OOP, typing and decorators, async, pytest and packaging, python-core CLI tool.

## Folder structure
```
python-core/
  notes/          one short .md per concept (what it is, when to use it)
  src/            exercises grouped by topic: oop/ typing/ decorators/ generators/ async/
  tests/          pytest file for every exercise
  cli_tool/       final CLI project
  pyproject.toml
```

## Daily input
- 1 concept: read or watch, then write a 10 to 20 line note in `notes/`
- 1 exercise in `src/` that uses the concept in a new way (not copied)
- 1 pytest test for it in `tests/`
- Commit message format: `topic: what you built`

Minimum on a bad day: one note and one test.

## Order
1. OOP (classes, inheritance, dataclasses, dunder methods)
2. Typing, decorators, generators, context managers
3. Async and concurrency basics
4. pytest, virtual environments, packaging
5. CLI tool with full tests

## Done when
- CLI tool works with tests passing
- You write new project code in Python without looking up basics

## Rules
- Type hints on every function
- No exercise without a test
- Write from memory first, then check the docs
