---
Note Type: Location
tags:
  - deleteme
---
A nice place where [[Characters/The Reader|The Reader]] can often be found.

# Geographical placement
%% Where is it in relation to other Locations %%
Not yet established

# History
%% How it began, who named it, notable events there, etc %%
Not yet established

# Dynamic Queries

## Scenes featuring The Reader's House

```base
filters:
  and:
    - note["Note Type"] == "Scene"
properties:
  file.name:
    displayName: File
  file.ctime:
    displayName: Created
  file.mtime:
    displayName: Last edited
views:
  - type: table
    name: Table
    filters:
      and:
        - Locations.contains(link("Locations/The Reader's House", "The Reader's House"))
    order:
      - file.name
      - file.ctime
      - file.mtime

```

## Events featuring The Reader's House

```base
filters:
  and:
    - note["Note Type"] == "Event"
properties:
  file.name:
    displayName: File
  file.ctime:
    displayName: Created
  file.mtime:
    displayName: Last edited
views:
  - type: table
    name: Table
    filters:
      and:
        - Locations.contains(link("Locations/The Reader's House", "The Reader's House"))
    order:
      - file.name
      - file.ctime
      - file.mtime

```