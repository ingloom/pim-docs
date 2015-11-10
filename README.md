# Akeneo PIM Documentation

The Akeneo PIM documentation

## Installation

Clone this repository.

### Linux

Install [Sphinx](http://sphinx-doc.org/).
```bash
    $ sudo apt-get install python-sphinx
```

### Mac OS
<<<<<<< HEAD

=======
>>>>>>> master

```bash
    $ brew install python
    $ pip install sphinx
    $ pip install git+https://github.com/fabpot/sphinx-php.git
```

Download composer `curl -s https://getcomposer.org/installer | php` and run `php composer.phar install`.

<<<<<<< HEAD
## Build the documentation
=======
## Build the documention
>>>>>>> master

From the `./pim-docs` directory, run:

``` bash
    $ sphinx-build -b html . ../pim-docs-build
```

The documentation will be generated inside `../pim-docs-build`.

<<<<<<< HEAD

=======
>>>>>>> master
## Make documentation code work with pim-community-dev or standard

Install pim-community

Then, go to Akeneo PIM `src/` directory and create a symlink `Acme` pointing to `pim-docs/src/Acme`.

Add all Acme bundles in `app/AppKernel.php` file.


## Contribution

Don't hesitate to propose cookbook entries via https://github.com/akeneo/pim-docs/issues
