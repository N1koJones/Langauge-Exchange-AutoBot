# Langauge-Exchange-AutoBot
## Sleeping Bot

A Discord bot used in the Japanese-English Language Exchange Discord server to automate events and announcements.
The name is related to the original organizer of the group who goes by the alias "Sleeping". He is still an active member but others have since assisted with organizing and upkeep of the group.

This project will aim to automate the announcement process of the weekly events held by the group. 

# Datapoints
### input [channel]
### output [channel]
### superuser [role]
### queue []
### events [] 

# Commands (tennative)
## Pretext for Commands: /

### /reset
- Resets all settings.

### /assignin [channel]
- Assigns the only channel that commands for this bot will be accepted in

### /assignout [channel]
- Assigns the **only** channel that announcements will be put.

### /superuser [role]
- Assign the role(s) that can use bot commands.


# Backend (tennative)

### Storing future events
To store future events, this will be held in a .json file for easy formatting and storing of event topics.
JSON formatting (tennative):
```
{
  "jp": "イベント例"
  "en": "Example Event"
}
```
