Homeseer Zwave & MQTT Setup
========================

## Node: 1
* Ref ID: 13 Name: Z-Wave Node 1 SmartStick+

## Node: 8 
* (NOT IN USE)

## Node: 10 - COMPLETED
### Manufacturer
* Ingersoll Rand Security & Safety
* Schlage BE468CEN716
#### Parent
* Ref ID: 3 Name: Access Control Living Room Back Door Lock Root
#### Children
* Ref ID: 6 Name: Application Status
* Ref ID: 7 Name: Back Door Lock Battery - **_sensors.yaml_**    
    * Publish:  
        *CRUD-06/mcsMQTT/Living_Room/Access_Control/Back_Door_Lock_Battery*  
    * Ref ID: 8 Name: Back Door Lock - **_locks.yaml_**    
    * Subscribe:  
        *CRUD-06/mcsMQTT/Living_Room/Access_Control/Back_Door_Lock/Control*
    *  Publish:  
        *CRUD-06/mcsMQTT/Living_Room/Access_Control/Back_Door_Lock*  
        *$$STATUS:*
* Ref ID: 9 Name: Back Door Access Control Notification - **_sensors.yaml_**  
    * Publish:  
        *CRUD-06/mcsMQTT/Living_Room/Access_Control/Back_Door_Access_Control_Notification*  
        *$$STATUS:*
* Ref ID: 10 Name: Power Management Notification
* Ref ID: 11 Name: System Notification

## Node: 12 - COMPLETED
### Manufacturer
* Ingersoll Rand Security & Safety
* Schlage BE468CEN716
#### Parent
* Ref ID: 19 Name: Access Control Entry Way Front Door Lock Root
#### Children
* Ref ID: 20 Name: Application Status
* Ref ID: 21 Name: Front Door Lock Battery - **_sensors.yaml_**   
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Access_Control/Front_Door_Lock_Battery*   
* Ref ID: 22 Name: Front Door Lock - **_locks.yaml_**  
    * Subscribe:  
    *CRUD-06/mcsMQTT/Entry_Way/Access_Control/Front_Door_Lock/Control* 
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Access_Control/Front_Door_Lock*  
    *$$STATUS:*
* Ref ID: 23 Name: Front Door Lock Access Control Notification - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Access_Control/Front_Door_Lock_Access_Control_Notification*  
    *$$STATUS:*
* Ref ID: 24 Name: Power Management Notification
* Ref ID: 25 Name: System Notification

## Node: 13 - COMPLETED
### Manufacturer
* Homeseer
* WD100
#### Parent
* Ref ID: 26 Name: Lighting Dining Room Light Switch Root
#### Children
* Ref ID: 27 Name: Dining Room Light Central Scene - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Dining_Room/Lighting/Dining_Room_Light_Central_Scene*  
    *$$STATUS:*  
* Ref ID: 28 Name: Dining Room Light - **_lights.yaml_**    
    * Subscribe:  
    *CRUD-06/mcsMQTT/Dining_Room/Lighting/Dining_Room_Light/Control*
    * Publish:  
    *CRUD-06/mcsMQTT/Dining_Room/Lighting/Dining_Room_Light  
    
## Node: 15 - COMPLETED
### Manufacturer
* Homeseer
* WD100
#### Parent
* Ref ID: 39 Name: Lighting Living Room Living Room Fan Light Switch Root 
#### Children
* Ref ID: 40 Name: Living Room Fan Light Central Scene - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Living_Room/Lighting/Living_Room_Fan_Light_Central_Scene*  
    *$$STATUS:*
* Ref ID: 41 Name: Living Room Light - **_lights.yaml_**  
    * Subscribe:  
    *CRUD-06/mcsMQTT/Livng_Room/Lighting/Living_Room_Light/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Living_Room/Lighting/Living_Room_Light*  

