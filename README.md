### vacine_bash
This bash script queries https://vaccinespotter.org every minute.
That site is updated each minute, so I only run this script every minute.

### Requirements

You need to install jq. On a mac it is simply :

brew install jq

[Other installs are described here](https://stedolan.github.io/jq/download/)

You need a notifier. I used terminal-notifier. On a mac the command is:

brew install terminal-notifier

[For more information](https://github.com/julienXX/terminal-notifier)

### Notes

The script is currently set for Boulder, Colorado and 30 miles. You can change the reference latitude,
longitude to your location, and widen the distance. 

You can change to another state by changing the curl command 
You also need to change your reference latitude and longitude.

Thanks to vaccinespotter.org

Kristine M. Larson
https://github.com/kristinemlarson

