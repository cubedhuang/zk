# JSON Requests in Rust

Rust's language design is cool but it doesn't come with a lot of implemented defaults. To make a request and return a struct, you need to use `reqwest` to make the request, `serde` to define the layout of the struct along with `serde_json`, and `tokio` as an async runtime.

I learned this when working on [[rust-nimi]].
