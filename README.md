### vaccine_bash
This bash script queries https://vaccinespotter.org every minute.
That site is updated each minute, so this script only checks every minute.

### Requirements

You need to install jq. On a mac it is simply :

brew install jq

[Other installs are described here](https://stedolan.github.io/jq/download/)

You need a notifier. I used terminal-notifier. On a mac the command is:

brew install terminal-notifier

[For more information](https://github.com/julienXX/terminal-notifier)

### Notes

The script is currently set for Central Park in NYC and 6 miles. You can change the reference latitude and  
longitude to your location, and widen the distance as desired. 

You MUST change the curl command to use the correct state.

This latest version also prints out the street address and sorts by distance.

A big thank you to https://vaccinespotter.org 
They did the hard work.  Please consider donating to their suggested organizations, which include UNICEF
https://www.unicefusa.org/mission/covid-19/vaccine

Kristine M. Larson
https://github.com/kristinemlarson

