# SQL_Project_1

Business Requirements
You are working for Fanshawe College who are setting up a drone (small personal unmanned flying aircraft) sharing program and database called FanshaweDroneShare.  They would like to track the people borrowing/renting, and the specific drones and accessories in the program.

Drones and accessories like cameras, GPS, sensors, joysticks are kept at stations (often the local library branch but not always).  Each drone/accessory has a home station that Fanshawe employees will return it to occasionally (note there is no need to model/capture   this work). The system will also track the station the drones/accessories are currently at. The current station will only be changed when a drone/accessory is checked in, so the current station for a drone/accessory will never be unknown.  Note that Fanshawe may want to add other types of accessories in the future.

Stations have names and maximum number of drones that can be held, each of which are always stored. For each station, the system should be able to track the number of drones that are currently at the terminal.  Drones will always have identification markings regulated by Transport Canada, and drones and accessories have manufacturer name, weight (in grams), model names and serial numbers which are always available.  Some drones/accessories will also have a manufactured date (and some will not).

Pilots will set up accounts and will be charged for their use via those accounts. Accounts may cover more than one pilot, such as when a house of roommates sets up an account. Each pilot may also be associated with more than one account.

When a pilot checks out a drone/accessory, it will be kept track of in the system. A pilot is permitted to sign out multiple drones/accessories at the same time. For example, a single pilot may sign out a drone for personal use as well as a drone for a guest.  One drone/accessory will never be checked out to multiple pilots simultaneously.

The system will be used to store specific information when pilots open an account. It will need to track a pilot’s first name and last name, along with their Transport Canada drone pilot certificate number, SIN and date of birth. We also need to store the street address, city, province, and postal code for a pilot.  It is possible for multiple pilots to live at the same address (e.g. multiple pilots in the same house). It is also possible for one pilot to have multiple addresses in our system (e.g. home address, business address). The pilot’s name, SIN, drone pilot certificate and date of birth are all mandatory, but all other pilot information is optional.
For each account the opening date, current balance, and account number should be stored. The account number is a unique number created by another system at a bank, so will always be available. The opening date and current balance will also always be populated.
