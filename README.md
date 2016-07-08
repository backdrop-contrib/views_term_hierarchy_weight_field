Views term hierarchy weight field
=====

This module allows you to filter or sort terms according to their hierarchical 
order or hierarchical depth.

Use cases
---------

- You need to display a list of entities ordered by their taxonomy terms in 
hierarchical order, example, a list of products ordered by categories.
- You need to display a list of entities where their terms is on a particular 
depth
- You need to display a list of entities in a select box with Better Jump Menu 
and you need it sorted hierarchically.

Provides
--------

- Two Views sort handlers (fields): Hierarchy weight and depth, with field, 
sort and filter handler.
- If Entity Menu Links is installed, you'll be able to access to the 
hierarchical weight of a menu item.

The module adds `hweight` and `hdepth` columns to the `taxonomy_term_data` 
tables.

Dependencies
---------

- Views

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- Use the handlers in Views as normal: Select the 
"Taxonomy term: Hierarchical weight" field, filter, sort or relationship 
handlers in the Views UI.

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

Current Maintainers
-------------------

- Docwilmot (https://github.com/docwilmot

Credits
-------

- Pol Dellaiera (Pol) (https://www.drupal.org/u/pol)
