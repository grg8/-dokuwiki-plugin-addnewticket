Dokuwiki Plugin: Add New Ticket
===============================

Fork from the add new page plugin for Dokuwiki: https://www.dokuwiki.org/plugin:addnewpage

It is adapted to add the current date in front of the title.

This is free software, released under the [GPL version 2](https://www.gnu.org/licenses/gpl-2.0-standalone.html).

## Syntax

    {{NEWDATE[>namespace]}}

Where namespace is optional, and indicates the destination namespace for the new page.
If you give @NS@ or @PAGE@ as namespace, the namespace of the current page or the current page ID will be used.

## Example

    {{NEWDATE>:user:admin}}

## Authors

- Originally written by [Benjamin Santalucia](https://github.com/ben8p) (aka iDo), 2006.
- Moved to Github by hamstar <hamstar@telescum.co.nz>, 2012.
- Updated by Sam Wilson <sam@samwilson.id.au>, 2013.
- Updated by Michael Braun <michael-dev@fami-braun.de>, 2013.
- Improved by Róbert Toth (FurloSK), 2013.
- Support for newpagetemplate added by Gerrit Uitslag <klapinklapin@gmail.com>, 2014.
- Disabling of restricted parent namespaces by Albert Chern, 2015.
- Title is prefixed with date by Christoph Strasser, 2021.
