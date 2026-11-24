V12: Campus Ride-Hailing Application
1. Product Overview
Babcock Keke is a proposed mobile ride-hailing application that connects
students of Babcock University with available Keke (tricycle) drivers
operating within the university and, subject to approval, nearby areas.

The application will allow students to request a ride, select a pickup
point and destination, view an estimated fare, and receive information
about the assigned driver. Drivers will be able to register, indicate
when they are available, receive ride requests, and manage accepted
trips.

The purpose of the product is to make finding and requesting Keke
transportation easier, more organized, and more transparent for
students. The first version will focus on the essential functions needed
to request, assign, and complete a ride.
2. Problem Statement
Students at Babcock University may have difficulty finding an available
Keke when they need transportation. They may have to search for a driver
physically, wait without knowing when a Keke will become available, or
negotiate a fare without having a clear estimate beforehand.

These challenges can lead to wasted time, uncertainty, and an
inconvenient transportation experience.

There is an opportunity to provide a centralized platform where students
can request Keke rides and where participating drivers can receive and
manage those requests.

Proposed solution: Develop Babcock Keke, a mobile application that
matches students requesting transportation with available, registered
Keke drivers and provides clear ride and fare information.
3. Target Users
3.1 Student passengers
Babcock University students who need transportation around campus or
within any additional service areas approved for the product.

Their needs include: - Finding an available Keke without searching
physically. - Selecting a pickup point and destination. - Knowing the
estimated fare before confirming a request. - Seeing the assigned
driver's details and ride status. - Knowing when a driver has accepted
or cancelled a request.
3.2 Keke drivers
Keke drivers approved to provide rides through the platform.

Their needs include: - Creating and managing a driver account. -
Indicating whether they are available to accept rides. - Receiving and
responding to ride requests. - Viewing passenger pickup and destination
details. - Managing the status of an accepted trip.
3.3 Platform administrator
A person or team responsible for operating and supervising the platform.

Their needs include: - Reviewing and approving driver registrations. -
Managing student and driver accounts. - Monitoring ride requests and
completed trips. - Handling reports and complaints. - Managing service
areas and fare rules.
4. User Stories
User stories describe what each type of user should be able to do and
why.
4.1 Student user stories
- As a student, I want to create an account and log in so that I can
  use the ride service.
- As a student, I want to select my pickup location so that a driver
  knows where to meet me.
- As a student, I want to enter my destination so that the system can
  identify the trip I need.
- As a student, I want to see an estimated fare before requesting a
  ride so that I can decide whether to proceed.
- As a student, I want to request a Keke so that I can be connected
  with an available driver.
- As a student, I want to know when a driver accepts my request so
  that I know my ride has been arranged.
- As a student, I want to see the driver's name and vehicle details so
  that I can identify the assigned driver.
- As a student, I want to cancel a request when necessary so that I am
  not committed to a ride I no longer need.
- As a student, I want to view my previous rides so that I can review
  my trip history.
- As a student, I want to rate or report a completed ride so that I
  can provide feedback about the service.
4.2 Driver user stories
- As a driver, I want to register and submit my details so that I can
  be considered for approval to use the platform.
- As a driver, I want to go online or offline so that I can control
  when I receive requests.
- As a driver, I want to receive ride requests with pickup and
  destination details so that I can decide whether to accept them.
- As a driver, I want to accept or reject a request so that I can
  manage my work.
- As a driver, I want to update a trip's status so that the student
  knows whether I have arrived, started the trip, or completed it.
- As a driver, I want to view my completed rides so that I can keep
  track of my activity.
4.3 Administrator user stories
- As an administrator, I want to review driver applications so that
  only approved drivers can accept rides.
- As an administrator, I want to view and manage user accounts so that
  I can address misuse of the platform.
- As an administrator, I want to view ride records so that I can
  monitor platform activity.
- As an administrator, I want to manage fare rules and service areas
  so that the platform operates according to agreed policies.
- As an administrator, I want to review complaints so that reported
  problems can be investigated.
