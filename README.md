# enshpy

## About

Enshpy is the abbreviation of Enriched Shell Experience with Python.
This project's purpose is to improve the user experience of running shell commands
with additional Python interoperability.

Widely loved, shell commands are powerful and versatile tools backed by a
well-established battle-tested ecosystem. Many organizations have complicated
shell programs performing critical tasks. However, long, convoluted shell programs
are intimidating for alteration and maintenance, especially for newcomers who are
not original authors.

The purpose of this project is to improve the user experience of working with shell
commands. This is achieved by providing a Python wrapper around shell commands,
which enriches functionalities like execution, documentation, testing, and
monitoring. With this wrapper, a Shell program can be parsed and executed as a
calling graph of Python objects.

## Inspirations

This project heavily builds on the shoulders of giants:

Documentation:

- [Explain Shell](https://github.com/idank/explainshell) helps to explain shell
commands.
- [TLDR](https://github.com/tldr-pages/tldr) is a collection of community-maintained help pages for command-line tool

Linting:

- [shellcheck](https://github.com/koalaman/shellcheck) is a static analysis tool for shell scripts

Execution:

- [Invoke](https://github.com/pyinvoke/invoke) for invoking shell commands.

Parsing:

- [Bashlex](https://github.com/idank/bashlex) for parsing shell commands into AST.
- [pash](https://github.com/binpash/pash) for inspiration of shell translations and transformation.
