---
title:  Getting Started
layout: guide
permalink: /guides/1/
---

hyper is an HTTP library for the Rust language.

You can start using it by first adding it to your `Cargo.toml`:

```toml
[dependencies]
hyper = { version = "1", features = ["full"] }
```

- If building a web server, continue with the [Server guide][].
- If trying to talk to a server, continue with the [Client guide][].

You could also look at the [generated API documentaton][docs].

[docs]: {{ site.docs_url }}
[Server guide]: server/hello-world
[Client guide]: client/basic
