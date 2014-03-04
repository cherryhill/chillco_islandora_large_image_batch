# Chillco Islandora Large Image Batch Import

## Introduction

This module complements the Chillco Islandora Large Image Solution Pack in importing (and converting) the XML for DPL and their images to Islandora (and brings over the appropriate image datastream as well). It uses the Islandora Batch Import API for bringing in content.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Tuque](https://github.com/islandora/tuque)
* [Islandora Batch](https://github.com/islandora/islandora_batch)
* [Chillco Islandora Large Image Solution Pack](https://github.com/chillco/chillco_islandora_solution_pack_large_image)
* Chillco Islandora DPL DAMS xmlparser (coming soon)

## Installation

For the module, install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

On the import page, specify the path to the xml directory and the path to the image directory. THe xml/path should hold the same relative paths (so if xml is at /path/to/xml/directory/site/1/happy.xml, the corresponding image would be /path/to/jpg/directory/site/1/happy.(jpg|tiff|gif|png))

## Troubleshooting

Having problems or solved a problem? Check out the Islandora google groups for a solution.

* [Islandora Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Islandora Dev Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

## FAQ

N/A

## Maintainers

[Ashok Modi](https://github.com/btmash)
