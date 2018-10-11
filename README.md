# Map Integration Services

Integration of transportation services within Existing Map Services. First mentioned here:— https://twitter.com/jsfaq/status/1016574764029075461

@2018 Garrett Smith

Integrate Uber, Lyft, LimeBike, and other transportation services as route options in maps.

## Problem
Existing map APIs such as by Apple and Google don't provide sufficient transportation options.

Currently, map services have directions by driving, walking, public transit, and, for Google, bicycling.

Many other options include Uber, Lyft, Lime bike, and scooters. 

## Solution 
Provide region-specific transportation options.


## User story: Transportation Plan
1) User enters start and end locations into map application.
3) User is given options that include Limebike, Uber, Lyft, including best fare and time duration. 
3) User chooses the option he wants. 
4) a. If an application matching choice (3) is available on the user's platform, the user is prompted to switch to that application. 
 b.Otherwise, the application makes an attempt to provide transportation plan within the map application
5) User completes transportation option scheduling; payment is settled electronically.