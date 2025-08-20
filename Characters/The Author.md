---
Note Type: Character
tags:
  - deleteme
---
# Who they are at the start of the story?

## Personality Traits

## Ideals

## Bonds

## Flaws

## Backstory

# Notable Events

- 

# Notable Relationships

- 

# Notable Locations

- 

# Secrets

- 

# Scenes featuring "The Author"

```base
filters:
	and:
		- note["Note Type"] == "Scene"
		- Characters.contains(link("Characters/The Author", "The Author"))
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
    order:
      - file.name
      - file.ctime
      - file.mtime

```
