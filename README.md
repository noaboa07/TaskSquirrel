# TaskSquirrel - A Task Management App

TaskSquirrel is a task management app designed to help parents motivate their children to complete household chores effectively. The app provides a list of tasks for users, tracks task completion with photo evidence, and uses location tracking to display where the task was completed. This project demonstrates fundamental skills in iOS development, including navigation, data handling, and UI implementation.

## Key Information

- Developer: **Noah Russell**
- Development Time: Approximately 3 hours
- Technologies Used: Swift, UIKit, CoreLocation, Xcode

## Features

The following required features have been implemented to create a functional task management app:

- [✅] Task List View: Displays a list of tasks with clear, actionable details.
- [✅] Task Detail Navigation: Allows users to tap a task and navigate to a detailed view with specific information about the task.
- [✅] Photo Attachments: Users can attach photos to tasks, marking them as complete.
- [✅] Location Tracking: Captures and associates the location where a photo is taken with the task.
- [✅] Map Integration: Displays task completion locations on an interactive map.

## Optional Features

The following optional feature has not been implemented yet:

- [❌] Camera Integration: Users cannot directly snap photos using the device’s camera from within the app (to be implemented in future iterations).

## Future Enhancements

The project has room for additional improvements:

- [🔲] Implementing direct camera functionality for seamless task photo attachments.
- [🔲] Adding notifications and reminders for pending tasks.
- [🔲] Integrating a progress tracker for gamified task completion.
- [🔲] Building a backend system to sync tasks across multiple devices.

## Video Walkthrough
Below is a video walkthrough showcasing the core functionality of TaskSquirrel:

<img style="max-width:300px;" src="lab-task-squirrel/Lab 1.gif" alt="TaskSquirrel Demo">
GIF created using VEED.io.


## Development Process

This project was built as part of an academic assignment to explore iOS development using Xcode. The following skills and tools were utilized:

- UIKit: For building the user interface and managing app navigation.
- CoreLocation: To capture and display the location of task completion.
- MapKit: For embedding an interactive map view in the task detail screen.
- MVC Architecture: To ensure clean separation of concerns and code modularity.
- Git Version Control: Used for tracking changes and managing project iterations.

## Challenges Faced
- Integrating location tracking with photo attachments was initially tricky but resolved by using CoreLocation in tandem with the UIImagePickerController.
- Managing app navigation and passing data between the task list view and detail view required careful handling of delegation and data flow.

## Key Takeaways
- Strengthened understanding of Xcode’s interface and debugging tools.
- Gained experience working with iOS frameworks like CoreLocation and MapKit.
- Improved ability to structure iOS applications using best practices.

## Technologies and Tools

- Language: Swift
- Frameworks: UIKit, CoreLocation, MapKit
- Development Environment: Xcode 14.0+
- Version Control: Git

## License

TaskSquirrel is licensed under the Apache License 2.0.
You may obtain a copy of the license at:
http://www.apache.org/licenses/LICENSE-2.0
