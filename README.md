# Builder - C++ and Python

**Builder** is a reusable `Go` package that fully automates the build process for
mixed-language source projects. It abstracts away the complexity of invoking
`CMake`, `Ninja`, and `Python` packaging tools, enabling developers to easily
build, test, and replicate environments across different branches or commits
with minimal effort.

Using a single Go-based configuration script, users define their build
parameters declaratively. Builder then handles the heavy lifting—managing
isolated build directories, orchestrating compilation stages, resolving
Python dependencies, and ensuring deterministic, reproducible outputs.

Designed as a pure Go library, Builder integrates seamlessly into any Go
application, toolchain, or CI/CD pipeline.

> **Scope**: The current stable version is explicitly tailored for C++
> (via `CMake`/`Ninja`) and Python (via virtual environments and `pip`). Support
> for additional languages is planned for future iterations.

## ROADMAP (v0.1.0 - Alpha)

- [ ] Invoke `Cmake`
- [ ] Invoke `Ninja`
- [ ] Invoke `pip` in a `venv`
