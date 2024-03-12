# jm_phoenix_wiki

## Project
A project to investigate using Elixir and Phoenix to serve wiki pages.

Inspired by the Copenhagen Elixir group's project [pwiki_workshop](https://github.com/cphex/pwiki_workshop) from a few years back. In
2024, there may be better library choices for a Phoenix webapp.

Motivated by job readiness and relevance.

## Startup
```
cd wiki
mix phx.server
```
Starting in this mode includes a filesystem watch, restarting Phoenix on an update.

## Goals
* Learning Elixir using a familiar interaction mode (wiki).
* Portfolio.
* Personal workflow exercise. 
* Wiki domain
    * Bootstrapping it into a set of notes on itself.
    * Core features: serve, render, edit, link, navigate.
    * Implementation details: page model, HTTP, persistence.
    * Non-core: history, backlinks, tags, search, interop, static site.
* For details of these goal areas, see [goals](./goals.md).

## Approach

### Initial Bootstrapping
* [X] Pin some initial tasks here.
* [X] Create a project progress directory. [progress](./progress)
* [X] Start the project log. [progress/log](./progress/log.md)
* [X] Move further tasks to the progress directory [progress/tasks](./progress/tasks.md).

### Task Flow
I'm using kanban single-piece flow and Mitchell Hashimoto's demo driven development as general inspiration.

