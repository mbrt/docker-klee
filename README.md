# docker-klee

Minimal Docker image for [KLEE](http://klee.github.io/) with LLVM 3.4 on Ubuntu Trusty.

## Usage

Run this image from within your workspace. You can than build your test files using `clang -emit-llvm`, and then test it with KLEE commands: `klee`, `ktest-tool`, etc. 

```
cd your/workspace
docker run --rm -tiv `pwd`:/work mbrt/klee
```

## License

Mit. See [LICENSE](https://github.com/mbrt/docker-klee/blob/master/LICENSE) file.
