![LinkedIn Banner](https://github.com/steven-hill/steven-hill/assets/98730693/b23c070a-1d24-4aa4-bbb6-59088cac9aa9)

# Steven Hill
## iOS developer

- 👋 Hi, I’m @steven-hill
- 👀 I’m interested in software development, mobile gaming, sports, languages and travel.
- 🌱 I’m a junior iOS developer looking for an entry level iOS developer role.
- 📫 You can reach me on [X (formerly Twitter)](https://twitter.com/H_Steven1) and on [LinkedIn](https://www.linkedin.com/in/steven-hill-570913230).


## About me

I’m focused on writing clean, maintainable code, and helping companies build great mobile app experiences. My first Apple device was an iPad. Learning iOS development was born out of a curiosity about how the iPad works and how it can become anything in the user’s hands. Since then, I've been learning how to build mobile app solutions with Swift, UIKit and SwiftUI. I love how software development gives us various tools to use to solve interesting problems. There are always more exciting things to learn!


## Skills

<img src="https://github.com/devicons/devicon/blob/master/icons/apple/apple-original.svg" alt="Apple logo" width="50" height="50"> <img src="https://github.com/devicons/devicon/blob/master/icons/swift/swift-original.svg" alt="Swift logo" width="50" height="50"> <img src="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-original.svg" alt="Xcode logo" width="50" height="50"> <img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original.svg" alt="GitHub logo" width="50" height="50"> 

- Swift
- iOS
- UIKit
- SwiftUI
- Xcode
- GitHub


## Projects

- 🎬 [MovieList](https://github.com/steven-hill/MovieList) - a UIKit project to search for movies using the iTunes API.

- 📝 [Job application tracker](https://github.com/steven-hill/Job-application-tracker) - a UIKit project to track job applications using CoreData.
  
- ☀️ Weather app
  - I'm currently building this app, and it's my first SwiftUI app.
  - Written in Swift 5.9 with Xcode 15.1.
  - The iOS deployment target is 17.0.
  - It's a single view iOS app with a widget extension, supporting a small and medium sized widget.
  - It uses CoreLocation to get the user's location (if the user grants permission). Then it makes two network calls using the Open Weather API to get the current weather data for that location. 
  - The app then displays the data on screen or presents an alert if an error has occurred.
  - Network code uses the Result type and completion handlers.
  - To handle different size classes I used GeometryReader, removing many hard coded values which I had initially used when building out the UI.
  - There is a floating button in the bottom right corner which the user can use to refresh the data.
  - It also uses WidgetKit for the home screen widgets (small and medium sizes are supported), which provide glanceable information for the user on their home screen.
  - The app uses XCTest (and a bit of Combine) for unit tests to test the weather view model. The test coverage for the app target is 91.1%.
  - This app has allowed me to learn and practice MVVM, more frameworks (SwiftUI, CoreLocation, WidgetKit and XCTest), dependency injection and using Instruments to check for memory leaks.
  - By practicing and picking up these frameworks I delved a lot into Apple's documentation and WWDC videos. I started with the documentation when implementing the frameworks, and, as a result, I've become more confident and familiar with Apple's documentation. 
