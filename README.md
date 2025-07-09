rust-static-reflect
====================
Compile-time reflection in rust!

The original use case is type-checking generated code in a JIT compiler (with zero runtime cost).
However, other use cases are certainly possible :)

Contributions are welcome!
I'd be happy to add more features as long as they align with the general philosophy
of compile-time reflection.

Unfortunately, there is very little documentation right now.
Hopefully, that will change in the future.

## Related Projects
- [facet](https://github.com/facet-rs/facet) - Very similar, much more recent, appears very high quality. *Unsound*: Does not require `#[repr(C)]` to manipulate type layout.
- [const-type-layout](https://github.com/juntyr/const-type-layout) - Similar, but far more complex use of type system. Requires specialization and many other nightly features.

## License
Licensed under either the [Apache 2.0 License](./LICENSE-APACHE.txt) or [MIT License](./LICENSE-MIT.txt) at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in this project by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
