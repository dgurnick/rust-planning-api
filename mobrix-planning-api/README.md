# References
1. https://www.google.com/search?client=firefox-b-d&q=rust+axum+getting+started#fpstate=ive&vld=cid:30391433,vid:QtKO9f_iPhI
2. https://dev.to/alexeagleson/how-to-set-up-a-fullstack-rust-project-with-axum-react-vite-and-shared-types-429e
3. Tracing: https://blog.devgenius.io/adding-logging-and-tracing-to-an-axum-app-rust-d7935693bc3c
   
# Process
``` terminal
cargo new mobrix-planning-api
cargo add axum
cargo add serde --features derive
cargo add serde-json
cargo add tokio --features full
cargo add tower-http --features cors
```