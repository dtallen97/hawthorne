# Open Character Model v0.1
Characters are a core componenent of any RPG - after all, they are "role" playing games. The Open Character Model (OCM) is intended to provide a flexible definition that can be used to generate characters and character sheets for a wide range of RPG systems.

## Stats
Stats (also known as "attributes", "skills", "traits", etc. in different systems) assign a score to certain aspects of a character. For example, a character might have a Strength stat that determines how strong they are, or a First Aid stat that determines how good they are at applying first aid techniques.

### Key Concepts

#### Primary and Derived Stats
There are two main categories of stats in the OCM: primary and derived.

Primary stats are innate qualities that a character has. Strength and Intellect are common examples of primary stats.

Derived stats are based off of one or more basic, or derived, stats. For example, First Aid might be based off of Intellect, and Firefighting might be based off of First Aid and Strength.

The only constraint on derived stats is that they cannot be cyclical. For example, you cannot have Climbing be derived from Agility and Agility be derived from Climbing.

#### Stat Groups
A stat group defines common behavior that a stat can use. For example, Strength and Intellect may both be part of an "Attribute" stat group that sets a default value of 10.

Stat groups are totally optional.

Stat groups have the following behavior:
- Stats may only be part of one stat group
- Stats may override the settings defined in the stat group

#### Modifiers
A modifier is a value that is calculated based off a skill score, and it typically defines how skills are used in a system. For example, in System X you may add your Strength modifier to rolls requiring Strength.

Modifiers are totally optional.

### Definition (TODO)

### YAML Example (TODO)
