# PHP Data Structures

Samples with PHP data structures, from:

- [SPL](https://secure.php.net/manual/pt_BR/book.spl.php)
- [ds](https://github.com/php-ds)

## How to execute the samples?

1. Install [Docker](https://www.docker.com/).
2. Pull the image [devdrop/php-toolbox](https://hub.docker.com/r/devdrops/php-toolbox/), by executing `docker pull devdrops/php-toolbox`.
3. Clone this repository and navigate to the source dir.
4. Execute `make run COMMAND='<folder>/index.php'`, where `<folder>` should be one of the folders present on this repository.

### Example

```bash
make run COMMAND='dll/index.php'
```

