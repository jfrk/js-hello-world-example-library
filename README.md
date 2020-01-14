# JS library boilerplate

An example Javascript library that can be used as a boilerplate. Includes
transpilation of the source code for Node.js and bundling of a UMD version for
browsers.

## How to use

1. Run `yarn install` to install dependencies.
2. Replace `hello-world` and `HelloWorld` with strings matching your library
   name in the `build:umd` script inside _package.json_ and in the `<script>`
   tag inside _tests/browser.html_ if you want to keep that file.
3. Replace the content in the src folder with your library code with
   _src/index.js_ as the entry point for both Node.js and browsers (UMD).
4. Run `yarn build` to build Node and UMD versions.
