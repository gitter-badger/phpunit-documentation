# Building the Documentation

[![Join the chat at https://gitter.im/nelson6e65/phpunit-documentation](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/nelson6e65/phpunit-documentation?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Requirements

- Apache Ant
- PHP 5 (with DOM, PCRE, SPL, and Tokenizer extensions enabled)
- Ruby
- xsltproc

## Building the Documentation

To build the complete documentation use:

    cd build
    ant

To build only one version of the documentation use:

    cd build
    ant build-LANG-VERSION

for example

    cd build
    ant build-en-4.3

# Output

The generated files will be in `build/output/VERSION/LANG`.
