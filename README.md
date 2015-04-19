# clock

Track your working hours on the command line

# Install

Available as a [bpkg](http://www.bpkg.io/)
```sh
bpkg install [-g] lordvlad/clock
```

# Usage
```sh
clock <command> [<task>] [-m <message>] [-f <clockfile>] [-t <dir>]
```

## Commands
-  `clock help`    show the help
-  `clock in`      clock in, will clock out any running task
-  `clock out`     clock out
-  `clock log`     show all log entries, or log entries for `<task>`
-  TODO `clock list`    show sums for all tasks

## Task
  If no task is specified, the current working directory
  will be used as task specifier

## Options
-  `-m|--message`      record additional message when clocking in/out
-  `-f|--file`         where to save the clocks, defaults to $HOME/.clocks
