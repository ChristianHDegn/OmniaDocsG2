Working with Events
===========================

Using a number of options in Omnia, together with a few dedicated options, information can be published about different kinds of events (training sessions is one example) and Event Managers can handle registration of participants for the event.

**Note!** Event Manager is not a separate permission, it's a term we use for the person that creates and manages an event. The permission an Event Manager needs is Page Author, for the page where the event is managed.

Important Event options:

+ Users can register to a Participant list. The list keeps track of available seats.
+ Users can register to a Standby list if all seats are taken.
+ Colleagues will automatically be moved from the Standby list to the Participant list and can also be moved manually by an Event Manager.
+ Users can register a number of (not named) colleagues that will accompany them to the event.
+ A user can register for others.
+ Users can edit or remove their own registrations.
+ External users that has been invited in the Azure AD, can use the Event Management options.
+ Event Managers can create new events, can edit all registrations and remove registrations if needed.
+ Event Managers can export the Participant list to Excel and can communicate with participants through e-mail.
+ Event managers only needs Author permissions.

If Event Management is connected to an Outlook Calendar, this additional option is used:

+ The Participant List displays a Status icon to indicate if the registered user has accepted the event in his or her calendar. 

**Note!** In Omnia on-prem, Use personal exchange calendars. Support for Exchange server 2016 and 2019.

There's a number of settings available to decide how Event Management will work. It can for example be set that a Reservation list should not be available and that users should not be able to register for others.

There's two specific blocks available for Event Management (see the links below). In all other aspects, you use available options in Omnia for Page Types so Event Administrators can create pages with the information they want to display for the Event.


.. toctree::
   :titlesonly:

   /setup/eventmanagement/index
   /blocks/blocks-event-management/index
   creating-new-event/index
   copy-event/index
   administer-event/index
   register-for-event/index
   implementation-example/index

