# ANSMedia-Common-Toolbar
#WIP Toolbar which is planned to be common across our current and future addons.

# Arrestors  
(Works with any plane with a tailhook whilst on any runway)

The arrestor slows you down to zero if you are on any runway above 30knots with the tailhook down until you release the tailhook or go more the 1m off runway. Base Arrestors will be removed soon as causing too many issues. Any future ANSMedia projects will. It is recommended you always use our arrestor button anyway as it will always slow you down if you are on the runway and with the tailhook deployed (it will release if you bounce or go off the end). Holds aircraft in position until you retract the tailhook.

It will now detect whether you are needs an ANSMedia Moving Carrier and apply a speed offset to the zero speed.

Animated Arrestorwires are WIP

Currently there are 2 ways the arrestor script is activated. If it detects you have caught a cable on a ansmedia carrier it will activate automatically as long as the toolbar is open. (MOVING CARRIER SUPPORT FOR ADVANCED ARRESTOR WIP). Alternatively you can activate the fake arrestors from the simple Catobar Page which will slow you down if you are on ground with tailhook deployed.

Future Update to Change speedoffset so works with any moving carrier also Planned.




# Catapult 
## Catapult Buttons on Controls Page

ONLY FOR USE ON ANSMEDIA CARRIERS (moving carrier support Also WIP)

1. Press Either aft or forward Carriers button. It will then direct you onto the catapult line. 

2. Press Button again when Lined up and message reads Click to lineup. Script will then fix any small inaccuracies in your lineup. It will then Initiate A hold script to stop any forward velocity.

3. Press Press Button Again to activate the Launch script when Click to Launch is Shown. You will be then be Launched 5 Seconds After your throttle is set above 80%. Toolbar Will then show Launch Complete




## Catapult Buttons on Simplified Catobar Page
(works on Any runway/carrier that is not moving aswell as ANSMedia Moving Locations).

 Speed Offset and Direction inputs are planned so this will work on all carriers.

There are 2 buttons. One for standard sized catapults (90m) and one for short Catapults (55m). The front catapult on the QE arkroyal proposal is a shorter one (55m) for drones and fighters only and accelerates quicker hence why the sort option is Included.

Simply press The button When on ground and below 30knots. This will initiate a Forward speed hold of zero (+speedoffset if your on an ANSMedia moving carrier). It will then Initiate the launch 5 seconds after your Throttle is set above 80%. 




Catapult Script Terminating velocity is 80m/s (155knots) for all Versions





## Pushback
(Works with any plane when on ground with idle Throttle)

Pushback of max 10knots - where velocity and turning rate are directly proportional to joystick position not just on-off speed and pointing change. It checks whether your throttle is below 10% and whether you are on the ground to make sure it doesn't trigger in the air and stops the script if you say fall off a carrier or increase your throttle. If you manually press stop pushback it will engage parking brake. If it stops the pushback script due to being off the ground, throttle position or reset being pressed it will not engage the parking brake.

The pushback also has anti-tip functionality aswell for both roll and pitch. It will now detect whether you are needs an ANSMedia Moving Carrier and apply a speed offset to the zero speed.

Custom User inputted Speed offset and direction for use on non-Ansmedia moving carriers is Planned. (This also would allow you to set a taxi cruise speed)

Custom Joystick Deadzone values and Max Speed is Also Planned.

Because of the Anti-tip functionality It is recommended you use this on Aircraft carrier Lifts. MSFS ground position changes are slow so will cause wheels to judder on lifts. Parking brakes will hold you aswell but Anti-tip should reduce Aircraft body movement and will make judders less visible especially in cockpit view.




## Additional FAQ:

The toolbar is planned to remain free.

We will not however allow forks or publishing altered version of our toolbar without express permission from us.

Yes one of the images above is a teaser of our E2D aswell

More features, Including non carrier features, are planned and this is a dependency of our carrier Project


Also Available on fs.to and simmarket

Check out our Demo of the carrier here: https://flightsim.to/file/75128/hms-queen-elisabeth-catobar-conversion-project-ark-royal

Or get access to more locations and enable access to the hanger by purchasing the full version https://secure.simmarket.com/ansmedia-hms-queen-elisabeth-carrier-catobar.phtml

Please consider a small Donation: DONATE

(The toolbar may be moved later to its own repository once more of the planned features are added)
For support and to see what we are working on next check out our Discord: ANSMedia
