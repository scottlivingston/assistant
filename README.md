# Assistant
I've long felt that computers should be used to improve our lives. This project is a direct attempt at that for myself. Maybe others will find it useful as well.

Assistant is a system built to help me shed cognative load off of things that a machine is much better at. At this time, the first things I will be adding is the FYI system and Consumable tracking. Funtionality I'm thinking about so far include:

1. FYIs
2. Consumable tracking
3. Personal Relationship Management
4. Task Management
5. Todo lists

## Entities

### FYIs
[Similar to this idea](https://codeascraft.com/2018/10/10/etsys-experiment-with-immutable-documentation/), FYIs are quick notes to jot down about something random

#### Attributes
|Field Name| Type | Description |
| ---- | ---- | ---- |
| content | String | Something to remember and make searchable |

### Consumable
Tracking use of Consumable items such as soap and snacks.

#### Attributes
|Field Name| Type | Description |
| ---- | ---- | ---- |
| name | String | Name of the Consumable |
| size | Volume | Volume of the Consumable |
| link | String | URL to the store page where purchased |
| startDate | Date | The date the Consumable use was started |
| endDate | Date | The date the Consumable ran out |

#### Features
Keep track of how long to consume the consumable and use that to gauge when to buy them again.

Setup automatic alerts to buy items again before they are needed.

### Person
Keep track of personal and professional relationships.

#### Attributes
|Field Name| Type | Description |
| ---- | ---- | ---- |
| name | String | Name of the Person |
| relationshipType | Enum | Personal/Professional |
| birthday | Date | The date of the Person's birth |
| contactInfo | Contact | Phone number, address, email... |

#### Features
Keep track of people and their contact info.

Remember birthdays and other important events with reminders.
