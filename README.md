# GameStructure-for-rojo

-- copy and put that in >>> default.project.json



```lua
{
  "name": "TestingStuff",
  "tree": {
    "$className": "DataModel",
    "$ignoreUnknownInstances": true,

    "ReplicatedStorage": {
      "$className": "ReplicatedStorage",
      "$path": "src/ReplicatedStorage"
    },

    "ServerScriptService": {
      "$className": "ServerScriptService",
        "$path": "src/ServerScriptService"
    },

    "StarterPlayer": {
        "$className": "StarterPlayer",
        "StarterCharacterScripts": {
        "$className": "StarterCharacterScripts",
        "$path": "src/StarterCharacterScripts"
        },
      "StarterPlayerScripts": {
        "$className": "StarterPlayerScripts",
        "$path": "src/StarterPlayerScripts"
      }
    }
  }
}
```
