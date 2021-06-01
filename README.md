# [collect-npm-readmes](https://joelpurra.com/projects/collect-npm-readmes/)

Copy a project's first-level `npm` package readme files to a separate directory for easy access.



> ## ⚠️ This project has been archived
>
> No future updates are planned. Feel free to continue using it, but expect no support.



- Looks in `./node_modules` by default.
- Collects all `README*` files.
- Copies the READMEs to `./node_module_docs` (automatically created) by default.
- [Project page](https://joelpurra.com/projects/collect-npm-readmes/)
- [Source code on github](https://github.com/joelpurra/collect-npm-readmes/)



## Installation


```bash
ln -s "${PWD}/src/collect-npm-readmes" "${HOME}/bin/"
```




## Get started


```bash
# Basic usage -- see ./node_module_docs for output.
collect-npm-readmes

# Specify output directory (will be created)
collect-npm-readmes "../../package-docs"

# Specify output directory path (will be created) and node_modules directory path.
collect-npm-readmes "../../package-docs" "../../../my-other-node-project"
```



## Kudos

- Thanks to Jeff ([@etisdew](https://github.com/etisdew)) for the project inspiration [on stream](https://www.twitch.tv/joelpurra).



---

Copyright &copy; 2018 [Joel Purra](https://joelpurra.com/). Released under [GNU General Public License version 3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl.html).
