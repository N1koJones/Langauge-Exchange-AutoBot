# Langauge-Exchange-AutoBot
A Discord bot used in the Japanese-English Language Exchange Discord server to automate events and announcements.

This project will aim to automate the announcement process of the weekly events held by the group. 

# Commands (tennative)
## Pretext for Commands (tennative): ~


## Setup
These are administration tools that will be used on startup and changing factors in the settings.

### setup [role]
This will start the setup process and restrict setup access to only the role given. (Can be overridden by an admin)
Setup process consists of seeing all input and output channels, queue, etc. after each input

### endsetup
This will stop the setup process and constant response of listing items as they are added/removed.

### assignout
This will assign the channel that announcements will be output to. (Can only be one channel at a time)

### assignin
This will assign the channel where inputs can be made. (This can be multiple channels)

### removein
This will remove the current channel from bot input.


## Post-Setup
This will be more commonly used commands during setup.

### queue [jp] [en]
This will queue an event topic and add it to the JSON file as jp and en respectively. (Must have "" on each sentence)

### viewqueue
This will output the current queue in the channel where the command was made.



## Backend (tennative)

### Storing future events
To store future events, this will be held in a .json file for easy formatting and storing of event topics.
JSON formatting (tennative):
```
{
  "jp": "イベント例"
  "en": "Example Event"
}
```
