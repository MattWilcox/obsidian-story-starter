---
Note Type: Organisation
---
# Organisation Name

## Also Known As
%% Organisations usually have nicknames or other terms they're known as to different groups. List them. %%

## Founding principles and people

## Areas of influence they hold

## Restrictions on their influence

## Important people and their roles

# Intended Arc
%% Does this organisation have an arc associated with it; what and why? %%

# Notable Events
%% Maybe related to a character, maybe related to a world event %%
- 

# Notable Relationships
%% Who's their parents? Family? Friends? Enemies? %%
- 

# Notable Locations
%% Places important to this organisation, etc %%
- 

# Secrets
%% Things they keep secret and why %%
- 

# Dynamic Queries

## Scenes featuring "{{title}}"
```base
filters:
	and:
		- note["Note Type"] == "Organisation"
		- Organisations.contains(link("Organisations/{{title}}", "{{title}}"))
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
