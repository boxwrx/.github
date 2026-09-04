# Box Works

Box Works is a collection of free-use repositories defining development environments that will run as
local Docker Development Containers, GitHub Codespaces, and Google Cloud Shells.
These environments provide a platform for teaching and mentoring these languages, and also function
as general sandboxes for programmers to play with.
While it is always possible and recommended for the long term to construct a local development environment,
using these virtual containers handles the heavy-lifting for getting started.

Docker Development Containers and GitHub Codespaces use Visual Studio Code in the browser as the interface to connect with the virtual environment.
Google Cloud Shell uses Code OSS, the open source project that VS Code is built on top of, so it is a compatible environment.
When deployed each repository initializes a virtual container using Debian Linux, configured with the appropriate tools for
coding and debugging the specific language.
More information about how VS Code and Code OSS function in this environment is available
here: <a href="https://code.visualstudio.com/docs/devcontainers/containers">https://code.visualstudio.com/docs/devcontainers/containers</a>.
These environments support building both server-side and single-page web applications, as the serving ports
are exposed externally: local for a local Docker container, and across the Internet for a Codespace or Cloud Shell.

GitHub Codespace and Google Cloud Shell environments are configured automatically in the cloud.
Local implementation requires Visual Studio Code and Docker to be installed.
Follow these [instructions for setting up a local environment](./local_install.md).

These repositories may be freely used as the base for lab environments for specific courses.
Some of these derivatives may be hosted here at Box Works, others by the course owners in their own organizations.

Supported environments include:

* Ada
* [C/C++](https://github.com/boxwrx/clang-devbox)
* Go
* Java
* .NET/C#
* Node.js (JavaScript/TypeScript)
* PHP
* Python
* Ruby
* Rust
* Swift

## License

The code is licensed under the MIT license. You may use and modify all or part of it as you choose, as long as attribution to the source is provided per the license. See the details in the [license file](./LICENSE.md) or at the [Open Source Initiative](https://opensource.org/licenses/MIT).

---
Copyright &copy; 2026 Smallrock Internet Services, Inc. All rights reserved.