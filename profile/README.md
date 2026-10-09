<p align="center"><img src="logo.svg" alt="Zap" width="128"></p>

<h1 align="center">Zap Grid</h1>

<p align="center">The grid that powers Zap: a language, an engine, and what is built with them.</p>

**Zap** is a fast, compiled programming language.

- **No garbage collector.** Ownership and borrowing free memory at known points.
- **Clean syntax.** Words instead of symbols, easy to read at a glance.
- **One language for everything.** Kernels, drivers, engines, servers, apps and scripts.
- **Made for agents.** Compact to write, plain for humans to review.
- **A compiler that does the work.** It infers, checks and optimises so the code doesn't have to.
- **Shaders in Zap too.** One language from the CPU to the GPU.

Like a power grid, this organization connects the pieces that Zap energizes:

| Repository | What it is |
|---|---|
| [zap](https://github.com/zap-grid/zap) | The language: compiler, runtime, standard library, test suite and specification |
| [zap-engine](https://github.com/zap-grid/zap-engine) | A 2D, 2.5D and 3D engine over Vulkan 1.3 and Direct3D 12 |
| [zap-projects](https://github.com/zap-grid/zap-projects) | Programs built on the engine: a Super Mario 64 rewrite, a voxel world, a graphics lab and two MMOs |

Each repository is versioned with tags, and a repository names what it builds on in its
`zap.deps` file.
