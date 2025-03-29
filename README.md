# BindBC-OpenCL
Dynamic binding to OpenCL.

[![DUB Package](https://img.shields.io/dub/v/bindbc-opencl.svg)](https://code.dlang.org/packages/bindbc-opencl)
[![DUB Downloads](https://img.shields.io/dub/dm/bindbc-opencl.svg)](https://code.dlang.org/packages/bindbc-opencl)

# OpenCL version selection
BindBC-OpenCL supports OpenCL versions 1.0, 1.1, 1.2, 2.0, 2.1, 2.2. Version to load should be specified at compile time, for example:

```
"versions": ["CL_11"]
```
