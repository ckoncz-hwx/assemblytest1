# Run maven assembly:single in a multimodule project

Some modules might not need to assemble anything.

The three branches of this repo show three solutions (combinations of `skipAssembly` and `ignoreMissingDescriptor`)

```
mvn assembly:single
```