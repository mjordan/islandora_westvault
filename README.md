# Islandora WestVault

Islandora module that provides functionality specific to the WestVault digital preservation network.

## Introduction

Currently the only functionality this module provides is to add the following tags to Bags created for deposit into WestVault:

* Bag-Size
* Bag-Count
* Bagging-Date
* Internal-Sender-Description: [Optional] Human readable description of the contents of the bag.
* Internal-Sender-Identifier: [Optional] Internal or alternate identifier used at the senders location.

Source-Organization is also required by WestVault, and 

## Requirements

* [Islandora](https://github.com/islandora/islandora)

## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Configuration options are available at Administration > Islandora > Islandora Utility Modules > Islandora BagIt. Check the "Add WestVault tags" option at the bottom of the form. You should also make sure that you enter your institution's name in the "Organization transferring the content" field at the top of the "Bag metadata" group form elements:

![BagIt configuration]('images/islandora_westvault.png')

## Maintainer

* [Mark Jordan](https://github.com/mjordan)

## Development and feedback

Bug reports, use cases, feature requests, and pull requests are welcome. Please open an issue before opening a pull request.

## License

* [GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
