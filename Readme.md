# Smart Monitor

  **Requirnments**

   1: You Need an Android Device/ Tablet

   2: MQTT Simulator

   3: OBD II Bluetooth Simulator.
   
   4: You are Good To Go. 

  **Working**
  
  The Smart Monitor App Allow you to view your device senosrs(Engine RPM, Coolant temperature, Speed, Mass AirFlow, Fuel, Engine Load, Voltage etc. ) data Periodically with the help of guauges and graphs it also helps you find your vehicle's location from your current location. it tells you a detailed data for each sensor also and some live data with the help of past data stored in the db for use. With the help of Smart Monitor you can keep a track on each sensor and your vehicle condition properly

 **Functionalities**

  *Add Device*

    Add Device let's you add your device. we have given two ways to a user add their device Either Via MQTT server or via Bluetooth Connectivity. The user can add device on their prefrence and can then view the data on the dashboard.

  *Dashboard*

    The Dashboard is used to view the data of the vehicle in graph an guages form or live data whichever user select it will show the value of the sensor in that particular style. Dashboardv also allows user to select the devices if there are multiple devices added for a single user, so He/She can select any one and can view it's data. Dashboard also has the option to go the the live data page where a user can view the details of each and every sensor particularly based on the default min max value or the values set up the user.

  *Rule Builder*

    The Rule Builder here is used to provide user with an option to set the low and high level values i.e., min and max values on their own or whatever they want to give if the user don't want to go with the defaukt values. Here the user can specify a rule inside a rule that is nested rule if He/She wants to set some particular aspects. 

  *Location*

    The Location Part is the part where we Show user the current location of the user and the loactions of the vehicle added in the app by the user. The user can view the location of all the vehicles which he added and can also go on to that vehicle's location by clicking on the particular vehicle in the bottomsheet where the vehicle's list is being shown. In addition to this if your vehicle is within 100m of your range then the bottomsheet will show with you for that vehicle otherwise it will show it's current location address.

  **Work Flow**

     *Add Device*

    * VIA MQTT *
    * 
    1: Click on Add Device
	2: Click on Customize your own device 
	3: Select MQTT
	4: Enter vehicle Name & It's Model
	5: then click on Add Device
	6: Set up Rules if you want or you can set afterwards in rule builder
	7: Click Take me to dashboard 
	
    *VIA Bluetooth*

    1: Click on Add Device.
	2: Click on Customize your own device.
	3: Select Bluetooth.
	4: Select the device from Paired Device list or scan for new device.
	5: then click the desired device.
	6: Set up Rules if you want or you can set afterwards in rule builder.
	7: Click Take me to dashboard.

  **Dashboard**

    1: select the device for which you want to view the data from drop down.
	2: select the graph/guage/live data frfom drop down.
	3: View the Value of 2 sensors on the dashboard screen in diffrent styles.
	4: click on the small Arrow icon near Gauges Drop down You will go to Live Data page.
	5: View the gauages for each sensor seperately there.
	6: View the list of all added vehicles in the box in right side Labeled as "My Devices". 

  **Rule Builder**

    1: Click on Rule Builder
	2: CLick Add Rule
	3: Select Sensor From Drop Down
	4: Provide it's Rule
	5: Write any custom message if you want to Write for any.
	6: Click on add rule and it's Done.

  **Location**

    1: Allow the permission for location.
	2: click on the vehicle in the bottom sheet.
	3: you will be redirected to the vehicle location's.
	4: you will be able to see the distance between your location and vehicle Location.

**Roadmap**

  This app is currently Available for automobile but we are trying to move it for the appliances like Refridgerators or AC etc. For now only two modes of connectivity are available i.e., Bluetooth and MQTT but for future the connection through Web Might also be there.

**License**

  Copyright @ DMINC  


