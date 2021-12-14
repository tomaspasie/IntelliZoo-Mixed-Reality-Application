###### Made by Tomas Pasiecznik

# IntelliZoo | Mixed Reality Application Proposal
In this project, I proposed an app for use in zoological facilities & designed its user interface using Figma.

## Executive Summary
Mixed reality is changing the way several industries operate day-to-day. Analyzing the current situation of zoological facilities, I have identified it as an industry that has the potential to greatly benefit from these new technologies. Currently, zoos need help collecting, storing, and analyzing data that will help them care and learn from their animals. From creating a more efficient workplace to increasing security at the zoo, the potential uses for mixed reality in zoos are seemingly endless. To bring these ideas to life, I am proposing an application I designed called IntelliZoo.

## Intended Users | Who is your intended user or users?
The intended users of this app are zookeepers who are responsible for the care of animals at a zoo. These are people who need quick and easy access to data about all the animals in their facility. The app can adapt to be used by upper management at the zoo and even its visitors in the future.

## Existing Solutions | What existing apps if any are similar to your proposed app?
After researching if there are any existing apps that are similar to my proposed app, I have not found any that are similar. This app fits a gap in a very specific niche. Although some zoo management systems software exist, none apply mixed reality along with the forward-thinking features included in my proposed app.

## Intended Use | What will the product do? How is it used?
This application is intended to be used as a data visualization software and management system. One of the primary goals of the app is to foster efficiency and facilitate data-driven decisions. Using the 3D interactive maps feature, users can keep track of where animals are located in the facility, what enclosures are empty, and what enclosures are showing security risks. This is the part of the app where the mixed reality features are most noticeable as users will be able to rotate and analyze a 3D map of the zoo in front of them. Another way users can check on the animals is through the “Live Cam” feature. All past live cam footage can be accessed through the “Past Live Footage” feature on the options panel. The app also has an animal-specific notes feature which can be used by users to communicate general comments or concerns about an animal. These notes, along with temperature levels, humidity levels, and past live cam footage are all stored in the cloud. Keeping these records are very important to help prevent or solve future problems.
The “New Note” feature is what allows notes to easily be added to the system. It can utilize a mixed reality keyboard or voice-to-text for typing. The “Update Feeding” feature is used for updating the system when an animal is fed. If feeding details are not updated by the next scheduled feeding time, users will get notifications on their devices to go feed that animal. The “Historical Details” feature allows users to see historical feeding, enclosure, and notes data. The “Security Alerts” feature allows users to view any current or past security risks caught by the system or other zookeepers. Any animal with current security risks will have proper markers for the user to easily be able to see and not miss them. The “Veterinary Data” feature allows users to see who that specific animal’s veterinarian is. It will also display the veterinarians contact information and give the user the ability to contact them directly from the application. The “Notify Visitors” feature allows users to notify all the visitors of the zoo that a specific animal is being fed. The “Call Management” feature allows users to directly contact upper management. The “Staff Information” feature allows users to see what zookeepers and other employees are currently at the zoo.

## User Experience | What will the user experience while using the product? How will it make them feel?
The user experience of the final product will make users feel as if they have become an omniscient zookeeper, knowing everything that is going on around them. Users will have access to all of the zoo’s data at their fingertips. As a result of this, users will experience increased productivity in their work at the zoological facility. The interface was designed with the user experience of the end-user in mind and users will certainly be able to feel that as they use the application daily.

## App Interface | Describe the app interface. What will the users see and hear and how will they interact with the AR elements?
The app interface is made up of three panels and a 3D interactive map. The panel in the center is the main panel the users will see where most of the data is displayed. When an animal is selected, its name, feeding details, enclosure details, live cam, and recent animal-specific notes are displayed. The live cam feature can be made “full-screen” using the button on the bottom right of the video. This will cover most of the interface, letting a user focus on the video. The panel on the right displays a list of options which contain several key features of the application. The panel on the left allows for easy switching between animals that are currently in the zoo. Animal selection can also be done through the 3D interactive map located under the panel in the center. A button to toggle the 3D rotation of the map is located near the bottom right of the map. This map shows each enclosure that is present within the zoo in a certain color.  
  
•	If an enclosure on the map is green, this means there is an animal in it, and it is secure.  
•	If an enclosure on the map is grey, this means the enclosure is empty.  
•	If an enclosure on the map is red, this means there is a security risk present.  
•	If an enclosure on the map is blue, this means that enclosure is currently selected.  
  
Since only one animal can be selected at a time, only one enclosure at a time will ever be blue. When an animal is selected, the name of the animal will also be highlighted in blue on the left panel. A button to toggle “Dark Mode” can be found in the panel on the right. This was implemented in the app because it is an option that many users like to have in the applications they use.

## Technologies Required | What technologies will be required? Smart phone, AR glasses, other peripherals?
The hardware required for a user to use this app is a mixed reality headset such as the HoloLens 2.

## App Benefits | How will using this product be a beneficial user experience?
One benefit of the app is that, using historical data, the app would be able to suggest things such as security or veterinarian check-ups through the mixed reality interface. It will also allow several users to be connected with each other through the animal-specific notes feature among the various other ones as described the other sections of this proposal. In a matter of seconds, users will be able to contact any person within the facility or access any piece of data they need. Finally, users will be able to find an empty enclosure for any new animal that comes into the facility quickly as they are clearly labeled “Empty” in the 3D interactive map.

## App Name | What is the name of your app? What does the name you chose convey to the user?
The name of my app is IntelliZoo. I chose this name because it conveys the data-driven nature of the application and further establishes it as a smart solution for zoological facilities.

## Sketch of What the User Will See (App Interface) | Software Used: Figma
 
![User Interface](/IntelliZoo-User-Interface.png "Screenshot of user interface.")
![User Interface (In Use)](/IntelliZoo-User-Interface-In-Use.png "Application being used at a zoo.")

## Cognitive Walkthrough | Include at least three main features and action statements for each.
Input method may vary by Mixed Reality headset, for these cognitive walkthroughs, we will assume the mixed reality headset has hand-tracking capabilities and will use the word “select” when that input capability is to be used. 
### Action Statements
Objective (Features): Analyzing a Tiger’s past live footage, then creating a new note of the findings, and finally calling the Tiger’s veterinarian.

1.	I selected the Tiger from one of the two available methods (ANIMALS panel or 3D interactive map).
2.	I acknowledged the most recent note to know what I have to do.
3.	I activated the “Past Live Footage” Feature.
4.	I scrolled through the videos of past live footage that were available to review.
5.	I selected a video I wanted to review, and it played automatically. 
6.	I paused the video to analyze it.
7.	I finished analyzing the video and went back to the video list.
8.	I went back to the Tiger’s main page.
9.	I activated the “New Note” feature.
10.	I chose an input method for the note (Voice-To-Text or Keyboard) and recorded it.
11.	I finalized the note I just recorded.
12.	I made sure the note was posted successfully, and went back to the Tiger’s main page.
13.	I activated the “Veterinary Data” feature 
14.	I found the veterinarian’s name and contact information.
15.	I called the veterinarian through the application.
16.	I got advice from the veterinarian and went back to the Tiger’s main page.
 
![Cognitive Walkthrough](/IntelliZoo-Cognitive-Walkthrough.png "Cognitive Walkthrough")

My cognitive walkthrough goes through my app’s interface and interacts with three of its main features. These features are the “Past Live Footage” feature, the “New Note” feature, and the “Veterinary Data” feature. The action statements will give you a good idea of how I intend the product to be used. In addition to this, one can get a good feel of the user experience. Overall, this shows how easy it is to quickly analyze and communicate some data using my proposed application.
