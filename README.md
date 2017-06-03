# SmartApps
The Catch me inside SmartApp is designed to work with www.internalpositioning.com and a device that can run their client program to enable the tracking of the client devices through different rooms in the home. This is effectivly an upgrade to presence sensors that instead of offery a binary home/not home can determine what room of your home you're in. 

Users will need to go through and create a preference entry for each location in their home they want to use with the SmartApp. You'll also need to create a virtual switch for each location in in your home and then edit the else if section for your switches and locations. The last reequired step is editing the params to include your own group and user. 

This is a super rough early version where nothing is being dynamically configured. Consider this mostly a proof of concept.
