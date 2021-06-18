# BashSupport Pro
This is the public issue tracker of the [BashSupport Pro](https://www.bashsupport.com/pro) plugin.

BashSupport Pro is **a plugin for advanced Bash and shell script development** — debugger, test runner, code completion, find usages, rename, ShellCheck, shfmt, and more. 

[docs](https://www.bashsupport.com/pro/) · [install instructions](https://www.bashsupport.com/pro/installation/) · [features](https://www.bashsupport.com/pro/features/) · [bug tracker](https://github.com/BashSupport-Pro/bashsupport-pro/issues) · [free licenses](https://www.bashsupport.com/pro/free-license/)
<br>

- **bashdb Debugger**: Debug Bash scripts with bashdb on macOS, Linux, and Windows (WSL, Git Bash, Cygwin).
- **bats-core Test Runner**: Run bats-core tests on macOS, Linux, and Windows (WSL, Git Bash, Cygwin).
- **ShellCheck Support**: [ShellCheck](https://github.com/koalaman/shellcheck) is bundled and used to highlight problems in script files.
- **shfmt Formatter**: [shfmt](https://github.com/mvdan/sh) is bundled and is used to format script files.
- **Powerful Run Configurations**: Run inline snippets, define stdin redirection, control logging, works well on Windows (WSL, Git Bash, Cygwin) and can be shared cross–platform.
- **Legacy Run Configurations**: Run configurations of legacy BashSupport and of JetBrains Shell are supported without the plugins being installed. 
- **Multi-File Navigation**: All features support sourced files: go to definition, rename, find usages, completions, etc. The `shellcheck source=` directive is used to support dynamic path values.
- **Go To Definition**: Supports `unset` and definitions by assignments, `export`, `typeset`, `declare`, `local`, `getopts`, `mapfile`, `read`, `readonly`, and `select`.  
- **Advanced Code Completion**: it only suggests functions and variables, which are valid at the current position in your script.
- **Rename**: Rename files, functions, variable definitions, and variable references without breaking your scripts.
- **Find Usages**: Find usages of your functions and variables in your scripts, sourced files and files sourcing the file.
- **Quick Documentation**: View documentation of your functions, variable, built-ins (`help`), and commands (`info`).
- **Inspections** (beta): Find unresolved references. Highlight variables, which could be `local`.   
- **Code Folding**: Powerful code folding to help you edit large scripts.
- **Helpers**: Intentions, inspections, line markers for recursive calls, editor breadcrumbs, navigation bar breadcrumbs, and more.

<br>Please refer to [bashsupport.com](https://www.bashsupport.com/pro/) for the complete documentation and an overview of all available features.
