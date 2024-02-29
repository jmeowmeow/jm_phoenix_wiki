# log.md - Project Log

Wed 28 Feb 2024 11:23:56 AM PST
* Set up project structure and README with goals and initial tasks.
* Create progress directory with [log.md](./log.md) (this file) and [tasks](./tasks.md).

Wed 28 Feb 2024 01:15:08 PM PST
* `:r! date` in vi/Unix to datestamp (a reminder). There's a vim builtin too.
* Initial commit with a break-out of [goals](../goals.md) and [taskflow](../taskflow.md).

Thu 29 Feb 2024 02:20:38 PM PST
* Setting up to pair and do an initial install of a Phoenix project `mix phx.new wiki`
* Walked through plan, did an initial `mix phx.new --no-ecto wiki` (deferring DB config).

Thu 29 Feb 2024 03:39:34 PM PST
* Switched from "cowboy" to "bandit" for HTTP interface. See [Bandit.PhoenixAdapter](https://hexdocs.pm/bandit/Bandit.PhoenixAdapter.html). Needed a `mix deps.get`. Removed the Cowboy plug dep.


