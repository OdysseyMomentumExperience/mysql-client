Container image with mariadb/mysql client tools.

To execute mysql command line tools inside docker or Kubernetes.

Alpine based image, with mysql-client and some other tools installed.
(In recent Alpine, mysql-client is provided by mariadb).

Default entry point is `mysql` command, but image contains other tools like `mysqldump`, `mysqladmin`, etc.

```console
docker run --rm --interactive --tty ghcr.io/OdysseyMomentumExperience/mysql-client:latest --host db --user root -p
```
