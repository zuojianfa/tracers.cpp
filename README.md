# tracers.cpp

> `tracers.cpp` is a visualization library for C++.

This repository is part of the project [Algorithm Visualizer](https://github.com/algorithm-visualizer).

## Dependencies

- [nlohmann/json](https://github.com/nlohmann/json)

- [libcurl](https://curl.haxx.se/libcurl/)

## Installation

1. Download and extract the source code in the [latest release](https://github.com/algorithm-visualizer/tracers.cpp/releases/latest).

2. Change directory to it and run:

```bash
mkdir build

cd build

cmake ..

make install
```

## Usage

```cpp
#include "algorithm-visualizer/LogTracer.h"

int main() {
    LogTracer logTracer = LogTracer("Scratch Paper");

    logTracer.print("Visualize your own algorithm here!");

    return 0;
}
```

Check out the [API reference](https://github.com/algorithm-visualizer/algorithm-visualizer/wiki) for more information.

## Contributing

Check out the [contributing guidelines](https://github.com/algorithm-visualizer/tracers.cpp/blob/master/CONTRIBUTING.md).