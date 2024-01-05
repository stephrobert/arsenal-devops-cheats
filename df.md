# Disk Free (df)

Command-line tool used in Unix and Unix-like operating systems to display the
amount of available disk space for file systems.

#plateform/multiple #target/local #cat/SysAdmin

% Unix, Linux, disk space, system administration

## df - Display File System Disk Space Usage

Shows the amount of disk space used and available on file systems.

```
df
```

## df - Display in Human-Readable Format

Shows disk space in human-readable format (e.g., KB, MB, GB).

```
df -h
```

## df - Include File System Type

Includes the type of file system.

```
df -T
```

## df - Display Inodes Information

Shows inode usage information.

```
df -i
```

## df - Display Only Specified File System

Shows information about a specific file system.

```
df <filesystem|/var>
```

## df - Exclude File System Type

Excludes file systems of a specific type.

```
df -x <filesystem_type|ext4>
```

## df - Limit display to specified file system type

Includes file systems of a specific type.

```
df -t <filesystem_type|ext4>
```
