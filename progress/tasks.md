# Taskboard

Initial set-up as task list. See [taskflow](../taskflow.md) for a
notion of how and why to break down tasks, suggesting details to
work out once the project is in the circle of life. See [goals](../goals.md) for needs in the area of developer environment, wiki domain, and feasibility investigation which could generate deliverables and tasks.

* [X] Set up git repo structure.
* [X] Create a tabular links file [./links](./links.md) for project information sources. Maybe this ends up in the wiki later.
* [X] Add Elixir links (hexdocs.pm, elixir-lang.org, phoenixframework.org) to the links file.
* [X] Publish to GitHub. Maybe to Sourcehut later on.
* [X] Add Phoenix how-to and docs links to the links file.

Re-setting the following after updating Elixir and Phoenix versions. See [log](./log.md) and [./links](./links.md)

* [X] Read about how to start a Phoenix webapp project.
* [X] Install Phoenix and prerequisites.
* [X] Database or no database? What happens if we say no now? _No DB yet, I think._
* [X] Initialize a Phoenix hello-world project. `mix phx.new --umbrella --no-ecto wiki`
* [X] Run: `cd wiki_umbrella; mix phx.server` also watches for changes and rebuilds (== devserver task)
* [X] Change home page template colors. `wiki_umbrella/apps/wiki_web/lib/wiki_web/controllers/page_html/home.html.heex` . Phoenix instantly reloads.
* [X] Find out how to add/use Elixir (mix) build and test targets. [phoenix mix test](https://hexdocs.pm/phoenix/testing.html) See also [phoenix assets](https://hexdocs.pm/phoenix/asset_management.html)
* [ ] Next: Routes?
