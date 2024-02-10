# Here i will address the problems i faced while working on this [tutorial](https://www.apnacollege.in/course/delta-feb-24) and it's solutions

## 1. Using MySQL from CLI

> Problem:

- The command suggested in the course video was not working because that `PATH` did not exist on my machine.
- Command showed in the course

```bash
$ /usr/local/mysql/bin/mysql -u root -p
 ```

> Solution:

- I found the base directory from `MySQL` in the settings, and from there i found the right `PATH`.

```bash
$ /usr/local/mysql-8.3.0-macos14-arm64/bin/mysql -u root -p
```
---
