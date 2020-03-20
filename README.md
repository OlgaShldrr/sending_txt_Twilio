# Sending a text alert with Twilio

This project shows how to send a text alert with twilio in Python. For the automation this script needs to be scheduled to run as often as necessary.
Here is the project flow:

1. Read in data. This project uses some fake revenue data for office supplies sales
2. Loop through the data and create a dictionary with items which revenue meets the target
3. Register on Twilio, set up Twilio number
4. Set Twilio credentials as your environment variables for safe code sharing
5. If your dictionary's length is greater than 0, send a text message alert. 
6. Schedule this script for as often as needed (e.g. daily in the morning?)

You are set to go!
