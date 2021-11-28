# FBX2GLTF

Change skinning-weights to 4 if your engine does not support that feature.

Change the default import of the engine to be different from 30 fps if needed.

There are artifacts in the Github Actions for Windows, MacOS and Linux.

This is a build used with values according to the company's internal model values.

## Build Instructions

Reference the Github workflow.

```bash
conan install . -i build -s build_type=Release -s compiler.cppstd=17 -s compiler.runtime=static --build=missing
```