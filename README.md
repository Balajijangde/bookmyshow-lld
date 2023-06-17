# BookMyShow LLD

## Requirements

Bookmyshow is an app where event organizers can organize different kinds of shows eg. standup comedy, movies, opera etc. so our basic requirement is to create 2 application, from which 1 is for event organizer where they can put details about event and all and 2nd app is for clients where they can book tickets for specified event.

## Actors

1. Event organizer
2. Audience
3. System

### 1. Event Organizer

Its the people who are responsible for creating and organizing events, they have different repsonsibilities to play like below.

- Registration / Login
- Create an event (event name, timing, place, no. of tickets, language, all details)
- Can edit event
- Provide food/meal/drink options
- Can cancel event
- Define base price for tickets
- Can provide seats locations and hall orientation, so clients can book specific seat
- Can provide coupon
- Provide event expiration time

### 2. Audience

The people who are going to attend event.

- Registration / Login
- Select an event
- Check availability of an event
- Book event
- Use online generated ticket for entry

### 3. System

The responsibilities of system

- Assist registration and logging in of audience organizers both
- have KYC for organizers
- Publish events created by organizers
- Show nearby events to audience
- Show availability of a show to audience
- Let people book tickets for events
- Coupon/ offers
- Generate e ticket for audience
- Take base ticket fare and convenience fee from customer
- Delete an event in its expiration time (eg. for movies its half hour before )

## Sequence of events

The sequence of operations will be happening on application

1.  Organizer registration, with KYC (organizer)
2.  Organizer validation and enable organizer to create events (system)
3.  Organizer creates events defining name, place, language, type, base pricing, timing and all (organizer)
4.  Event gets published in web (system)
5.  User registration/ log in (audience)
6.  Fetch user's current location (system)
7.  Suggests shows on current city to audience (system)
8.  User select event to attend and book a available seat (audience)
9.  System provide different food/ meal options (system)
10. System asks for base ticket price + convenience fee from user (system)
11. On successful booking, generate an e-ticket for user entry (system)
12. Remove event from list on its expiration time (system)
