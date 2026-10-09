<p align="center"><img src="logo.svg" alt="Zap" width="128"></p>

<h1 align="center">Zap Grid</h1>

<p align="center">The grid that powers Zap: a language, an engine, and what is built with them.</p>

**Zap** is a compiled, statically typed language without a garbage collector. Memory is managed
by ownership and borrowing, inspired by Rust but without its lifetime syntax or borrow-checker
fights, in a clean syntax with few symbols. It aims to be fast enough to beat Rust on application
code and broad enough to write everything in one language, from a kernel or a driver to an
engine, a server, an app or a script. It is designed to be written by agents and reviewed by
humans: compact for the model, plain for the reader. The compiler is written in Zap and emits
native executables itself; shaders are written in Zap too.

Like a power grid, this organization connects the pieces that Zap energizes:

| Repository | What it is |
|---|---|
| [zap](https://github.com/zap-grid/zap) | The language: compiler, runtime, standard library, test suite and specification |
| [zap-engine](https://github.com/zap-grid/zap-engine) | A 2D, 2.5D and 3D engine over Vulkan 1.3 and Direct3D 12 |
| [zap-projects](https://github.com/zap-grid/zap-projects) | Programs built on the engine: a Super Mario 64 rewrite, a voxel world, a graphics lab and two MMOs |

Each repository is versioned with tags, and a repository names what it builds on in its
`zap.deps` file.
