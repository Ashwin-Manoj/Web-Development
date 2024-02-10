# Here i will address the problems i faced while working on this tutorial and it's solutions

## 1. Using MySQL from CLI

> Problem:

- The command suggested in the course video was not working because, that `PATH` did not exist in my machine.
- Command showed in the course

```bash
$ /usr/local/mysql/bin/mysql -u root -p
 ```

> Solution:

- I found the base directory from the `MySQL` in the settings, from there i found the right `PATH`.

```bash
$ /usr/local/mysql-8.3.0-macos14-arm64/bin/mysql -u root -p
```
---
