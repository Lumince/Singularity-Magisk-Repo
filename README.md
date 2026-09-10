## Schema

```json
{
  "schemaVersion": 1,
  "modules": [
    {
      "id": "magisk_overlayfs",    // Set this to the module's real module.prop `id`
      "name": "Magic OverlayFS",
      "description": "...",
      "author": "agreenbhm",
      "githubOwner": "agreenbhm",  // the module's OWN repo -- app resolves its latest release
      "githubRepo": "magic_overlayfs",
      "assetSuffix": ".zip",       // used to pick the right asset from that repo's latest release
      "deviceFilter": null         // null, or a QuestDevice name: "QUEST_2" | "QUEST_PRO" | "QUEST_3" | "QUEST_3S"
    }
  ]
}
```
