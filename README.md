# User Guide for todo.txt file

## Reference

- About the format: [[Original]](https://github.com/todotxt/todo.txt/blob/master/README.md) [[Mirror]](CONCEPT.md)
- Usage of todo.txt-cli: [[Original]](https://github.com/todotxt/todo.txt-cli/blob/master/USAGE.md) [[Mirror]](USAGE.md)

## Installation

```bash
brew install todo-txt
cp -n /usr/local/opt/todo-txt/todo.cfg ~/.todo.cfg
```

## Get Started

1. Config config to **~**, edit `$TODO_DIR` in **~/.todo.cfg**
2. Add alias in *rc `alias td=todo.sh`
3. Add task `td a my things +project`
4. List task `td ls`
