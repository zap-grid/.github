<p align="center"><img src="logo.svg" alt="Zap" width="128"></p>

<h1 align="center">Zap Grid</h1>

<p align="center">The grid that powers Zap: a language, an engine, and what is built with them.</p>

**Zap** is a fast, compiled language without a garbage collector: ownership and borrowing manage
memory, the syntax is clean and light on symbols, and one language covers everything from a
kernel or a driver to an engine, a server, an app or a script. It is made to be written by agents
and read by humans, and the compiler does as much of the work as it can. Shaders are Zap too.

Like a power grid, this organization connects the pieces that Zap energizes:

| Repository | What it is |
|---|---|
| [zap](https://github.com/zap-grid/zap) | The language: compiler, runtime, standard library, test suite and specification |
| [zap-engine](https://github.com/zap-grid/zap-engine) | A 2D, 2.5D and 3D engine over Vulkan 1.3 and Direct3D 12 |
| [zap-projects](https://github.com/zap-grid/zap-projects) | Programs built on the engine: a Super Mario 64 rewrite, a voxel world, a graphics lab and two MMOs |

Each repository is versioned with tags, and a repository names what it builds on in its
`zap.deps` file.
