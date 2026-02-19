---
Note Type: Location
---
# Geographical placement
%% Where is it in relation to other Locations %%

# History
%% How it began, who named it, notable events there, etc %%

# Resources
%% What is there, why would this location be valuable for people? %%

# Related places
%% Not geographically, but in terms of things like trade or similar %%

# Dynamic Queries

## Scenes featuring "{{title}}"

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
        - Locations.contains(link("Locations/{{title}}", "{{title}}"))
    order:
      - file.name
      - file.ctime
      - file.mtime

```

## Events featuring "{{title}}"

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
        - Locations.contains(link("Locations/{{title}}", "{{title}}"))
    order:
      - file.name
      - file.ctime
      - file.mtime

```