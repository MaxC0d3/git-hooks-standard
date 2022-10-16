# Git hooks standard 

Here you will find hooks to verify rules before pushing to the local repository.



## Hooks availables

- Check commit standard message: *commit-msg*
- Check lint, code style, unit test: *pre-commit* **(for Rust)**


## commit-msg

### Examples 

![2022-10-15_20h56_35](https://user-images.githubusercontent.com/43556246/196014252-02f55ff2-56f5-4531-8f75-4f2a9dc402cb.png)

![2022-10-15_20h57_22](https://user-images.githubusercontent.com/43556246/196014264-19d5b4f1-ebe9-49df-982d-72665fda9c31.png)

Hook to verify that the commit message complies with the standard.

### Installation commit-msg on your proyect

- First, go to the folder of the project in which you want to install the hook
- Make sure your git repository is initialized
- Now run the following command 👇

```sh
 $ curl https://raw.githubusercontent.com/MaxC0d3/git-hooks-standard/main/commit-msg -o ./.git/hooks/commit-msg
```
#### Commit standard prefixes


| Prefixes  | Description                |
| :-------- | :------------------------- |
| `feat` | A new user feature |
| `fix`  |Fixes a bug that affects the user|
| `perf`  | Changes that improve site performance |
| `build`  | Changes in build system, deployment or installation tasks |
| `ci`  |Changes in continuous integration |
| `docs`  | Changes in documentation |
| `refactor`  | Code refactoring such as variable or function name changes |
| `style`  | Formatting changes, tabs, spaces or semicolons, etc; do not affect the user |
| `test`  | Add tests or refactor an existing one |

## Authors

- [@MaxC0d3](https://www.github.com/MaxC0d3)
- [@04l3x](https://www.github.com/04l3x)