5. Requirements
5.1 Functional Requirements
Functional requirements describe what the system must do.
  ID                      Requirement             Priority
  FR-01                   The system shall allow  Must have
students to register
and log in using the
required account
details.                

  FR-02                   The system shall allow  Must have
drivers to register and
submit the information
required for approval.  

  FR-03                   The system shall allow  Must have
administrators to
approve or reject
driver registrations.   

  FR-04                   The system shall allow  Must have
students to select or
enter a pickup location
and destination.        

  FR-05                   The system shall        Must have
display an estimated
fare before a student
confirms a ride
request.                

  FR-06                   The system shall allow  Must have
a student to submit a
ride request.           

  FR-07                   The system shall make   Must have
eligible ride requests
available to online,
approved drivers.       

  FR-08                   The system shall allow  Must have
a driver to accept or
reject a ride request.  

  FR-09                   The system shall notify Must have
the student when a
driver accepts or a
request cannot be
fulfilled.              

  FR-10                   The system shall        Must have
display the assigned
driver's available
identification and
vehicle details to the
student.                

  FR-11                   The system shall allow  Must have
the driver to update
the ride status,
including arrival, trip
started, and trip
completed.              

  FR-12                   The system shall allow  Should have
students and drivers to
cancel a ride subject
to defined cancellation
rules.                  

  FR-13                   The system shall store  Must have
records of ride
requests and completed
trips.                  

  FR-14                   The system shall allow  Should have
students to view their
ride history.           

  FR-15                   The system shall allow  Should have
students to submit a
rating or report after
a completed ride.       
FR-16                   The system shall        Must have
provide administrators
with tools to manage
users, drivers, rides,
complaints, and fare
rules.
5.2 Non-functional Requirements
Non-functional requirements describe the quality and operating standards
of the system.
  ID                                  Requirement
  NFR-01: Usability                   The application should have a
simple, clear interface that
students and drivers can use with
minimal guidance.

  NFR-02: Performance                 The application should respond
promptly to common actions under
normal network conditions.

  NFR-03: Reliability                 Ride requests and status changes
should be saved accurately and
should not be lost during normal
operation.

  NFR-04: Security                    Passwords and sensitive account
information must be protected, and
access must be restricted according
to user roles.

  NFR-05: Privacy                     The application should request
location permission only when
needed and should limit access to
personal and location information.

  NFR-06: Compatibility               The first release should support
the agreed target mobile operating
systems and commonly used devices.

  NFR-07: Availability                The service should be accessible
during its approved operating
hours, subject to network and
hosting availability.

  NFR-08: Maintainability             The software should be structured
so that developers can test, fix,
and extend it without unnecessary
changes to unrelated features.
NFR-09: Scalability                 The system should be capable of
supporting an increase in
registered students, drivers, and
ride requests.
6. Minimum Viable Product (MVP)
The Minimum Viable Product is the smallest useful version of Babcock
Keke that can demonstrate the core ride-request process.

The MVP should include:
1. Student registration and login.
2. Driver registration and administrator approval.
3. Student pickup and destination selection.
4. Driver online and offline availability.
5. Ride request creation.
6. Driver receipt and acceptance or rejection of requests.
7. Estimated fare display.
8. Student notification when a driver accepts a request.
9. Display of assigned driver and vehicle details.
10. Basic ride status updates.
11. Recording of completed rides.
12. A basic administrator interface for managing drivers and ride
    records.
Suggested features for later versions: - Live driver tracking on a
map. - In-app card or bank-transfer payments. - Scheduled rides. - Promo
codes and referral rewards. - Advanced driver earnings analytics. -
Emergency assistance features. - Multiple vehicle categories.

These features may be added after the core service has been tested with
students and drivers.
7. Acceptance Criteria
Acceptance criteria define the conditions that must be met for a feature
to be considered complete.
  Feature                             Acceptance criteria
  Student registration                A student can submit valid required
details and create an account. The
system rejects invalid or
incomplete details and provides a
useful error message.

  Student login                       A registered student can log in
