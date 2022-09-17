# ps

The `ps` command shows status of runs within the current Git repository.

### Usage

```shell
dstack ps [-a | RUN]
```

#### Arguments reference

The following arguments are optional and mutually exclusive:

-  `-a`, `--all` – (Optional) Show status of all runs
- `RUN` - (Optional) A name of a run

!!! info "NOTE:"
    If no arguments are specified, the command shows status of unfinished runs if any or otherwise the 
    last finished run.