---
name: 100 Days Of SwiftUI
tools: [Xcode, Swfit, SwfitUI, Project Apps]
image: /portfolio/assets/100daysofswiftui.jpg
description: This is a 100 days of challenge of coding in Swift using SwiftUI framework. I started this challenge on Mid November 2019 to learn more about SwiftUI which is recently released at WWDC19 conference.   
---

# 100 Days Of SwfitUI

I started the 100 Days of SwiftUI Challenge where I am spending at least couple hours of coding in Swift programming language for 100 days. I started learning iOS development with user interface tool kit framework UIKit during my Colleges years. After watching Apple’s WWDC19 conference, I felt I should get on this new tool kit framework SwiftUI. First I started with Apple’s developer page learning from tutorials of SwiftUI then I found 100 Days Of SwiftUI challenge and started coding, credits to  [@twostraws](https://twitter.com/twostraws){:target="_blank"}. Below is and would be a recap of everything I have accomplished during 100 days of SwiftUI.

# Days 1-12: Introduction to Swift
In those days, I covered all the fundamentals of the Swift programming language even though I have been coding in Swift. There were short quizzes to solve after each topic completion. I mostly did those quizzes. I combined few days to finish faster just because I was behind the other challengers. I would recommend that you give good amount of time to each topic to master them.

# Days 13-15: Consolidation I
In these days, I did a lot of quizzes to cover my weak spots until I felt comfortable that I learned all the Swift language fundamentals covered in days 1 to 12.

# Days 16-24: Starting SwiftUI
In these days, I started building real SwiftUI apps. There were three projects. The first one, with together we created [WeSplit](https://github.com/adzguy/WeSplit){:target="_blank"} app which its a check-splitting app that you use after eating at a restaurant - you enter the amount cost of your food, select how much of a tip your giving, and many people are splitting with, then it tells you how much each person needs to pay. Link
After first project, there was a challenge to create your own app with similar view. From the option that’s given, I chose to create [Temperature](https://github.com/adzguy/ConvertTemp){:target="_blank"}, and [Volume](https://github.com/adzguy/VolumeConvrt){:target="_blank"} conversion apps. I also posted them on my twitter [@imadzguy](https://twitter.com/imadzguy){:target="_blank"}. <br>
The second project was about to use stacks such as VStack, HStack, ZStack to arrange views. Also colors, frames, buttons with images, and showing alert message at the end. Together we created [GuessTheFlag](https://github.com/adzguy/GuessTheFlag){:target="_blank"} app which is a guessing game that helps users learn some of the many flags of the world. <br>
On our third project, we focused on two fundamental components of SwiftUI: Views and Modifiers. We went through lots of details such as why SwiftUI use struts instead of classes, what’s behind the main SwiftUI view, why SwiftUI use “some View” for its view type, and sort of modifiers such as like conditional, environmental, and custom modifiers. In the end of this third project, we went back to our own created apps to change and create modifiers inside the code. Basically, we refactored our codes. 

# Day 25: Consolidation II
The 25th day, there was a challenge to create an app using what we covered in days 16 to 24. The app I created was a brain training game app that challenges players to win or lose at rock, paper, scissors. You can check on it in my GitHub repo [here](https://github.com/adzguy/RockPaperScissors){:target="_blank"}. 

# Days 26-34: Expanding my skills
In these days, we will be creating three projects. The first project we created together was a BetterRest app. This app basically does alert your ideal bed time asking you three questions. When do you want to wake up? How many hours of sleep do you want? And how many cups of coffee do you drink a day? I was introduced to DataPicker, Stepper, navigationBarItems, Date, DateComponents, and DateFormatter in SwiftUI. Moreover, I had learnt more about things we can built with using Apple’s frameworks like as Create ML and Core ML. I was familiar with Core ML when I created my Image detection app before SwiftUI. In this project, we created a machine learning model to use in our prediction with the accuracy of 89 percent to our ideal bed time using csv format data using Create ML framework. At the end of this project, the challenge was to change user interface so that it always shows its ideal bed time instead showing alert. You can check on my GitHub repo [here](https://github.com/adzguy/BetterRest){:target="_blank"}. 

# Day 35: Consolidation III
In this day, I have to create my own app called Edutainment which is half educational and other half is entertainment, using skills I have covered so far. Basically, user picks multiplication table and question amount from first or settings layout then presses a Go button which takes to the next layout. Next layout is asking questions according to the inputs on settings layout. At the end user seas the score and able to go home page to restart settings to play. App can be check out in my GitHub page [here](https://github.com/adzguy/Edutainment){:target="_blank"}. 

# Day 36-46: Scaling up to bigger apps.

In these days, we started to build bigger apps using new skills. We have completed 3 big projects including several challenges at the end of every each project. <br>
In first project, overall 7th project, I learned how to show another screen with sheet(), how to share data across screens using classes instead of struct, how to fetch and save JSON data using Codable protocol. The name of the app is [iExpense](https://github.com/adzguy/iExpense), which user can add expense to the main list by clinking navigationBarItem. When add button pressed, sheet() or new layout comes up to add an item amount in dollars, pick personal or business expense, and name of the expense. Then user able to delete item by swiping or clicking edit button on navigation bar. The challenges were to change color of item’s amount according to their price range, add Edit/Done button so users can delete rows more easily in addition for swipe delete, and add validation to the save button at sheet() so when user enters “fish” or another thing that can’t be converted to a integer, the would show an alert telling user what was problem.<br>
In our second project, overall 8th project, we created [Moonshot](https://github.com/adzguy/Moonshot) app that lets users learn about missions and astronauts that formed NASA’s Apollo space program. I got more experience with Codable, but more importantly I also worked with scroll views, navigations such as NavigationLink, and much more interesting layouts. The challenges were to add the launch date below the mission badge, to modify AstronautsView to show all the missions this astronaut flew on by retrieving complex JSON format data, and to make bar button toggle between showing launch date and showing crew names on the main page.<br>
The third project, overall 9th project, we focused on drawing in SwiftUI. I learned about path, shapes, insettable shapes, and more. We together draw several shapes such as Triangle, Rectangle, Color Cycling Circle, and Spirograph which is beautiful shape to see. I added the demo on my GitHub page named [Drawing](https://github.com/adzguy/Drawing). The challenges were to draw an Arrow, to make the line thickness of the Arrow shape animatable, and to create Color Cycling Rectangle by allowing to control the position of the gradient using a property. 

# Day 47-48: Consolidation IV
 47th day was the milestone day which is to creating an app in SwiftUI framework from scratch using skills I acquired from days 36 to 46. The app I created was a [Habit-Tracking](https://github.com/adzguy/Habit-Tracking) app. This app is for people who wants tp keep track of how much they do certain things. That might be learning a new language, exercising, or whatever they get to decide to track. Codable and UserDefaults were leveraged to load data and save all user data. 

# Day 49-59: Focus on Data
In these days we have created three projects together and did challenges individually. We started looking more carefully at how we send, retrieve, and store data in our SwiftUI apps. 
The first project we built a multi-screen app for ordering cupcakes called [Cupcake Corner](https://github.com/adzguy/Cupcake-Corner). We went deeper into Codable like adding Codable conformance for @Published properties, sending and receiving Codable data with URLSession and SwiftUI and more. As a challenge I implemented an informative alert for the user when the user places an order and there appears a fail - for example if there is no internet connection. For the second challenge I improved the validation of text fields because initially text fields were considered valid if they contain anything, even if it is just only whitespace. 
The second project we built [Bookworm](https://github.com/adzguy/Bookworm) app using one of Apple’s frameworks: Core Data which is responsible for managing objects in a database, including reading, writing, filtering, sorting, and more. We added few customization such as rating books using @Binding property wrapper, and emojis display according to the rate the books get. One challenge was to validate inputs it gets from forms because it was possible to select no genre for books, which caused a problem for the detail view of the book. Another challenges were to modify content view such as when book gets one star rate the name turns to red, and to add date attribute to the book entity so it gets the current date and time.
For the third project we went deeper on Core Data; How to create NSManagedObject subclasses in order to handle nil coalescing. How we ensure Core Data objects are unique using constraints and one to many, many to one, many to many relations of objects in Core Data. As a challenge I sorted objects to get used in its fetch request in NSSortDescriptor, and made string parameter that controls which predicate is applied. App is in [GitHub](https://github.com/adzguy/CoreDataProjectChallenges).

# Days 60-61: Consolidation V
On day 60, it’s time to build an app from scratch using what we learned on days 49 to 59. My job was to use URLSession to download some JSON from this url: https://www.hackingwithswift.com/samples/friendface.json - that’s a massive collection of randomly generated data for example users; use Codable to convert it to Swift types, then use NavigationView, List, and more to display it to the user. I called the app [FriendFace](https://github.com/adzguy/FriendFace). 
On the next day 61, @twotwats scope creeped and made us to save data using Core Data framework so app user can use the app offline. It was a great challenge to learn Core Data. I integrated what was asked to the [FriendFace](https://github.com/adzguy/FriendFace) app.

# Days 62-76: Views and View Controllers 
In these days, the difficulty started to ramp up as we look how we integrate code from framework outside of SwiftUI, including UIKit and MapKit. We built three projects together and did challenges after each project. Challenges were to add extra functionality to the app.
The first project [Instafilter](https://github.com/adzguy/Instafilter) app that lets user import photos from library then modify them using various image effects. We covered new techniques, such as Core Image framework and one important SwiftUI skill is to integrate with UIKit. The challenges were to try making the Save button show an error if there was no image in the image view; to make the Change Filter button change its tittle to show the name of the current selected filter; and experiment with having more than one slider to control each of the input keys user cares about. <br>
The second project [Bucket List](https://github.com/adzguy/BucketList) app that lets the user build a private list of places on the map that they intent to visit one day. The challenges were to re-write MapView, Circle, and Button as part of their own view; and fix the error during biometric authentication. <br>
The third project was about accessibly. For example, if app user is blind then the app should work well with the systems’s VoiceOver system to ensure UI can be read smoothly. In this project we looked at a handful of accessibility techniques, then looked at some of the previous projects we made to see how they might get upgraded.
As a challenges, I checked out view in [Cupcakes Corner](https://github.com/adzguy/Cupcake-Corner) app that uses an image which doesn’t add anything to the UI. So I found a way to make the screenreader not to read it out. Second challenge, I fixed the stepper in [BetterRest](https://github.com/adzguy/BetterRest) so that they read out useful information when the user adjusts their values. The third challenge was to do a full accessibility review for [Moonshot](https://github.com/adzguy/Moonshot). 

# Days 77-78: Consolidation VI
In day 77, I created [Friends](https://github.com/adzguy/Friends) from scratch that user can save people they met in conferences or meetups so they do not forget. So the app asks users to import a picture from their photo library, then attach a name and about of the person. <br>
In day 78, I added a map with a pin on that marked where they were that pin was added. 


more is about to come…

<!---<p class="text-center">
{% include elements/button.html link="https://github.com/YoussefRaafatNasry/portfolYOU" text="Learn More" %}
</p>
--->