with correct credentials. Incorrect
credentials do not grant access.

  Driver registration                 A driver can submit the required
registration details and see
whether the application is pending,
approved, or rejected.

  Driver approval                     An administrator can review a
driver application and approve or
reject it. Only approved drivers
can receive ride requests.

  Location selection                  A student can select a pickup
location and destination. The
selected locations are shown for
review before requesting a ride.

  Fare estimate                       The system displays an estimated
fare before the student confirms
the request.

  Ride request                        A student can submit a ride request
and see that it is waiting for a
driver.

  Driver availability                 An approved driver who is online
and not handling another active
ride can receive eligible requests.
An offline or busy driver cannot be
assigned a new ride.

  Request response                    A driver can accept or reject a
request. The system updates the
request status accordingly.

  Booking confirmation                When a driver accepts a request,
the student receives confirmation
and can view the assigned driver's
details.

  Ride status                         The driver can update the trip
through the defined stages. The
student can see the latest status.

  Ride completion                     A driver can mark a trip as
completed, and the system saves the
completed ride record.

  Ride history                        A student can view previously
completed rides associated with
their account.
Administration                      An authorized administrator can
access the management interface and
perform permitted management
actions.
8. Scope
8.1 In scope for the proposed MVP
- A mobile application for student passengers and Keke drivers.
- Separate student and driver account roles.
- Driver registration and approval.
- Pickup and destination selection.
- Ride requests and driver assignment.
- Fare estimates.
- Basic booking notifications.
- Driver and vehicle information.
- Ride status management.
- Ride record storage.
- Basic administrator management tools.
8.2 Out of scope for the proposed MVP
- Car, motorcycle, or bus ride-hailing.
- Food and parcel delivery.
- Inter-city transportation.
- Operations outside the approved service area.
- Advanced loyalty and reward programmes.
- Automated driver payouts.
- Complex promotional campaigns.
- Scheduled or recurring bookings.
9. Priorities
Priorities indicate which features should receive attention first during
development.
  Priority                Meaning                 Features
  P0 -- Must have         Essential for the core  Student and driver
service to function     accounts, driver
approval, location
selection, ride
requests, driver
acceptance, fare
estimates, ride status,
and ride records

  P1 -- Should have       Important improvements  Cancellation rules,
that can follow the     ride history, ratings,
core workflow           reports, and expanded
admin tools
P2 -- Could have        Useful additions for    Live map tracking,
future releases         digital payments,
scheduled rides,
referrals, promotions,
and advanced analytics
The team should complete and test P0 features before prioritizing P1 and
P2 features.
10. Unanswered Questions
The following questions must be discussed and resolved by the team
before development begins.
1. Service area: Will the application operate only within Babcock
   University, or will it also cover nearby areas?
2. Driver participation: Will the platform use existing Babcock
   Keke drivers, recruit new drivers, or accept both?
3. University approval: What permissions are required from the
   university before the service can operate?
4. Application structure: Will students and drivers use one
   application with separate account roles or two separate
   applications?
5. Payment method: Will students pay drivers in cash, pay online
   through the application, or have both options?
6. Fare calculation: Will fares be fixed for specific routes,
   calculated by distance, or set by drivers?
7. Platform revenue: Will the platform charge drivers a commission,
   a subscription fee, or no fee during the initial pilot?
8. Driver verification: What documents or identification will
   drivers need to submit?
9. Operating hours: Will the service operate throughout the day or
   only during approved hours?
10. Ride cancellation: What cancellation rules should apply to
    students and drivers?
11. Passenger capacity: Will the application support only individual
    bookings or allow multiple passengers travelling together?
12. Technology and budget: What development tools, hosting services,
    and budget will the team use?
13. Safety and complaints: Who will handle emergencies, complaints,
    and reports involving drivers or passengers?
14. Pilot testing: How many students and drivers should participate
    in the initial test?
These questions are intentionally left open for team discussion rather
than treated as confirmed product decisions.