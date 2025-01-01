# Community Portal Event

The **Community Portal Event** is a web application that allows users to participate in events and helps event organizers manage their event details. Built with **Django**, this platform enables users to browse events, RSVP, and ensure no scheduling conflicts. It also allows event organizers to create, manage, and monitor events along with attendee details.

Deployed on **Azure App Services**, this application ensures high availability and scalability.

## Features

### For **Normal Users**:
- **Browse and Participate in Events**: Users can view a list of available events and RSVP to those they wish to attend.
- **RSVP Validation**: Users cannot RSVP to events if the event's capacity is full.
- **Conflict Check**: Users cannot RSVP to overlapping events scheduled on the same day and time.

### For **Event Organizers**:
- **Create and Manage Events**: Organizers can create new events, update existing ones, and manage event details.
- **View Attendees**: Organizers can see the list of attendees who have RSVPed for their events.

## Key Technologies

- **Django Framework**: Used for backend logic, form handling, and validation.
- **SQLite/PostgreSQL**: Used for database management and data storage.
- **HTML, CSS, JavaScript**: For building and styling the user interface.
- **Azure App Services**: For deploying the application with scalability in mind.

## Installation

To get started with the project locally, follow these steps:

### Clone the repository
```bash
git clone https://github.com/yourusername/community-portal-event.git
cd community-portal-event
