# Jeremy Yarley

##### Location: Connecticut, USA 🇺🇸
##### Primary Language: Swift (UIKit and SwiftUI)
##### Secondary Languages: Python, Perl, VBA, Matlab, Fortran

### About Me
I'm an aerospace engineer by degree, an electro-mechanical engineer by practice, and an iOS developer by night. During the day I try to figure out why a pump or motor on an airplane or helicopter isn't working correctly, and then I come home to figure out why one of my app's animations are broken. I've curated some of my projects below, and hinted at some of the other projects I can't go into vast detail about. I hope you enjoy! 

If you want to see what I'm working on now, follow me on Twitter: @JeremyYarley


## Capstone Senior Design Project
The purpose of the project was to design, contstruct, test, and fly a seagliding aircraft for the Naval Research Lab. It had to be able to rocket launch from a rail, transition to powered flight for 15 miles, land in the water, submerge, and seaglide to a depth of 100 meters and resurface. My personal responsibility on the team was propulsion, so I was in charge of choosing the motor, integrating it with the aircraft system, and performing a wind tunnel test to validate it would work and determine range capabilities. If the picture below didn't give a hint, it was a success! 

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/786D3AF4-D4B9-457B-BA80-2ACC6A12A63B.jpeg?raw=true"/>
</p>
(Fair disclosure, that's not me, it's my teammate) 


## Professional Projects
Unfortunately I shouldn't go into a lot of detail here since all of my professional projects are either military aircraft or proprietary. The big thing is that I can't take or share any pictures, which takes most of the fun out of it. 

That being said, I started performing structural analysis work for Pratt & Whitney engines that go on various aircraft (including a few neat fighter jets) using a very expensive software called ANSYS Classic. After a brief detour of climbing cell phone towers I transitioned to the world of fuel pumps, primarily for small aircraft and helicopters. My role here was to fix problems that would come up in the field or the manufacturing process. My horizons expanded further by supporting another product line that makes hydraulic vane motors for the G500 and G600 (like in the rap song), which is a complex combination of hydraulics, mechanics, and electronics. 


## iOS Development

### GridPlan

[GridPlan](https://apps.apple.com/app/id1550443458) is a minimal calendar app with beautiful animations and a unique aesthetic, currently available on the Apple App Store.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/GridPlan-Collaborated.png?raw=true"/>
</p>

#### Description

GridPlan is a minimalistic calendar app that allows the user to add, edit, and delete important events. Each event has a title, start/end times, start/end dates, a personalized color option, and a location. GridPlan uses Apple's MapKit API to search for an address or location to be included with the event. All data is saved on Apple's CloudKit API in the user's private database, so there are no concerns about data privacy whatsoever. GridPlan leverages MatchedGeometryEffect to create beautiful animations when presenting days and events. 

##### Technologies: SwiftUI, CloudKit, MapKit, MatchedGeometryEffect



### Foster

[Foster](https://apps.apple.com/us/app/id1515152448) is an iOS app currently available on the Apple App Store built with SwiftUI with Firebase as the backend service.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/Github-Collaborated.png?raw=true"/>
</p>


#### Description

Foster allows users to create and customize wish lists for special occasions such as birthdays, holidays, barbecues, and much more. Gifts can be added to the list and customized to include a website link and other details specific to the user (shoe size, color, amount, etc.). Wish lists can be shared with friends and family through text, email, twitter, and more. When a gift is purchased, the purchaser simply marks that gift as purchased so that nobody else purchases the same gift.

##### Technologies: SwiftUI, Firebase API, Universal Links


### COVID Chart
[COVID Chart](https://github.com/getyarley/COVID-Tracker) is an iOS app built with SwiftUI that shows recent information about COVID-19 for the United States. This project includes a Widget to display the user's most recent selection right on the homescreen! 

_COVID Chart was submitted to the Apple App Store but was rejected because it is not affiliated with a legal healthcare organization. Submitting an appeal did not change the outcome. Unless you happen to be a reputable healthcare corporation, I wouldn't recommend submitting a similar app to the app store._ 

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/COVID-Chart-Collaborated-Dark.png?raw=true"/>
</p>

The user selects a region and a search criteria, the appropriate JSON data is loaded from The COVID Project API, and the graph automatically and seamlessly updates to display the most recent trends. Search criteria is saved locally with UserDefaults, which is then reused at launch to load relevent data for each specific user, as well as keep the Widget up to date. 

The data for this app was provided by The COVID Tracking Project, a volunteer organization as part of The Atlantic. 
[Go to The COVID Tracking Project website](https://covidtracking.com/)

##### Technologies: WidgetKit, SwiftUI, UserDefaults, JSON Encoding/Decoding


### NY Times API Reader

[NY Times API Reader](https://github.com/getyarley/NYT-API-Reader) is an open source iOS app built with Swift, UIKit, and UserDefaults and can be viewed on GitHub.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/NYT-Summarized.png?raw=true"/>
</p>

This project uses the free NY Times API to read JSON files and display them in a simple format on your iOS device. The user has the ability to view the title, date, and abstract for several articles. Loaded articles can be filtered based on several categories (Most Viewed, Most Shared, Most Emailed) and recent time periods (Last 24 Hours, Last 3 Days, Last 30 Days). Articles can be bookmarked and are saved automatically in UserDefaults. Bookmarked articles are reloaded on launch and are available to the user. 

##### Technologies: Swift, UIKit, UserDefaults, JSON Encoding/Decoding

_Disclaimer: This is NOT meant for production, and could possibly provoke legal action from the NY Times if you attempt to make a profit off of the data provided by their free API. Let's not take advantage of companies like the NY Times for giving us wonderful free API's like this._



### SwiftUI Music Player

[SwiftUI Music Player](https://github.com/getyarley/SwiftUI-Music-Player) is an open source iOS app built with SwiftUI that uses AVAudioPlayer to play music locally.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/Music-Player_Collaborated.png?raw=true"/>
</p>

This is an app I built to practice SwiftUI, combine (reactive programming), and AVAudioPlayer. The user can select songs preloaded into this app (not very useful for a released app) and play them with some basic controls such as play, pause, skip forward/backward 15 seconds, and restart. The user can also favorite songs and the view automatically updates to reflect the change.

##### Technologies: SwiftUI, AVAudioPlayer, reactive programming (Combine)


