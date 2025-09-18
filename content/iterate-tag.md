# Iterating Entries in a Tag

Iterating a tag has to be done AFTER all data has loaded! (e.g. with `ServerLifecycleEvents.END_DATA_PACK_RELOAD` and `ServerLifecycleEvents.SERVER_STARTED`

```
TagKey<Block> exmapleTag = TagKey.of(RegistryKeys.BLOCK, identifier);
WIP
```
