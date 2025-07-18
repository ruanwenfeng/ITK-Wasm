itk-convert
===========

Convert an image or mesh from one file format to another.

This package provides a command line executable, `itk-convert` to convert
image file formats with
[ITK-Wasm](https://github.com/InsightSoftwareConsortium/ITK-Wasm.git).

## Installation

```
npm install -g itk-convert
```

## Usage

```
itk-convert <inputFile> <outputFile>
```

## Development

```
cd ../..
pnpm install
pnpm build
cd examples/node-js
pnpm test
```

## More Information

This example demonstrates how to use
[ITK-Wasm](https://wasm.itk.org/) in a Node.js
application. More information can be found in the [example
documentation](https://docs.itk.org/projects/wasm/en/latest/typescript/distribution/node.html).
