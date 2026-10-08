# keel plugin: Map

A picture of the project: the system, its modules and the database (ER), drawn from folders, migrations and the API contract.

> **Status: planned.** The code still lives in [keel-v2](https://github.com/MiladNalbandi/keel-v2). It moves here step by step, as
> [the plugin plan](https://github.com/MiladNalbandi/keel-v2/tree/main/docs/plugins) says. There is nothing to install yet.

| | |
| --- | --- |
| id | `map` |
| needs | keel core (plugin SDK 1) |
| works with | Database |
| parts | engine · web |
| trust level | runs code in keel |

**What it adds to keel**

- the Map page (#/map)

**Where the code is today (keel-v2)**

- `engine/keel_engine/runtime/mapper.py`
- `engine/keel_engine/runtime/sqlschema.py`
- `web/src/pages/Map.tsx`

## Layout

```
keel-plugin.yml   the manifest
engine/           Python package for keel's engine
web/              React pages and slots (an ES module)
```

## Install

When it is released: in keel, **Control › Plugins › Marketplace › Map › Install**. keel checks the file's
signature, shows what the plugin may do, and asks you before it installs.

## License

MIT