## Node: 16 - COMPLETED
### Manufacturer
* Jasco Products
* 14287 Fan Control Switch
#### Parent
* Ref ID: 42 Name: Fan Control Living Room Living Room Fan - **_fans.yaml_**  
    * Subscribe:  
    *CRUD-06/mcsMQTT/Living_Room/Fan_Control/Living_Room_Fan/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Living_Room/Fan_Control/Living_Room_Fan*  
    *$$STATUS:* 

## Node: 18
### Manufacturer
* GoControl/Linear (Nortek)
*  GD00Z-4
#### Parent
* Ref ID: 48 Name: Access Control Garage Garage Door Entry Control
#### Children
* Ref ID: 49 Name: Garage Door Application Status
* Ref ID: 50 Name: Garage Door
    * Subscribe:  
    *CRUD-06/mcsMQTT/Garage/Access_Control/Garage_Door/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Garage/Access_Control/Garage_Door*  
    *$$STATUS:* 
* Ref ID: 51 Name: Garage Door Access Control Notification
* Ref ID: 52 Name: Garage Door Home Security

## Node: 19
* (PHANTOM)

## Node: 21
### Manufacturer
* Trane Corp
* XR524
#### Parent
* Ref ID: 55 Name: HVAC Thermostat Thermostat
#### Children
* Ref ID: 56 Name: Temperature
    * Publish:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Temperature*  
    *$$STATUS:* 
* Ref ID: 57 Name: Fan Mode
    * Subscribe:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Fan_Mode/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Fan_Mode*  
    *$$STATUS* 
* Ref ID: 58 Name: Fan State
    * Publish:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Fan_State*  
    *$$STATUS* 
* Ref ID: 59 Name: Mode
 * Subscribe:  
 *CRUD-06/mcsMQTT/Thermostat/HVAC/Mode/Control*  
 * Publish:  
 *CRUD-06/mcsMQTT/Thermostat/HVAC/Mode*  
 *$$STATUS:*
* Ref ID: 60 Name: Operating State
    * Publish:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Operating_State*  
    *$$STATUS:* 
* Ref ID: 61 Name: Heating Setpoint
    * Subscribe:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Hearting_Setpoint/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Heating_Setpoint*  
    *$$STATUS:* 
* Ref ID: 62 Name: Cooling Setpoint
    * Subscribe:  
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Cooling_Setpoint/Control*
    * Publish:   
    *CRUD-06/mcsMQTT/Thermostat/HVAC/Cooling_Setpoint*  
    *$$STATUS:*

## Node: 22 - COMPLETED
#### Manufacturer
* Homeseer
* WD100
### Parent
* Ref ID: 189 Name: Lighting Master Bedroom Master Bedroom Fan Light Switch Root
#### Children
* Ref ID: 190 Name: Master Bedroom Fan Light Central Scene - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Master_Bedroom/Lighting/Master_Bedroom-Fan_Light_Central_Scene*  
    *$$STATUS:*
* Ref ID: 562 Name: Master Bedroom Fan Light Switch - **_lights.yaml_**  
    * Subcribe:  
    *CRUD-06/mcsMQTT/Master_Bedroom/Lighting/Master_Bedroom_Fan_Light_Switch/Control*
    * Publish:  
    *CRUD-06/mcsMQTT/Master_Bedroom/Lighting/Master_Bedroom_Fan_Light_Switch*  

## Node 23 - COMPLETED
### Manufacturer
* Jasco Products
* 14287 Fan Control Switch
#### Parent
* Ref ID: 192 Name: Fan Control Master Bedroom Master Bedroom Fan - **_fans.yaml_**  
    * Subscribe:  
    *CRUD-06/mcsMQTT/Master_Bedroom/Fan_Control/Master_Bedroom_Fan/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Master_Bedroom/Fan_Control/Master_Bedroom_Fan*  
    *$$STATUS:*

