---
Note Type: Character
tags:
  - deleteme
---
# Who they are at the start of the story?

The Reader is an enigma, a mystery with few aspects known to me.

## Personality Traits

- Interested in writing

## Ideals

- Aspiring author

## Bonds

- Unknown

## Flaws

- A tendency to get distracted by nerdy stuff online

## Backstory

Someone working in tech, but feeling the need to branch out and try something new. A creative needing a new outlet. They have set their mind to try writing a story, and so their adventure begins...

# Notable Events
%%Personal events may be simple sentences. If the character is involved in a Historically Important Event, that may be a link to one of the Event note types%%

- Discovered a GitHub project for writing stories in Obsidian - this will become pivotal to their arc.

# Notable Relationships

- A friend of [[The Author]], having discovered their work online.

# Notable Locations

- [[Locations/The Reader's House|The Reader's House]]

# Secrets

- Oh so many!

# Scenes featuring "The Reader"

```base
filters:
  and:
    - note["Note Type"] == "Scene"
    - Characters.contains(link("Characters/The Reader", "The Reader"))
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
      - file.folder
      - file.ctime
      - file.mtime
    sort: []

```