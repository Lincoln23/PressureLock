# PressureLock
Group Project- Our project is a pressure activated system that allows an individual to unlock/lock their door by knocking on the pressure pad in a specific pattern.  It works by implementing an initial preset pattern that can be changed by the user and multiple users are able to set up their own patterns. To lock the door the user keeps constant pressure on the pressure senor for two seconds. When the pressure sensor detects pressure, it will check if the input matches the saved pattern. If the inputted pattern matches, the motor will be activated and unlock the door.

Designed an algorithm to track a user input pattern and store it into a text file using ofstream

Designed a function that matches the saved pattern to the input using  Boolean arrays

Created a logging function using getTime() and concatenated the time with the status of the system
