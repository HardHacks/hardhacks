# CodePath Final Project **HardHacks**

This project allows users to find listing of the newest game releases. 

##Wireframes

https://mhammond.proto.io/share/?id=c918957a-b946-4be6-a7f8-12c989b1ccad&v=1

## Video Walkthrough 
Here's a walkthrough of implemented user stories:

GIF created with [LiceCap](http://www.cockos.com/licecap/).


## User Stories

### What
Our app is centered on providing a detailed view of a user's lifestyle, through daily activity mapping.

Things that would be included would be: 
- A chart of the tracked activities
  -Sitting
  -Walking
  -Running
  -Driving
- A pie chart, showing the percentage of the day spent doing each activity
- A list of said activities, with times in hr:min, of time spent performing that activity today
- A method for storing user data, via a login to a service such as parse, allowing long term goal/stats tracking
- A user stats screen, showing the average time each day/week/month spent performing each activity

Things that could be potentially implemented later:
- Potentially a warning, if too long is spent doing an undesireable activity (sitting too long)
- Notifications to get up and move after X minutes sitting, workout time notifications
- Ability to set additional activities, and specify paramaters of said activity for tracking
- Incorporation of additional smart band / fitness sensor data

### Who
People are constantly looking for new ways to enhance their health and lifestyles. This app supports that by not tracking the amount of excersize done, but the daily lifestyle of the user, allowing them to view and adjust their daily habbits.

### Why
Many apps help users with their workout routine, or track activity, but it becomes very difficult to profile your lifestyle and patterns of activity throughout the day. This app allows you to view exactly what you were doing throughout the day, helping to plan new routines to improve lifestyle.

###Minimum Features

The following **features** will be implemented:
- [ ] Title screen with login feature, new user registration feature, and use without login button
- [ ] Main stats screen has dynamic pie chart, showing daily activity percentages for today
- [ ] Main stats screen has list of all activities being tracked, and numerical value of time spend on each
- [ ] Detailed stats screen can pull data from parse server, to display historical data and averages
- [ ] Detailed stats screen can show a chart of the current day, showing a timeline and what activities were occuring at certain times
- [ ] Settings screen allowing user to set various paramaters
- [ ] Ability to swap between imperial and metric units
- [ ] Ability to reset and erase all user data, online/offline or both

###Mightfinish Features
The following **optional** might be implemented:
- [ ] Multiple color shcemes, ability to select what activities are tracked
- [ ] Ability to set "snooze" times, times when tracking is disabled or set to a certain static activity
- [ ] Integration with various smart watch / wearable device sensors to improve detection / gather additional data

## Installation

- Do "pod install" with the podfile (requires cocoapods to be installed)
- Open the project *.workspace

## Usage

None so far

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History
None so far

## Credits
Jason Tan | Jaime Orellana | Michael Hammond

## License

Copyright [2016] [Jason Tan, Jaime Orellana, Michael Hammond]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
