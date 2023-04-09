# Shannen Tan's Project Portfolio Page

## Overview

BagPacker is a desktop Command Line Interface (CLI) application used to manage a user's packing list.
It stores a packing list, edit the quantities packed and the total quantity packed of an item, and searches the packing list for items.
It is written in Java, and has about 3 kLoC.

## Summary of Contributions
Given below are my contributions to the project.

New Feature: `editquantity`
  * What it does: allows the user to edit the total quantity of an item at the index specified
  * Justification: this feature improves the product significantly as there was no way to reduce the total quantity of an item in teh packing list
      * Repeated `add` commands can be used to increase the total quantity of an item, but not reduce it
  * Highlights: users are able to edit the total quantity of an item to be packed, without having to delete the current item and add the item again

Code contributed: [RepoSense link](https://nus-cs2113-ay2223s2.github.io/tp-dashboard/?search=shannentan&breakdown=true)

Project management
* Created GitHub organisation for the team
* Set up GitHub team repository

Enhancements to existing features
* Enhanced the `add`, `pack` and `unpack` commands to support multiple quantities
  * Involved changing the `Item` constructor, and the respective methods used to parse inputs and execute the commands


Documentation
* User Guide
  * Formatted the User Guide
  * Added the tables of contents, links to different sections within the User Guide, and colours to the headers
  * Added description of command, format, example usage and important notes to some commands
    * `add`, `delete`, `pack`, `unpack`, `editquantity`, `list`, `deletelist` and `find`
  * Added the command summary
* Developer Guide

Community
* Reported bugs and gave suggestions to other teams in the class during [PE-D](https://github.com/shannentan/ped/issues)