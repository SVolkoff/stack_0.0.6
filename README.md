[![Build Status](https://travis-ci.org/SVolkoff/stack-0.0.6.svg?branch=master)](https://travis-ci.org/SVolkoff/stack-0.0.6)

```
cmake -H. -B_builds -DBUILD_TESTS=ON -DBUILD_EXAMPLES=ON
cmake --build _builds
cmake --build _builds --target test -- ARGS=--verbose
_builds/example
```
