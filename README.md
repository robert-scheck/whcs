# Web Hosting Control Scripts (WHCS)

## About

The Web Hosting Control Scripts (WHCS) are a collection of small Bash scripts for managing simple Apache HTTP server virtual hosts with PHP-FPM pools and MariaDB databases, intended for use on a small web hosting server with Red Hat Enterprise Linux 9 or derivatives such as Rocky Linux.

WHCS are not intended to replace or compete with existing, more comprehensive web hosting control panels or similar solutions. This means that web-based manageability, configuration databases, multi-tenancy, multi-server support or other Linux distributions are not within the targeted scope.

Until they were revised and summarized as Web Hosting Control Scripts, the predecessor scripts were created peu à peu since 2006, primarily as unversioned and unpublished “copycode”.

## Requirements

- Red Hat Enterprise Linux 9 (or a derivative such as Rocky Linux) with packages
  - httpd, mod\_http2, mod\_ssl (Apache HTTP server)
  - mariadb, mariadb-server (MariaDB database server)
- [Remi's RPM repository](https://rpms.remirepo.net/) with SCL packages for parallel installation of multiple PHP versions
  - phpXY-php-fpm, phpXY-php-\* (PHP X.Y with at least PHP-FPM)

## License

This project is licensed under the GNU General Public License, version 2 or later - see the [LICENSE](LICENSE) file for details.
