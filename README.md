# LaunchDarkly
Deanna Cortina Interview for Launch Darkly 

This feature flag is set up to change the text displayed to the customer depending on their country location. 

If this user in the in US, it will display 'Hello Darkly'
If this user is not in the US, it will display 'Hello World'

First, recreate this feature flag within Launch Darkly app by following the steps below. 
1. Create two segments 'US' and 'Non-US'
2. Create targetting rules 
	- If 'user is in segment' 'US' serve 'true'
	- If 'user is in segment' 'UK' serve 'false' 

Next we will setup the SDK using the file provide on Github.

1. Install Node. 
2. Clone repo provided on GitHub. 
3. Replace the SDK key on line 18 where it says 'SDK KEY HERE'. 
4. In the terminal, write the command 'node index.js'.
5. Open webpage to see text displayed and your feature flag in action! 
