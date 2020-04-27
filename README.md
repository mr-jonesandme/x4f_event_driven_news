# Event Driven News v1.0.2

Event Driven News is a mod for X4 which adds dynamic event based news and reports to the game.  Forum link - https://forum.egosoft.com/viewtopic.php?f=181&t=426035

## Installation

Place the 'event_driven_news' folder into your X4 Foundations extensions folder.  This mod does not require a fresh game start and is to the best of my knowledge safe to remove.  Make a backup of your save just in case

## Known Issues
On a brand new game start, you will receive faction HQ destruction news events after the universe first initializes.  I'm aware of this issue and need to add in some kind of timer to suppress the very first, but not subsequent, faction HQ change events

## Change Log

### 1.0.2
- Added a new GNN "channel" - CrimeWatch
- Added a new "bounty" story to the CrimeWatch channel.  If a pirate successfully hacks a station cargo module, there is a slight chance of a dynamic news entry being created for this event
- Various bugfixes to existing news events

### 1.0.1
- Removed SCA from ware shortage/surplus/shipping events - a news network probably shouldn't be reporting on SCA logistics 
- Bumped up frequency of ware surplus/shortage events, was too low
- Some edits to content.xml so the version and name show correctly

### 1.0.0
Initial release

## Feeds and Events
Currently, there is one active feed - GNN

### GNN 
The GNN feed reports on general galaxy events, logging into the player's "tips" logbook with the headline split by category. This is your basic barebones news feed and is available to all from the start.  For balancing purposes, it will not be as precise as one of the planned "premium" feeds, but adds life to the universe and gives some indication to the player as to what sectors are experiencing.  The GNN feed currently reports based off the following types of events:
#### GNN Politics 
- Sector ownership changes (includes player faction)
- Rebuilt faction HQ's (NPC factions only)

#### GNN MarketTalk
- Sector ware shipping issues (NPC factions, excluding Xenon & SCA)
- Sector ware shortage events (NPC factions, excluding Xenon & SCA)
- Sector ware surplus events (NPC factions, excluding Xenon & SCA)

#### GNN CrimeWatch
- Pirate activity as it pertains to the theft of cargo from station storage

### Additional planned GNN features
- Basic UI for toggling news events on/off by category
- Rumors regarding Xenon I sightings
- More variety/X lore friendly reporting

## Premium Feeds
The following "premium" feeds are planned in a future update.  In contrast to the GNN feed, these will be more analytical in nature and help guide players in military and economic objectives

### Teladi Trading Terminal
This will be a license available from a friendly Teladi for some change.  It will provide more precise economy related event topics, making it easier for industry focused players to respond to dynamic pricing events.  These events are likely to arrive sooner and contain information that a player is able to act on to bring in more profitsss

### Corporate Intelligence Services
This feed will depend on the dedication of a player "asset", such as a defense station or fleet.  It will enable the player to receive periodic intelligence assessments on other in game factions and alerting about faction goals targeting player assets.  Reports could include information such as estimated faction capital ship numbers, active defense stations, faction goals, contested sectors, faction momentum etc.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  If you are interested in adding more variety in some stories of your own, please open an issue so that I can get into contact with you

## License
[MIT](https://choosealicense.com/licenses/mit/)
