# du (disk utilization)

Disk utilization (`du`) is a standard Unix/Linux command used to estimate file
space usage—space used under a particular directory or files on a file system.

#plateform/multiple #target/local #cat/SysAdmin

% linux, unix, disk usage, file system, command line


## du - basic usage

To display the disk usage of files and directories:

```
du
```

## du - display disk usage in human-readable form

```
du -h
```

## du - summarize disk usage of each file

```
du -s
```

## du - display disk usage of a directory

```
du <path|/var>
```

## du - display disk usage in bytes

```
du -b
```

## du - display disk usage for all files and directories recursively

```
du -a
```

## du - display disk usage and exclude files matching a pattern

```
du --exclude=<pattern|*.ignore>
```

## du - display disk usage of a directory, including all subdirectories

```
du -c <path|/var>
```
