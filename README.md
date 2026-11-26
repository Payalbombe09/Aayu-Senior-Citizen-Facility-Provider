# Senior Citizens Facility Provider App

A health and safety app for senior citizens, designed to be simple enough
for elderly users and useful for their children and caregivers.

## Features
- **SOS emergency:** confirmation screen, then doctor call, caregiver alert,
  GPS/address sharing, and a medical snapshot sent to the doctor
- **Ambulance request:** raised by the doctor or authorized user and sent to
  a provider; status shown only when the provider confirms
- **Medicine reminders:** multiple doses per day, taken/missed tracking, history
- **Doctor appointments:** reminders, edit, cancel, mark as completed
- **Doctor-prescribed routine:** medicines, exercise, diet, checkups, kept
  separate from personal reminders
- **Health records:** BP, sugar, weight, reports, prescriptions, secure uploads
- **Caregiver and doctor management:** role-based access, doctor verification
- **Accessible UI:** large buttons, readable text, minimal navigation

## Tech stack
React (PWA) | Node.js + Express | MySQL | JWT auth | Firebase Cloud Messaging
| SMS gateway (MSG91/Twilio) | Private file storage

## Repository contents
- `/docs`: design document, ER diagrams, database schema
- `/design`: wireframes and clickable prototype (PDF)
- `/backend`: REST API, scheduler, SOS and ambulance services
- `/frontend`: web/mobile client
- `/database`: SQL schema and seed data

## Note
This app assists emergency response and does not replace calling emergency
services (112 / 108 in India). Ambulance and call integrations may be
simulated in the demo build.

## License
MIT
