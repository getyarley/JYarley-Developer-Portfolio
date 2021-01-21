# Jeremy Yarley

#### About Me
I'm an Aerospace engineer by degree, a mechanical engineer by practice, and an iOS developer by night. See some of the projects I've done listed below, the first of which is available on the Apple App Store for free. 

##### Location: Connecticut, USA 🇺🇸
##### Primary Language: Swift (UIKit and SwiftUI)
##### Secondary Languages: Javascript (In Progress), Python, Perl, VBA, Matlab, Fortran


## Foster

[Foster](https://apps.apple.com/us/app/id1515152448) is an iOS app currently available on the Apple App Store built with SwiftUI with Firebase as the backend service.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/Github-Collaborated.png?raw=true"/>
</p>


#### Description

Foster allows users to create and customize wish lists for special occasions such as birthdays, holidays, barbecues, and much more. Gifts can be added to the list and customized to include a website link and other details specific to the user (shoe size, color, amount, etc.). Wish lists can be shared with friends and family through text, email, twitter, and more. When a gift is purchased, the purchaser simply marks that gift as purchased so that nobody else purchases the same gift.

##### Technologies: SwiftUI, Firebase


## COVID Chart
[COVID Chart](https://github.com/getyarley/COVID-Tracker) is an iOS app built with SwiftUI that shows recent information about COVID-19 for the United States. This project includes a Widget to display the user's most recent selection right on the homescreen! 

_COVID Chart was submitted to the Apple App Store but was rejected because it is not affiliated with a legal healthcare organization. Submitting an appeal did not change the outcome. Unless you happen to be a reputable healthcare corporation, I wouldn't recommend submitting a similar app to the app store._ 

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/COVID-Chart-Collaborated-Dark.png?raw=true"/>
</p>

The user selects a region and a search criteria, the appropriate JSON data is loaded from The COVID Project API, and the graph automatically and seamlessly updates to display the most recent trends. Search criteria is saved locally with UserDefaults, which is then reused at launch to load relevent data for each specific user, as well as keep the Widget up to date. 

The data for this app was provided by The COVID Tracking Project, a volunteer organization as part of The Atlantic. 
[Go to The COVID Tracking Project website](https://covidtracking.com/)

##### Technologies: WidgetKit, SwiftUI, UserDefaults, JSON Encoding/Decoding


## NY Times API Reader

[NY Times API Reader](https://github.com/getyarley/NYT-API-Reader) is an open source iOS app built with Swift, UIKit, and UserDefaults and can be viewed on GitHub.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/NYT-Summarized.png?raw=true"/>
</p>

This project uses the free NY Times API to read JSON files and display them in a simple format on your iOS device. The user has the ability to view the title, date, and abstract for several articles. Loaded articles can be filtered based on several categories (Most Viewed, Most Shared, Most Emailed) and recent time periods (Last 24 Hours, Last 3 Days, Last 30 Days). Articles can be bookmarked and are saved automatically in UserDefaults. Bookmarked articles are reloaded on launch and are available to the user. 

##### Technologies: Swift, UIKit, UserDefaults, JSON Encoding/Decoding

_Disclaimer: This is NOT meant for production, and could possibly provoke legal action from the NY Times if you attempt to make a profit off of the data provided by their free API. Let's not take advantage of companies like the NY Times for giving us wonderful free API's like this._



## SwiftUI Music Player

[SwiftUI Music Player](https://github.com/getyarley/SwiftUI-Music-Player) is an open source iOS app built with SwiftUI that uses AVAudioPlayer to play music locally.

<p align="center">
  <img src ="https://github.com/getyarley/getyarley-images/blob/master/Music-Player_Collaborated.png?raw=true"/>
</p>

This is an app I built to practice SwiftUI, combine (reactive programming), and AVAudioPlayer. The user can select songs preloaded into this app (not very useful for a released app) and play them with some basic controls such as play, pause, skip forward/backward 15 seconds, and restart. The user can also favorite songs and the view automatically updates to reflect the change.

##### Technologies: SwiftUI, AVAudioPlayer, reactive programming (Combine)


