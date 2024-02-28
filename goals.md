# goals.md 

Expanded goals outline from [README](./README.md)

## Goals

### Why and How

* Learning Elixir using a familiar interaction mode (wiki).
* Portfolio. This might suggest reader-friendly project choices.
    * Testing
    * Factoring for Testability
    * Getting Code Reviews
    * Demonstration (and demo-driven task flow)
    * Deployment
* Personal workflow exercise. First four portfolio points and also:
    * Project log. What did I try, what did I learn, where did I link.
    * Information sources. Where and who, beyond hexdocs.pm ?
    * Many More Much Smaller Steps as inspiration, credit Michael D. "GeePaw" Hill.
        * Development as a conversation with the code and application.
        * Seek a sense of liveness. Test Often. Get Unstuck. 
        * Tidy First (Kent Beck) also points to refactoring.
        * [MMMSS First Sketch](https://www.geepawhill.org/2021/09/29/many-more-much-smaller-steps-first-sketch/)
    
### What

* Wiki domain
    * Bootstrapping it into a set of notes on itself.
    * Core features.
        * Serve and render pages.
        * Edit and link pages.
    * Implementation details.
        * Domain model.
            * A page in the app.
            * HTTP/app translation, persistence/app translation.
            * Canonical page title form aka "slug".
        * HTTP interaction
            * Configuring Phoenix, choosing helper libraries
            * HTTP Navigation model (slug as path fragment/param?).
        * Persistence model
            * page content, blop-o-markdown or something else?
            * page metadata, slug, tags, create, update, history?
    * Non-core features.
        * Non-wiki assets (images).
        * History, do we care?
        * Tags, do we care?
        * Search, do we care?
        * Export to static site.
        * Interoperative with MASVF / Obsidian vaults?

