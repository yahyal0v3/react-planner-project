Models

-Event has many To Dos
-Task belongs to an Event

    Event
Title
Deadline
Description

    Task
Deadline
Description
____________________

Components

    Containers (2)
Event Form
Task Form
Events
Planner
Home

    Stateless (5)
About
EventCard
TaskCard
Header 
Footer 
____________________

Paths (3)

    Home
About Component
Event Form Component (Display inputs one at a time?)
Events Component (Limit 3?)

    Events
Events Component

        Planner
    Task Form Component
    Tasks Component

____________________

To Do
x-fix navbar links
x-when user clicks check out, completed false becomes true
x-EventShow buttons when pass deadline
x-update reducer
x-task deadline has to be before event
x-update event form

x-delete confirmation alert
x-fix horizontal scroll