## Node 24 - COMPLETED
### Manufacturer
* Homeseer
* DS100
#### Parent
* Ref ID: 193 Name: Access Control Master Bathroom Master Bath Closet Door Root
#### Children
* Ref ID: 194 Name: Master Bath Closet Door Battery  - **_sensors.yaml_**    
    * Publish:  
    *CRUD-06/mcsMQTT/Master_Bathroom/Access_Control/Master_Bath_Closet_Door_Battery*  
* Ref ID: 195 Name: Master Bath Closet Notification - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Master_Bathroom/Access_Control/Master_Bath_Closet_Notification*  
    *$$STATUS:*  
* Ref ID: 196 Name: Master Bath Closet Tamper Switch - **_not subscribed_**  

## Node 25 - COMPLETED
#### Manufacturer
* Jasco
* 14318 Switch
#### Parent
* Ref ID: 197 Name: Lighting Master Bathroom Closet Light - **_switches.yaml_**  
* Subscribe:  
    *CRUD-06/mcsMQTT/Master_Bathroom/Lighting/Closet_Light/Control*
* Publish:  
    *CRUD-06/mcsMQTT/Master_Bathroom/Lighting/Closet_Light*

## Node 26 - COMPLETED
### Manufacturer
* Homeseer
* DS100
#### Parent
* Ref ID: 198 Name: Access Control Entry Way Front Door Sensor Root
#### Children
* Ref ID: 199 Name: Front Door Sensor Battery - **_sensors.yaml_**
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Access_Control/Front_Door_Sensor_Battery*  
* Ref ID: 200 Name: Front Door Sensor Notification - **_sensors.yaml_**
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Access_Control/Front_Door_Sensor_Notification*  
    *$$STATUS:*   
* Ref ID: 201 Name: Front Door Sensor Tamper Switch - **_not subscribed_**  

## Node 27 - COMPLETED
### Manufacturer
* Homeseer
* DS100
#### Parent
* Ref ID: 202 Name: Access Control Living Room Back Door Sensor Root
#### Children
* Ref ID: 203 Name: Back Door Sensor Battery - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Living_Room/Access_Control/Back_Door_Sensor_Battery*  
* Ref ID: 204 Name: Back Door Sensor Notification - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Living_Room/Access_Control/Back_Door_Sensor_Notification*  
    *$$STATUS:* 
* Ref ID: 205 Name: Back Door Sensor Tamper Switch - **_not subscribed_**

## Node 28 - COMPLETED
### Manufacturer
* Jasco
* 14318 Switch
#### Parent
* Ref ID: 206 Name: Lighting Garage Inside Garage Light - **_switches.yaml_**  
    * Subscribe:  
    *CRUD-06/mcsMQTT/Garage/Lighting/Inside_Garage_Light/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Garage/Lighting/Inside_Garage_Light
    
## Node 29 (Phantom)

## Node 30 - COMPLETED
### Manufacturer
* Homeseer
* DS100
#### Parent
* Ref ID: 208 Name: Access Control Garage Laundry/Garage Door Sensor Root
#### Children
* Ref ID: 209 Name: Laundry/Garage Door Sensor Battery - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Garage/Access_Control/Laundry-Garage_Door_Sensor_Battery*  
* Ref ID: 210 Name: Laundry/Garage Door Sensor Notification - **_sensors.yaml_**     
    * Publish:  
    *CRUD-06/mcsMQTT/Garage/Access_Control/Laundry-Garage_Door_Sensor_Notification*  
    *$$STATUS:* 
* Ref ID: 211 Name: Laundry/Garage Door Sensor Tamper Switch - **_not subscribed_**  

## Node 31 - COMPLETED
### Manufacturer
* Homeseer
* WS200
#### Parent
* Ref ID: 545 Name: Appliance Kitchen Disposal Root
#### Children
* Ref ID: 546 Name: Kitchen Disposal Central Scene - **_not subscribed_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Appliance/Kitchen_Disposal_Central_Scene/Control*  
* Ref ID: 547 Name: Kitchen Disposal - **_switches.yaml_**
    * Subscribe:  
    *CRUD-06/mcsMQTT/Kitchen/Appliance/Kitchen_Disposal/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Appliance/Kitchen_Disposal*  
    
