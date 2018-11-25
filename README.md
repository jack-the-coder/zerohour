# zerohour
Zerohour README

Zerohour is a cross between a to-do list application and a learning-management system. Unlike some other LMSs, which focus on a Facebook-like interface, Zerohour’s primary concept is the task. Tasks can be assigned by teachers to students or to classes. Students see a timeline with the tasks that have been assigned to them. When students click on tasks, they can see documents that a teacher attached to the task as well as an interface to upload deliverables. Additionally, since Zerohour aspires to be a complete task-management application, it will allow students to add their own tasks to the timeline for complete life scheduling. 

At the moment, Zerohour has not been written. Through experimentation with a variety of technologies, we hope that the best option can be chosen for the final product. 

The following technology stacks are in consideration right now: 
- Ruby on Rails (server-generated HTML)
- Ruby on Rails (REST API consumed by JavaScript front end)
- Django (server-generated HTML)
- Django (REST API)
- Snooze [Common Lisp] (REST API)
- Awful [Chicken Scheme] (server-generated HTML)

The application must include support for a variety of client devices, including iOS and web applications. Server-generated HTML options would act as progressive web apps (PWAs) with support for “Add to home screen” functionality. This way, the application could be used on both computers and iOS devices with the same interface. 

However, the interaction model for computers and iOS devices is very different, so a mobile-first UI would look strange on the desktop. For that reason, a REST API might allow for a simple backend with multiple modular frontends. Data would be passed as JSON or another notation from the backend to be put into HTML by the web client and to be placed into UI elements on the iOS app. 

Each of these options have been considered, but we’re not sure which to use. Please leave an issue with your opinion if you want to help! 

