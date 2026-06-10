# @bufbuild/protoplugin-transpile

This package is the transpilation backend of
[@bufbuild/protoplugin](https://www.npmjs.com/package/@bufbuild/protoplugin).
It transpiles TypeScript to JavaScript and TypeScript declaration files with
a pinned version of the TypeScript compiler for stable output.

It is internal infrastructure and not intended for direct use. To write your
own Protobuf code generator plugin, use
[@bufbuild/protoplugin](https://www.npmjs.com/package/@bufbuild/protoplugin)
instead.

The transpilation logic lives in its own package to isolate the pinned
compiler from the TypeScript version used to build `@bufbuild/protoplugin`
itself.
