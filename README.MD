# WP FR-CA
Cet outil permet de maximiser l'efficacité de traduction de masse pour la langue Français du Canada.

This tool helps us to maximize mass translations for French Canada.

## Installation

First, you need [WP-CLI](https://wp-cli.org/fr/) installed.

Second, you need to install [PO-Merger](https://github.com/SatelliteWP/po-merger).

Then, you can clone this repo:

    git clone git@github.com:SatelliteWP/wp-fr-ca.git

That's it, you can start mass translating!

## Usage

You can now start mass translating using PO-Merger, our fuzzy file and dictionary. That will speed up the process.  

Here is the suggested command line that will maximize your effort:

    wp po merge fr-ca fr <source> --diff-only --fuzzy=files/fuzzy.txt --dictionary=files/dictionary.po

You can also merge PO files together to make the dictionary better

    wp po merge-file files/dictionary.po my-other-file.po


## Maintainers
This project was created and is maintained by [SatelliteWP](https://www.satellitewp.com/en?utm_source=wp-fr-ca) from an idea by [Cedric Bethencourt](https://github.com/cedricus).

## Contributing
Ideas are welcome.
