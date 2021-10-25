# The JDX Project

The JDX Project was created to make storing large categorical datasets of images much easier. Currently, it consists of three tools/libraries that allow you to interact with JDX files (distinguished with the extension `.jdx`). The underlying library is [libjdx](https://github.com/jeffreycshelton/libjdx), which is written in C and can be used freely in personal projects. All wrappers are derivates of libjdx, including [jdx-rust](https://github.com/jeffreycshelton/jdx-rust), the Rust wrapper for JDX. The [JDX CLT](https://github.com/jeffreycshelton/jdx-clt), also written in Rust and built on the Rust wrapper, is the command line tool for interacting with JDX files. It can generate, expand, summarize, and concatenate JDX files among other functions.

## Development

The JDX Project is in the alpha development phase. If you want to contribute by creating a new tool/wrapper or adding features and fixes to existing JDX projects, please do! Contributions and issues help to make JDX a more capable format and its accompanying tools more useful.

## License

The JDX Project and all subprojects are licensed under the [MIT License](LICENSE).