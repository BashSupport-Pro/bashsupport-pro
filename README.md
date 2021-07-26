# BashSupport Pro
**This is the public issue tracker of the [BashSupport Pro](https://www.bashsupport.com/) plugin.**

BashSupport Pro is **a plugin for advanced Bash and shell script development** – debugger, test runner, code completion, find usages, rename, ShellCheck, shfmt, and more. 

<br>[manual](https://www.bashsupport.com/manual/) · [install instructions](https://www.bashsupport.com/manual/installation/) · [features](https://www.bashsupport.com/features/) · [bug tracker](https://github.com/BashSupport-Pro/bashsupport-pro/issues) · [free licenses](https://www.bashsupport.com/pricing/#open-source-and-academia)
<br>
<br>

- **bashdb Debugger**: Debug Bash scripts with bashdb on macOS, Linux, and Windows with WSL, Git Bash, or Cygwin ([manual](https://www.bashsupport.com/manual/debugger/)).
- **bats-core Test Runner**: Run bats-core tests on macOS, Linux, and Windows with WSL, Git Bash, or Cygwin ([manual](https://www.bashsupport.com/manual/bats-core/)).
- **ShellCheck Support**: [ShellCheck](https://github.com/koalaman/shellcheck) is bundled and used to highlight problems in script files ([manual](https://www.bashsupport.com/manual/editor/shellcheck/)).
- **shfmt Formatter**: [shfmt](https://github.com/mvdan/sh) is bundled and is used to format script files ([manual](https://www.bashsupport.com/manual/editor/formatter/)).
- **Google Shell Style Guide** support: Inspections, quick fixes, and a formatter preset help you follow the [Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html) in your Bash scripts ([manual](https://www.bashsupport.com/manual/google-style-guide/)). 
- **Powerful Run Configurations**: Run inline snippets, define stdin redirection, control logging, works well on Windows (WSL, Git Bash, Cygwin) and can be shared cross–platform ([manual](https://www.bashsupport.com/manual/run/)). Run configurations of **legacy BashSupport** and of **JetBrains Shell** are supported without the plugins being installed ([manual](https://www.bashsupport.com/manual/run/legacy-bashsupport/)).
- **Multi-File Navigation**: All features support sourced files: go to definition, rename, find usages, completions, etc. The `shellcheck source=` directive is used to support dynamic path values ([manual](https://www.bashsupport.com/manual/navigation/)). User-defined **[shell script libraries](https://www.bashsupport.com/manual/navigation/libraries/)** and [project variables]() support you with complex setups.
- **Go To Declaration**: Supports definitions by assignments, `export`, `typeset`, `declare`, `local`, `getopts`, `mapfile`, `read`, `readonly`, `select`, `printf`, and `coproc`. `unset` is also handled ([manual](https://www.bashsupport.com/manual/navigation/declaration/)).
- **Advanced Code Completion**: it only suggests functions and variables, which are valid at the current position in your script ([manual](https://www.bashsupport.com/manual/editor/code-completion/)).
- **Rename**: Rename files, functions, variable definitions, and variable references without breaking your scripts.
- **Find Usages**: Find usages of your functions and variables in your scripts, sourced files and files sourcing the file ([manual](https://www.bashsupport.com/manual/navigation/find-usages/)).
- **Quick Documentation**: View documentation of your functions, variable, built-ins (`help`), and commands (`info`) ([manual](https://www.bashsupport.com/manual/editor/documentation/)).
- **Inspections**: Find unresolved references, locate unused global variables, or quickly find variables, which could be `local` ([manual](https://www.bashsupport.com/manual/inspections/)).   
- **Code Folding**: Powerful code folding to help you edit large scripts ([manual](https://www.bashsupport.com/manual/editor/code-folding/)).
- **Helpers**: Intentions, inspections, line markers for recursive calls, editor breadcrumbs, navigation bar breadcrumbs, and more.

<br>Please refer to [bashsupport.com](https://www.bashsupport.com/) for the complete documentation and an overview of all available features.
