DarvinDatabaserBundle
=====================
This bundle integrates "darvinstudio/databaser" with Symfony.

## Usage

### Pull database

```shell
$ /usr/bin/env php bin/console databaser:pull [-k|--key [KEY]] [-p|--password] [-P|--port [PORT]] <user@host> <project_path_remote> [<project_path_local>]
```

Examples:

```shell
$ /usr/bin/env php bin/console databaser:pull root@example.com www/example.com
$ /usr/bin/env php bin/console databaser:pull -P 123 root@example.com /var/www/example.com
```

### Push database

```shell
$ /usr/bin/env php bin/console databaser:push [-k|--key [KEY]] [-p|--password] [-P|--port [PORT]] <user@host> <project_path_remote> [<project_path_local>]
```

Examples:

```shell
$ /usr/bin/env php bin/console databaser:push root@example.com www/example.com
$ /usr/bin/env php bin/console databaser:push -P 123 root@example.com /var/www/example.com
```
