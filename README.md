# Using Database Markup Language

DBML (database markup language) is a simple, readable DSL language designed to define database structures.

## Benefits

- It is simple, flexible and highly human-readable
- It is database agnostic, focusing on the essential database structure definition without worrying about the detailed syntaxes of each database

## Renderer

```bash
npm install -g @softwaretechnik/dbml-renderer
```

It can then be used to render DBML files like so:

```bash
dbml-renderer -i northwind.dbml -o northwind.svg
```

## Rendering

![schema](northwind.svg)

## Community

* [Emacs Mode for DBML (Contributed by ccod)](https://github.com/ccod/dbd-mode)
* [Vim Plugin for DBML (Contributed by jidn)](https://github.com/jidn/vim-dbml)
* [VSCode Plugin for DBML by duynvu](https://marketplace.visualstudio.com/items?itemName=duynvu.dbml-language)
* [Python parser for DBML by Vanderhoof](https://github.com/Vanderhoof/PyDBML)
* [FloorPlan: Android's Room to DBML by julioz](https://github.com/julioz/FloorPlan)
* [Go parser for DBML by duythinht](https://github.com/duythinht/dbml-go)
* [DbmlForDjango: Converter between Django models.py and DBML](https://github.com/hamedsj/DbmlForDjango)
* [parseServerSchema2dbml: Converter between ParseServer MongoDB \_SCHEMA collection and DBML by stepanic](https://github.com/stepanic/parse-server-SCHEMA-to-DBML)
* [dbml-renderer: A DBML CLI renderer](https://github.com/softwaretechnik-berlin/dbml-renderer)
* [dbml-parser: A DBML parser written on PHP8 by Butschster](https://github.com/butschster/dbml-parser)
* [Kacher: Laravel's Database Schemas to DBML by Arsanandha Aphisitworachorch](https://github.com/aphisitworachorch/kacher)
* [d365fo-entity-schema: Generate DBML from Dynamics 365 Finance and Operations ](https://github.com/noakesey/d365fo-entity-schema)