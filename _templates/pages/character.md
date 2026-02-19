---
Note Type: Character
---
# Who are they

## Personality Traits

## Ideals

## Bonds

## Flaws

## Backstory

## How do they think?
%%Imagine writing in first person - what things do they notice? What do they pay attention to? _How_ do they think? %%
# Intended Arc
%% What are we wanting this character to go through, where should they end up. What's _their_ story going to be? %%

# Notable Events
%% Maybe for the character, maybe related to a world event %%
- 

# Notable Relationships
%% Who's their parents? Family? Friends? Enemies? %%
- 

# Notable Locations
%% Where they grew up, want to go to, etc %%
- 

# Secrets
%% Things they keep secret and why %%
- 

# Dynamic Queries

## Scenes featuring "{{title}}"
```base
filters:
	and:
		- note["Note Type"] == "Scene"
		- Characters.contains(link("Characters/{{title}}", "{{title}}"))
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
