# University Event Registration and Participant Management System

Eastern Samar State University – Salcedo Campus
CPE 315 – Developing Cloud Native Applications (1st Semester, SY 2026-2027)

*Live website:* https://jcadayong07-lab.github.io/essu-event-registration/

## Group members
- Barcial, Ma. Lucelle Rose M.
- Cadayong, Joshua M.
- Duran, John Elbert P.

BSCpE 3-2 | Submitted to: Dr. Joseph G. Acebo

## About
A web-based system where students register for university events and administrators manage events, participants and registrations in one place.

## Features
*Students*
- Sign up and log in with a Student ID (format 24-00341) and Gmail address
- Browse available events and register online
- View, filter and cancel their registrations
- Update their profile and change their password
- Reset a forgotten password by email

*Administrators*
- Add, edit and delete events, with date, time, venue, slots and status
- View and search participants and registrations
- Approve or cancel registrations
- View a registration summary and download a report

## Technologies
- HTML, CSS and JavaScript (front end)
- Firebase Authentication (login and password reset email)
- Cloud Firestore (online database) with security rules
- GitHub Pages (hosting)

## How to try it
1. Open the live website.
2. Choose the *Student* tab and click *Sign up* to create a student account.
3. Log in, open *Events*, and register for an event.
4. An administrator account is available for the instructor on request.

## Deployment note
Hosted on *GitHub Pages* as a static site. Data is stored online in *Firebase (free Spark plan)*, so registrations are shared across devices.