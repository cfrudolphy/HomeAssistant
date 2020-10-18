This file will describe events as necessary

Occupancy
  Group - 286ATS_LocationGroup
    Abita
    Olga
    Chris
    Chuck
    Emily
    Patty
  Triggers
    Occupied - If any one of the above entities in the group become home
    Un-Occupied - If all of the above entites in the group are not home
  Actions
    Occupied:
      switch Occupied on
      Send MQTT message to Homeseer to turn Virtual Occupancy Device on
    Un-Occupied:
      switch Occupied off
      Send MQTT message to Homeseer to tur
      ton Virtual Occupancy Device off
  Notes:
    The status of Occupied will control lights, door locks, and thermostat

House Scenes
  Occupied - Day
  Occupied - Night
  Un-occupied
Triggers
  Enters Day Time Period
  Enters Night Time Period
Conditions
  Occupied
  Un-Occupied
Actions
  Day - Occupied - Set thermostat to: 
    Heat to 66 - Cool to 72
    Ceiling Fans to Low
    Blue Iris to Occupied
  Night - Occupied - Set thermostat to: 
    Heat to 66 - Cool to 70 (68 maybe)
    Ceiling Fans to Low
    Bedlamps to 50%
    Blue Iris to Occupied Night
  Un-Occupied (regarless of time period) - Set thermostat to: 
    Heat to 60 - Cool to 78
    Ceiling Fans to High
    Blue Iris to Unoccupied

