[Pages](Pages.md)

# Currently Implemented

## Sensors
The Sensors Table is used to store information about the sensors that a user currently has implemented in their system
### Fields

| Field       | Type      |
| ----------- | --------- |
| Sensor Type | Reference |
| Location    | Reference |
| Name        | String    |
| Sys.ID      | String    |

## Sensor Types
The Sensor Types is used to store information about types of sensors that can be used in a system
### Fields

| Fields  | Type   |
| ------- | ------ |
|  Name   | String |
| Measure | Ref    |
| Sys.ID  | String |

## Units
The Units table is used to store informaton about the attributes to be measured in a system and the units that can be used to measure those attributes
### Fields

| Fields | Type   |
| ------ | ------ |
| Type   | String |
| Sys.ID | String |
| Unit   | String |


## Hardware Readings
THe Hardware Readings table is used to store the Readings taken from hardware implemented in a users system
### Fields

| Fields | Type   |
| ------ | ------ |
| Created | Date |
| Sys.ID | String |
| Value   | String |
|Hardware| Ref    |

## Sensor Readings
The Sensor Readings table is used to store the Readings taken from sensors implemented in a users system
### Fields

| Fields | Type   |
| ------ | ------ |
| Created | Date  |
| Sys.ID | String |
| Value  | Int    |
| Sensor | Ref    |

## Hardware Types
The Hardware Types table is used to store information about types of hardware a user could implement in their system
### Fields

| Fields  | Type   |
| ------- | ------ |
|  Name   | String |
| Control | Ref    |
| Sys.ID  | String |
| Tank    |  Bool  |

## Hardware
The Hardware table is used to store information about the Hardware a user has implemented in their system
### Fields

| Field       | Type      |
| ----------- | --------- |
| Hardware Type | Reference |
| Location    | Reference |
| Name        | String    |
| Sys.ID      | String    |

## Location

### Fields

| Fields  | Type   |
| ------- | ------ |
|  Name   | String |
| Sys.ID  | String |
| Tank    |  Bool  |

# To Do

## Users
The Users table is used to store information about the users of the application
### Fields

| Fields  | Type    |
| ------- | ------  |
| Username | String |
| Password | String |
| Sys.ID  | String  |


## Plants
The Plants Table is used to store information about things being grown in a Users system
### Fields

| Fields  | Type   |
| ------- | ------ |
|  Name   | String |
| Location | Ref   |
| Sys.ID  | String |