## Node 32 - COMPLETED
### Manufacturer
* Homeseer
* WS200
#### Parent
* Ref ID: 548 Name: Appliance Kitchen Dishwasher Power Root
#### Children
* Ref ID: 549 Name: Kitchen Dishwasher Power Central Scene - **_not subscribed_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Appliance/Kitchen_Dishwasher_Power_Central_Scene*  
* Ref ID: 550 Name: Kitchen Dishwasher Power - **_switches.yaml_**  
    * Subscribe:  
    *CRUD-06/mcsMQTT/Kitchen/Appliance/Kitchen_Dishwasher_Power/Control* 
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Appliance/Kitchen_Dishwasher_Power*  

## Node 33 - COMPLETED
### Manufacturer
* Jasco
* 14318 Switch
#### Parent
* Ref ID: 53 Name: Lighting Entry Way Outside Entryway Light - **_switches.yaml_**   
    * Subscribe:  
    *CRUD-06/mcsMQTT/Entry_Way/Lighting/Outside_Entryway_Light/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Lighting/Outside_Entryway_Light*

## Node 34 - COMPLETED
### Manufacturer
* Jasco
* 14318 Switch
#### Parent
* Ref ID: 1075 Name: Lighting Garage Outside Garage Light - **_switches.yaml_**
    * Subscribe:
    *CRUD-06/mcsMQTT/Garage/Lighting/Outside_Garage_Light/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Garage/Lighting/Outside_Garage_Light*    

## Node 35 - COMPLETED
### Manufacturer
* Homeseer
* WD200
#### Parent
* Ref ID: 1078 Name: Lighting Kitchen Kitchen Light 2 Root
#### Children
* Ref ID: 1079 Name: Kitchen Light 2 Central Scene - **_sensors.yaml_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_2_Central_Scene*  
    *$$STATUS:*
* Ref ID: 1080 Name: Kitchen Light 2 - **_lights.yaml_** 
    * Subscribe:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_2/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_2*  

## Node 36 - COMPLETED
### Manufacturer
* Homeseer
* WD200
#### Parent
* Ref ID: 1081 Name: Lighting Kitchen Kitchen Light 3 Root
#### Children
* Ref ID: 1082 Name: Kitchen Light 3 Central Scene - **_not subscribed_**
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_3_Central_Scene*  
* Ref ID: 1083 Name: Kitchen Light 3 - **_lights.yaml_**
    * Subscribe:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_3/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_3*  

## Node 37 - COMPLETED
### Manufacturer
* Homeseer
* WD200
#### Parent
* Ref ID: 1084 Name: Lighting Kitchen Kitchen Light 1 Root
#### Children
* Ref ID: 1085 Name: Kitchen Light 1 Central Scene - **_not subscribed_**  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_1_Central_Scene*  
* Ref ID: 1086 Name: Kitchen Light 1 - **_lights.yaml_**
    * Subscribe:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_1/Control*  
    * Publish:  
    *CRUD-06/mcsMQTT/Kitchen/Lighting/Kitchen_Light_1*  
    
## Node 38 - COMPLETED
### Manufacturer
* Homeseer
* WS200
#### Parent
* Ref ID: 1087 Name: Lighting Entry Way Inside Entryway Root
#### Children
* Ref ID: 1088 Name: Inside Entryway Light Central Scene - **_not subscribed_**
    * Publish:  
    *CRUD-06/mcsMQTT/Entry_Way/Lighting/Inside_Entryway_Light_Central_Scene*  
* Ref ID: 1089 Name: Inside Entryway Light - **_switches.yaml_**
    * Subscribe:
    *CRUD-06/mcsMQTT/Entry_Way/Lighting/Inside_Entryway_Light/Control*  
    * Publish:
    *CRUD-06/mcsMQTT/Entry_Way/Lighting/Inside_Entryway_Light*ls