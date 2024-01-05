# sar (System Activity Report)

The `sar` command is part of the sysstat package and is used for collecting, reporting, and saving system activity information in Linux.
#plateform/multiple #target/local #cat/SysAdmin
% sysstat, performance monitoring, system statistics, Linux, command line

## sar - basic usage

To display CPU usage for the current day:

```
sar
```

## sar - display CPU usage at specific intervals and count

```
sar -u <interval|10> <count|5>
```

## sar - display memory usage

```
sar -r
```

## sar - display I/O transfer rates

```
sar -b
```

## sar - display network statistics

```
sar -n <dev|eth0>
```

## sar - display swap space usage

```
sar -S
```

## sar - display block device statistics

```
sar -d
```

## sar - display paging statistics

```
sar -B
```

## sar - generate a report for a specific time period

For historical data, specify the file with `-f` and the time range:

```
sar -f <file|/var/log/sysstat/sa10> -s 10:00:00 -e 12:00:00
```

## sar - save reports in a specified file

```
sar -o <file|sarfile>
```
