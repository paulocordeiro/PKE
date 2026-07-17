# PKE — Project Knowledge Engine

> An open specification for representing, planning, and delivering software project knowledge to AI agents.

[Português do Brasil](README.pt-BR.md)

## Status

PKE is in its founding and research phase. The project follows a **specification-first** approach: concepts and interoperability contracts are defined before a reference implementation.

## Motivation

Software project knowledge is distributed across source code, tests, architecture records, issues, pull requests, documentation, schemas, logs, and conversations. Sending more of these artifacts to an AI agent does not necessarily improve its decisions; it often increases cost, latency, contradiction, and loss of focus.

PKE aims to define how systems can:

1. represent project knowledge independently of its source;
2. determine the knowledge required for a task;
3. retrieve the smallest sufficient body of evidence;
4. assemble context for any compatible AI agent.

## Core position

**Knowledge is an asset. Context is a delivery mechanism.**

PKE is designed for AI-assisted development while remaining independent of model vendors, agent frameworks, IDEs, programming languages, and storage technologies.

## Working principles

The project is governed by the [Founding Principles](FOUNDING_PRINCIPLES.md), including **Knowledge Budget**: every new concept and artifact has a permanent maintenance cost and should eliminate more complexity than it introduces.

## Documentation languages

Normative and project-level documentation is maintained in:

- English, used as the default file;
- Brazilian Portuguese, identified by the `.pt-BR.md` suffix.

Both versions must preserve the same meaning. Differences should be treated as documentation defects.

## Current scope

The initial work is intentionally limited to:

- defining the problem and terminology;
- establishing the knowledge model;
- specifying knowledge planning and context assembly;
- defining an interoperable protocol;
- describing a reference architecture.

Implementation decisions remain open until the specification provides enough evidence to make them.

## License

Licensing will be selected before accepting external contributions or publishing normative specification releases.
