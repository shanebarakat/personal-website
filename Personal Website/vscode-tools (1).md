# Vscode Tools

## Vscode commands:

* **Ctrl + /:** New comment
* **Alt + Shift + a:** Wraps the currently selected text in comments
* **Alt+ z:** makes lines not run off the screen
* **Ctrl + Shift + o:** Removes all unneeded imports
* **Alt + UP/DOWN:** Moves the selected line up and down
* **Ctrl + Alt + UP/DOWN:** Makes multiple cursors
* **Ctrl + B:** show or hide file manager
* **Alt + Shift + F:** Auto formats selected text
* **Alt + Shift + DOWN:** duplicate a line


## Useful Extensions:

* **GitLens:**  Git Extension used for visualizing and updating changes to file in Git repositories
* **ESLint:**  JavaScript Code analysis tool that can be used to identify problems before runtime
* **Prettier:**  A Extension that allows for the best code formatting (Alt + Shift + F)
* **MobileView:** opens a emulated mobile device view where you can see your webapp running on mobile devices
* **Even Better Toml:** .toml file support plugin
* **VS Code Icons:** Adds icons to all of your files in the file browser
* **TODO Tree:** Adds a todo searcher that looks through all your documents for the keyword TODO
* **Live server:** launches a live server for your HTML files (No need for React as it is built in)
* **File-tree-generator:** Generates a file tree for your projects so you can input it into a README
* **Path Intellisense:** Intellisense for file paths


## Security Commands:

[Mega-Linter](https://megalinter.io/latest/mega-linter-runner/): Amazing safety linter that works with almost every language, 

```bash
 npx mega-linter-runner --flavor javascript  -e 'SHOW_ELAPSED_TIME=true'
```



:::warning
Docker is required to run this command, if on windows install [Docker Desktop](https://www.docker.com/products/docker-desktop/)

:::


To change languages simply change the flavor variable to one of the following,



| **Flavor** | **Description** | **Embedded linters** | **Info** |
|----|----|----|----|
| [all](https://megalinter.io/7.11.1/supported-linters/) | Default MegaLinter Flavor | 122 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter) |
| [c_cpp](https://megalinter.io/latest/flavors/c_cpp/) | Optimized for pure C/C++ projects | 55 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-c_cpp/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-c_cpp/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-c_cpp) |
| [ci_light](https://megalinter.io/latest/flavors/ci_light/) | Optimized for CI items (Dockerfile, Jenkinsfile, JSON/YAML schemas,XML | 21 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-ci_light/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-ci_light/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-ci_light) |
| [cupcake](https://megalinter.io/latest/flavors/cupcake/) | MegaLinter for the most commonly used languages | 84 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-cupcake/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-cupcake/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-cupcake) |
| [documentation](https://megalinter.io/latest/flavors/documentation/) | MegaLinter for documentation projects | 51 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-documentation/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-documentation/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-documentation) |
| [dotnet](https://megalinter.io/latest/flavors/dotnet/) | Optimized for C, C++, C# or VB based projects | 64 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-dotnet/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-dotnet/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-dotnet) |
| [dotnetweb](https://megalinter.io/latest/flavors/dotnetweb/) | Optimized for C, C++, C# or VB based projects with JS/TS | 73 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-dotnetweb/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-dotnetweb/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-dotnetweb) |
| [formatters](https://megalinter.io/latest/flavors/formatters/) | Contains only formatters | 17 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-formatters/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-formatters/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-formatters) |
| [go](https://megalinter.io/latest/flavors/go/) | Optimized for GO based projects | 53 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-go/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-go/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-go) |
| [java](https://megalinter.io/latest/flavors/java/) | Optimized for JAVA based projects | 54 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-java/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-java/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-java) |
| [javascript](https://megalinter.io/latest/flavors/javascript/) | Optimized for JAVASCRIPT or TYPESCRIPT based projects | 60 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-javascript/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-javascript/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-javascript) |
| [php](https://megalinter.io/latest/flavors/php/) | Optimized for PHP based projects | 54 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-php/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-php/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-php) |
| [python](https://megalinter.io/latest/flavors/python/) | Optimized for PYTHON based projects | 64 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-python/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-python/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-python) |
| [ruby](https://megalinter.io/latest/flavors/ruby/) | Optimized for RUBY based projects | 51 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-ruby/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-ruby/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-ruby) |
| [rust](https://megalinter.io/latest/flavors/rust/) | Optimized for RUST based projects | 51 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-rust/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-rust/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-rust) |
| [salesforce](https://megalinter.io/latest/flavors/salesforce/) | Optimized for Salesforce based projects | 55 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-salesforce/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-salesforce/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-salesforce) |
| [security](https://megalinter.io/latest/flavors/security/) | Optimized for security | 24 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-security/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-security/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-security) |
| [swift](https://megalinter.io/latest/flavors/swift/) | Optimized for SWIFT based projects | 51 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-swift/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-swift/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-swift) |
| [terraform](https://megalinter.io/latest/flavors/terraform/) | Optimized for TERRAFORM based projects | 55 |  ![Docker Image Size (tag)](https://img.shields.io/docker/image-size/oxsecurity/megalinter-terraform/v7.11.1)[ ](https://img.shields.io/docker/image-size/oxsecurity/megalinter-terraform/v7.11.1) ![Docker Pulls](https://img.shields.io/docker/pulls/oxsecurity/megalinter-terraform) |


SVG REPO: <https://www.svgrepo.com/> 