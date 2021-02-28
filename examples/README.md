## Examples
For specific details see corresponding READMEs.

Consider first looking at [Counter](./counter).

Most of the examples can be run by simply:
```sh
cd examples/$EXAMPLE_DIR
cargo make start
```

### [Homepage repo](https://github.com/seed-rs/seed-rs.org)
The Seed homepage, also serving as an example. Includes simple
interactions, markdown elements, routing, and view markup.

### [Animation](animation)
How to make a basic animation with random generators.

### [Bunnies](bunnies)
Intended as a demo of [Shipyard](https://github.com/leudz/shipyard) (Entity Component System) integration.

### [Canvas](canvas)
How to make a canvas element and use `ElRef`s.

## [Component builder](component_builder)
How to write reusable views / components with builder pattern.

### [Counter](counter)
Intended as a demo of basic functionality.

### [Custom Elements](custom_elements)
How to create and use custom elements.

### [Drag And Drop](drag_and_drop)
How to drag and drop simple items.

### [Drop Zone](drop_zone)
How to create a drop-zone.

### [Element Key](el_key)
How to control a DOM update using element keys and empty nodes.

### [I18N](i18n)

How to support multiple languages in your web app based on [Fluent][url_project_fluent]. 
Includes a language selector, some sample text and [FTL strings][url_ftl_syntax_guide] 
demonstrating the simplicity and power of [Seed][url_project_seed] 
powered by [Fluent's Rust crate][url_crate_fluent].

[url_project_fluent]: https://projectfluent.org/
[url_crate_fluent]: https://docs.rs/fluent/
[url_ftl_syntax_guide]: https://projectfluent.org/fluent/guide/
[url_project_seed]: https://seed-rs.org/

### [Markdown](markdown)
How to render markdown.

### [Pages](pages)
How to create and browse multiple pages in your app.

### [Pages with hash routing](pages_hash_routing)
How to create and browse multiple pages in your app.
This example uses hash routing.

### [Pages that keep their state](pages_keep_state)
How to create and browse multiple pages in your app.
Pages keep their state.

### [ResizeObserver](resize_observer)
How to use [ResizeObserver](https://developer.mozilla.org/en-US/docs/Web/API/ResizeObserver).

## [Rust from JS](rust_from_js)
How to call Rust functions from Javascript.

### [Subscribe](subscribe)
How to create and use subscriptions, streams, notifications and commands.

### [TEA component](tea_component)
How to write a component in The Elm architecture.
You'll also learn how to pass messages to the parent component.

### [Tests](tests)
How to test your app.

### [Fetch](fetch)
How to make HTTP request using Fetch API.

### [NoChange](no_change)
How to increase render speed by `Node::NoChange`.

## [Record Screen](record_screen)
How to record the screen using the [Screen Capture API](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API/Using_Screen_Capture).

### [Todo MVC](todomvc)
Classic TodoMVC example with Local Storage.

### [Unsaved changes](unsaved_changes)
How to prevent navigating away when there are unsaved changes on the website.

### [Update from JS](update_from_js)
How to trigger `update` function from Javascript world.
You'll also see how to call JS functions from Rust.

### [Url](url)
Intended as a demo of Url functions and browser navigation.

### [UserMedia](user_media)
How to show your webcam output in `video` element.

### [Window Events](window_events)
A demonstration of event-handlers attached to the `window`.

## Server
Backend server integration & interaction examples.

### [Service Worker](service_worker)
Service worker integration demo. Includes registration, asset caching, state change messaging and notification subscription.

### [Auth](auth)
How to implement login / logout.

## [E2E encryption](e2e_encryption)
Demonstrates how to register, log in and communicate with the server over an unsecured network.

### [GraphQL](graphql)
How to communicate with a GraphQL backend.

### [Integration](server_integration)
Example of a workspace with [Actix](https://actix.rs/) server.

### [Websocket Chat](websocket)
Example of communicating with a server using WebSockets.
